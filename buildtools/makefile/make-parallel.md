# Make Parallel Builds

[Back](../../index.md#build-tools){: .button}

`make -j <number-of-threads>`

```make

.ONESHELL:
.DEFAULT: end

end: a b c d
  echo "Ending"

a:
  echo "Hello from A"

b:
  echo "Hello from B"

c:
  echo "Hello from C"

d:
  echo "Hello from D"

.PHONY: a b c d end

```
