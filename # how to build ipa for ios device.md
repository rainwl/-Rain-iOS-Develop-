 # ios ipa build
## 如何打包ipa
- unity打包，然后xcode打开包里面的xcodeproj
- 选择any ios device, 然后edit scheme，选择release
- 然后product->Build
- 然后在左侧的文件栏里面，找product文件夹，找到里面的.app
- 从访达中打开，然后新建一个文件夹，叫“Payload”，将app拖进去，压缩，压缩后扩展名改成.ipa
- 用爱思助手可安装