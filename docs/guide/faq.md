#### 支持的平台
    -目前仅支持高通AECX平台的AE模块。

#### 支持的图片格式
    -目前仅支持jpg,png。

#### 部分exif组件显示不全
    -程序是基于2k的高分屏开发，因此对于1080p的屏幕显示会出现部分组件遮挡。被遮挡部分的组件对于调试不影响。

#### 图片解析时间过长
    -图片解析时间过长，需要解析的数据比较大，涉及xml的读写因此较慢。借助平台的c7工具解析metadata信息，没办法加速，请耐心等待。

#### 生成缩略图时间常
    -图片列表太长需要生成的缩略图较多，此时程序界面会卡顿，请耐心等待。

#### tuning界面打开等待时间太长
    -tuning界面默认加载缩略图方便调试，因此加载时间较长，请耐心等待。

#### 图片拖拽到程序内ui界面提示无响应
    -请将图片拖拽到程序窗口内，会自动解析meta，然后再解析xml涉及的步骤将多，因此会阻塞ui界面，请耐心等待，且一次性不要将太多图片直接拖拽到程序窗口内，建议多图时直接使用导入图片文件夹的方式。
