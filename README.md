# Plant-detect-ios-sdk

## Example

```swift
let vc = PlantHealthViewController(token: "...")
// vc.modalPresentationStyle = .fullScreen
self.present(vc, animated: true)
```

## Permissions

Since this SDK includes camera and photo functionality, you must add permissions to your iOS app.

```plist
<key>NSCameraUsageDescription</key>
<string>We need access to your camera for capturing photos.</string>

<key>NSPhotoLibraryUsageDescription</key>
<string>We need access to your photo library to select and upload images.</string>
```
