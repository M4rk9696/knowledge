# Bash read config file and store value from config file

[Back](./bash.md)

## Reading config file

This should be enough to read variables which are stored in a file

```bash
source file.config
```

## Update value in a config file

```bash
sed -c -i "s/\($TARGET_KEY *= *\).*/\1$REPLACEMENT_VALUE/" $CONFIG_FILE
```
