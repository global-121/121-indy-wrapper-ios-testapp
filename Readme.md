Tests for the 121 Indy Wrapper
------------------------------

These are the tests for the [Cordova plugin][1] that wraps [Hyperledger Indy][2]
functionality for the [Red Cross 121 project][3].

### Prerequisites

   * Install [NodeJS][4].
   * Install [Xcode][5].
   * Install the Hyperledger Indy SDK and start a [local pool][6].

### Run tests

The first time you run the tests, execute:

    cd testapp
    npm install
    npm run ios

This will open the iOS simulator and runs the test app.
Click 'Auto Tests' to execute the tests.

When you've made changes and wish to run the tests again, execute:

    npm run ios-reload

[1]: https://github.com/global-121/121-indy-wrapper-ios
[2]: https://www.hyperledger.org/projects/hyperledger-indy
[3]: https://www.121.global
[4]: https://nodejs.org/en/
[5]: https://developer.apple.com/xcode/
[6]: https://github.com/hyperledger/indy-sdk#how-to-start-local-nodes-pool-with-docker
