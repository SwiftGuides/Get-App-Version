# Get-App-Version
This is used to get Dynamic App Version of the App. 


Source :- https://stackoverflow.com/a/40961427/10422074

```swift
        if let version = Bundle.main.infoDictionary?["CFBundleShortVersionString"] as? String {
            print(version)
            AppVersion.text = "v\(version)"
        }
```
