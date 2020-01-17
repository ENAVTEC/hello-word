English ·
[hola mundo]() ·
# hello-word
siguiendo el manual


## Bind
  A set of std::function utilities like NullFunction and DoNothing.

## Check
  A set of macros for better programming error handling.

```cpp
void Foo(void* ptr) {
  // Aborts in debug build.
  RST_DCHECK(ptr != nullptr);
  // Aborts in debug and release builds.
  RST_CHECK(ptr != nullptr);
  // RST_DCHECK(false) actually.
  RST_NOTREACHED();
}
```
