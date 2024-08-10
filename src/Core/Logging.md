# Logging
There are five logging macros available:
```cpp
HX_GAME_TRACE()
HX_GAME_INFO()
HX_GAME_WARNING()
HX_GAME_ERROR()
HX_GAME_FATAL()
```

You can also log variables:
```cpp
int a = 7;
HX_GAME_TRACE("a = {0}", a);
```