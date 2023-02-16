# test_electron_app


To build MAC intel package:
npm exec electron-packager . -- --platform=darwin --arch=x64 --overwrite=true --out=builds/

To build MAC M1 package: 
npm run prepare -- --debug --arch='arm64' --version='21.3.0'
npm exec electron-packager . -- --platform=darwin --arch=arm64 --overwrite=true --out=builds/

 
