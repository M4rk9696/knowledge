# Const Member Function

[Back](./cplusplus.md){: .button}

In a const member function `this` is `const`, and cannot be altered

```cpp
class A {
  public
  A() {}
  void test() const; // const member function
}
```
