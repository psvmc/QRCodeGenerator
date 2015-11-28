###二维码生成
####添加依赖
```swift
platform :ios
pod 'libqrencode', '~> 3.4.2' 
```

####使用方法(swift)
```swift
let url = "http://www.baidu.com";
self.image = QRCodeGenerator.qrImageForString(url, imageSize: 600);
```
