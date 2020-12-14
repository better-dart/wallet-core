# Dart FFI: binding to dart.


- use `dart:ffi` to binding `wallet-core` for dart.


## quickstart:


- install:

```
make osx-install

```

- setup:

```
make ffi-setup

```

- gen binding codes:

```
make ffi-gen
```

## dart binding file:

- result: [dart/wallet_core_bindings.dart](./dart/wallet_core_bindings.dart)


## pubspec.yaml:

- about ffi gen part: [dart/pubspec.yaml](dart/pubspec.yaml)


## wallet core docs:

### build/release wallet core dynamic library:

- https://developer.trustwallet.com/wallet-core/developing-the-library/building
- https://developer.trustwallet.com/wallet-core/developing-the-library/releasing

### integration:

- https://developer.trustwallet.com/wallet-core/integration-guide/wallet-core-usage
- android: https://developer.trustwallet.com/wallet-core/integration-guide/android-guide


