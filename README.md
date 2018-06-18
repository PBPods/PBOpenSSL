# PBOpenSSL

TLS/SSL and crypto library

[openssl.org](https://www.openssl.org)

**Build detail**: toolchain version, minimal requiest OS version.

| version          | Xcode | SDK version           | iOS  | watchOS | tvOS | macOS | bitcode |
| ---------------- | ----- | --------------------- | ---- | ------- | ---- | ----- | ------- |
| 1.1.008 (1.1.0h) | 9.4   | iOS 11.4              | >8.0 | NA      | >9.0 | NA    | ✓       |
| 1.1.007 (1.1.0g) | 9.2   | iOS 11.2              | >8.0 | NA      | >9.0 | NA    | ✓       |
| 1.0.215 (1.0.2o) | 9.4.1 | iOS 11.4              | >8.0 | NA      | >9.0 | NA    | ✓       |
| 1.0.214 (1.0.2n) | 9.4.1 | iOS 11.4              | >8.0 | NA      | >9.0 | NA    | ✓       |
| 1.0.212 (1.0.2l) | 9.2   | iOS 11.2              | >8.0 | NA      | >9.0 | NA    | ✓       |

Build with script via [x2on/OpenSSL-for-iPhone](https://github.com/x2on/OpenSSL-for-iPhone)

## Usage

```
// Add at the beginning of your podfile
source 'https://github.com/PBPods/PBOpenSSL.git'

// May also need to add the master repo manually
source 'https://github.com/CocoaPods/Specs.git'

pod 'openssl', '~> 1.0.212'
```

## Others

I must agress [@st3fan](https://github.com/st3fan/ios-openssl) said:

> OpenSSL is not a good choice for getting access to crypto primitives or for SSL/TLS networking in iOS applications.
>
> Instead, you should use the iOS provided libraries.
>
> The native iOS Security and Networking Frameworks will always be more up to date and receive regular security fixes as part of iOS upgrades.
