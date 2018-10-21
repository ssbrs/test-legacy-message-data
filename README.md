A binary for testing whether the rust [legacy data implementation](https://github.com/ssbrs/legacy-msg-data) correctly handles the [test data set](https://github.com/sunrise-choir/legacy-value-testdata).

To use this, clone the [implementation](https://github.com/ssbrs/legacy-msg-data) and this repo into the same directory, so that the file-system import works. Then execute `cargo run`. If it returns with exit code 0, then the implementation correctly handles the test data set. Else, you should get some helpful output into the console telling you where the rust implementation differs from the test data.
