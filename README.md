curl-android-ios
================
The goal of this project is to provide a pre-compiled version of libcurl to be
used in Android and iOS.

It uses cURL from the upstream repository and it's updated frequently.

For Android, it also uses OpenSSL from its upstream repository.

If you want to build the library, scripts are provided for both platforms.
Test projects are also provided for both iOS and Android.

``sudo chown -R $USER:admin /usr/local/include``

``brew install autoconf automake libtool``

``git submodule init``

``git submodule update``

## We can't compile without socket() support!
Update xcode command line tools.
