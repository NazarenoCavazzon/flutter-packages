By default, go_router_flow comes with default error screens for both `MaterialApp`
and `CupertinoApp` as well as a default error screen in the case that none is
used. You can also replace the default error screen by using the
[errorBuilder](https://pub.dev/documentation/go_router_flow/latest/go_router_flow/GoRouter/GoRouter.html)
parameter:

```dart
GoRouter(
  /* ... */
  errorBuilder: (context, state) => ErrorScreen(state.error),
);
```
