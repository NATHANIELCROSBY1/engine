This folder contains unit tests that are run with `kReleaseMode` set to true. This can be used for unit testing code that is guarded by this boolean, such as in cases where debug code is intentionally ellided for performance or code size reasons. The unit tests are still run in the VM and are not otherwise precompiled.

To run these test from the command line, use the command: `flutter test --dart-define=dart.vm.product=true test_release/`
