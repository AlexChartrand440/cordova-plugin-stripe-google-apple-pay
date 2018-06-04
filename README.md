# cordova-plugin-stripe-google-apple-pay
Cordova plugin for Google &amp; Apple pay integration

## Notes

This plugin only supports Android and iOS.

This plugin will add these dependencies to your build.gradle file:

```
com.stripe:stripe-android:6.1.2
com.google.android.gms:play-services-wallet:15.0.1
com.android.support:support-v4:27.0.2
com.android.support:appcompat-v7:27.1.1
```

## Installation

```
cordova plugin add cordova-plugin-stripe-google-apple-pay
```

## Usage

This plugin puts the functions into `window.sgap`.
All functions return a promise.

```
sgap.isReadyToPay()
```

 - Used to test if the appropriate payment method is available on the current device.
 - Resolves if successful, rejects if not, or if it encounters an error.


## Contributing

PRs welcome!

## License

MIT
