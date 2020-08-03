all:
	clang++ -Os -target arm64-apple-ios8.0 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk -o unicornvm_apitest -I../include -L../dylib -lunicornvm -framework Foundation -std=gnu++14 -stdlib=libc++ ./apitest.mm
	clang++ -Os -target arm64e-apple-ios8.0 -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk -o unicornvm_apitest_e -I../include -L../dylibe -lunicornvm_e -framework Foundation -std=gnu++14 -stdlib=libc++ ./apitest.mm
