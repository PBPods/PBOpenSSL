# PBOpenSSL

TLS/SSL and crypto library 

https://www.openssl.org

**Build detail**: toolchain version, minimal requiest OS version.

| version          | Xcode | SDK version           | iOS  | watchOS | tvOS | macOS | bitcode |
| ---------------- | ----- | --------------------- | ---- | ------- | ---- | ----- | ------- |
| 1.0.212 (1.0.2l) | 9.2   | iOS 11.2              | >8.0 | NA      | >9.2 | NA    | ✓       |

Build with script via https://github.com/x2on/OpenSSL-for-iPhone


## Usage

```
// Add at the beginning of your podfile
source 'https://github.com/PBPods/PBOpenSSL.git'

// May also need to add the master repo manually
source 'https://github.com/CocoaPods/Specs.git'

pod 'openssl', '~> 1.0.212'
```
