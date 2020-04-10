# ios-secp256k1
Script that builds C library based on [bitcoin-core/secp256k1](https://github.com/bitcoin-core/secp256k1) for iOS

1. Support archs: i386, armv7, armv7s, arm64, x86_64  
2. Default sdk version is fetched from `xcodebuild -showsdks`  
3. run secp256k1.sh  

### Usage:

```shell
./secp256k1.sh
```


TODO: 

# configure: WARNING: unrecognized options: --disable-assembly
# can we build without copying the source code first?
# with  --host=none-apple-darwin, it gives
configure: WARNING: using cross tools not prefixed with host triplet
# ./configure: line 12132: PKG_PROG_PKG_CONFIG: command not found


