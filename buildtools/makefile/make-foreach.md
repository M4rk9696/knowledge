# foreach in Makefile

[Back](../buildtools.md){: .button}

### Syntax:

```sh
$(foreach var,list,text)
```

### Use Case:

This is used

```sh
FILES=$(foreach file,$(NAMES),"$(file).lua")
```

### Reference:

- [GNU foreach Reference](https://www.gnu.org/software/make/manual/html_node/Foreach-Function.html)

