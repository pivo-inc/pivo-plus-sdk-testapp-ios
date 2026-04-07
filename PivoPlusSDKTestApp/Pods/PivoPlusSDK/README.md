# Pivo Plus SDK

Pivo Plus SDK is an iOS Framework which can be used to:
- Connect with Pivo
- Control Pivo
- Tracking with Pivo (feature-based licensing)

The Plus SDK supports feature-based tracking mode gating. Available tracking modes are determined by the `features` array in the license key:
- `action` — Object tracking
- `face` — Face tracking
- `body` — Human body tracking
- `horse` — Horse tracking

For more information about Pivo: [getpivo.com](https://getpivo.com)

For more information of the SDK and contact to get license to use the SDK: https://developer.pivo.app/

## Installation

### CocoaPods

Add the following to your `Podfile`:

```ruby
pod 'PivoPlusSDK', :git => 'https://github.com/pivo-inc/pivo-plus-sdk-ios.git', :tag => '1.0.0'
```

Then run:

```bash
pod install
```

## Changelogs

In version 1.0.0:
- Initial release of Pivo Plus SDK
- Feature-based tracking mode gating via license `features` array
- Support for Object, Face, Human, and Horse tracking
- Easing function enabled
