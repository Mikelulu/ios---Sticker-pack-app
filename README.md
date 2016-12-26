# ios---Sticker-pack-app

iMessage app 是iOS10中嵌入到Message内容的iMessage apps，包含简单的表情包以及自定义的复杂界面。

iMessage App类别：

* Sticker pack app ：单独的表情包应用，不需要编写任何代码，只需拖动图片即可，包括静态和动态表情。

* iMessage app ：单独的iMessage应用，要编写代码，可以发送表情包、文字、视频、音频。

上面两个也可以以一个app的扩展嵌入到iMessage应用中。

 

一、创建独立的表情包应用（Sticker pack app）：无需代码

 

表情包限制：

* Small ：100 x 100 @3x scale (300 x 300 pixel image)

* Medium : 136 x 136 @3x scale (378 x 378 pixel image)

*Large : 206 x 206 @3x scale (618 x 618 pixel image)

其他限制（表情包大小）：

* 文件中的 images 不可以大于500kb

* image 不可以小于100 x 100 pt (300 x 300 pixels)

*image 不可以大于206 x 206 pt (618 x 618 pixels)

*image 格式必须是PNG、APNG、JPEG、GIF
