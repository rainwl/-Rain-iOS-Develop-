# easy AR - Xcode配置

## unity内部配置


- bundle ID要与license Key一致
- target Architecture： IL2CPP，Architecture：Universal
- Camera Usage Description： use camera

## Xcode内配置
### 添加frameworks
- easyar.framework
- libc++.tbd
- Accelerate.framework
- AVFoundation.framework
- CoreGraphics.framework
- CoreImage.framework
- CoreMedia.framework
- CoreMotion.framework
- CoreVideo.framework
- OpenGLES.framework
- UIKit.framework
- ARKit.framework (以optional方式添加)
### 禁用bitcode
配置中禁用bitcode
