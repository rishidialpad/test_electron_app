# test_electron_app


To build MAC intel package:
npm exec electron-packager . -- --platform=darwin --arch=x64 --overwrite=true --out=builds/

To build MAC M1 package: 
npm exec electron-packager . -- --platform=darwin --arch=arm64 --overwrite=true --out=builds/