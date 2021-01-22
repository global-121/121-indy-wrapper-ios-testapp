Tests for the 121 Indy Wrapper
------------------------------

These are the tests for the [Cordova plugin](https://github.com/global-121/121-indy-wrapper-ios) that wraps [Hyperledger Indy](https://www.hyperledger.org/projects/hyperledger-indy)
functionality for the [Red Cross 121 project](https://www.121.global).

### Prerequisites

   * Install [NodeJS](https://nodejs.org/).
   * Install [Xcode](https://developer.apple.com/xcode/).
   * Install the Hyperledger Indy SDK and start a [local pool](https://github.com/hyperledger/indy-sdk#how-to-start-local-nodes-pool-with-docker).

### Run tests

The first time you run the tests, execute:

    cd testapp
    npm install
    npm run ios

This will open the iOS simulator and runs the test app.
Click 'Auto Tests' to execute the tests.

When you've made changes and wish to run the tests again, execute:

    npm run ios-reload

---

## License

Released under the Apache 2.0 License. See [LICENSE](LICENSE).
