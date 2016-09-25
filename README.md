# Medit

A creative WYSIWYG rich text editor for mobile device by javascript.

一个创新型的移动端所见即所得富文本编辑器。

Demo Adress : [Medit Demo](https://echosoar.github.io/medit/demo/demo.html)

***

### How to use 如何使用：
	
	// first, import "medit.js" to your html file.
    <script src="../src/medit.js"></script>
	
	// second, initial object,you can use "new medit(DOM Element)" or "medit(DOM Element)".
	var meditObject = medit(document.getElementById("meditContainer"));
	
	// if you wanna get content
	meditObject.getContent();
	
	// if you wanna auto save
	meditObject.autoSave("autoSaveId", function(data, timestamp){
		console.log(data, timestamp);
	});
	

***

### Current support 目前支持:

***

##### Basic function 基础功能:

![add left](./src/images/add-left.png) Add To Left 向当前块左部添加内容

![delete](./src/images/close.png) Delete 删除当前块

![ok](./src/images/ok.png) Ok 完成当前块编辑

![mode](./src/images/mode.png) Mode 选择当前块类型

![add right](./src/images/add-right.png) Add To Right 向当前块右部添加内容

***

##### Text Edit 文本编辑:

![bold](./src/images/text/bold.png) Bold 加粗

![italic](./src/images/text/italic.png) Italic 斜体

![underline](./src/images/text/underline.png) Underline 下划线

![size](./src/images/text/size.png) Font-size 文字大小

+ ![sizebigger](./src/images/text/sizeBigger.png) Enlarge Font-size 增大文字

+ ![sizeSmaller](./src/images/text/sizeSmaller.png) Narrow Font-size 缩小文字

![color](./src/images/text/color.png) Color 文字颜色

+ ![black](./src/images/text/colorBlack.png) Black 黑色

+ ![red](./src/images/text/colorRed.png) Red 红色

+ ![green](./src/images/text/colorGreen.png) Green 绿色

+ ![blue](./src/images/text/colorBlue.png) Blue 蓝色

+ ![yellow](./src/images/text/colorYellow.png) Yellow 黄色

+ ![pink](./src/images/text/colorPink.png) Pink 粉色

Text selected by gesture 文本手势选择

![text select](./demo/demo-gesture.gif)

***

##### Super Links 超链接:

![setting](./src/images/link/setting.png) Setting 超链接设置

![/cancel-link](./src/images/link/cancel-link.png) Cancel Super Link 取消超链接

![link demo](./demo/demo-link.gif)

***

##### Image 图片:

![setting](./src/images/image/setting.png) Setting 图像设置

![biger](./src/images/image/biger.png) Increase size 尺寸增大

![smaller](./src/images/image/smaller.png) Shrink size 尺寸缩小

![upload](./src/images/image/upload.png) Upload image from user local device 从用户本地上传图片



© 2016




 

