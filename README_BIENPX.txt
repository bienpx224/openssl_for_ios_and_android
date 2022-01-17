export ANDROID_NDK_ROOT=/Users/bienpx224/Library/Android/sdk/ndk/21.3.6528147
cd tools

export api=16
####### armeabi-v7a
./build-android-openssl.sh arm

export api=21
####### arm64-v8a
./build-android-openssl.sh arm64    

./build-android-openssl.sh x86

./build-android-openssl.sh x86_64