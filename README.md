# FreeFireMaxProxyUI

A SwiftUI visual recreation of the supplied reference screen with three UI panels:
- Proxy
- Định Vị
- Mod NV

The UI includes functional demo toggles, a bundled `cache_res.unity3d` resource, and a "MỞ GAME" button that attempts to open Free Fire MAX through supported URL schemes.

Important: the bundled asset is not executed or used to modify Free Fire. This project does not implement proxy injection, memory editing, ESP extraction, anti-cheat bypass, or other game modification.

The supplied original IPA was inspected only for metadata. Its bundle identifier is `com.apple.mobile.MobileHouseArrest` and it declares the custom URL scheme `threeoneosfive`; that scheme is not used to bypass or modify the original app.

Build requirements:
- macOS + Xcode
- iOS 16+
- Your own Apple Development signing identity to export an installable IPA
