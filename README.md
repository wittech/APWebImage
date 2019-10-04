#  说明
采用SDWebImage 5.2.2版本
编译后，执行合并：
lipo -create /编译路径/Build/Products/Release-iphoneos/APWebImage.framework/APWebImage /编译路径/Build/Products/Release-iphonesimulator/APWebImage.framework/APWebImage -output /APWebImage/Products/APWebImage
