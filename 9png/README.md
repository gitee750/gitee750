# .9.png启动页面实例
HBX的安卓端只提供的三个启动页图片，在全面屏上会明显变形。 
使用9png图片可以制作上中下左右五个方向固定内容的启动图片，满足大多数启动页的要求。 
[用一张正方形图片搞定安卓启动页-dcloud论坛连接](https://ask.dcloud.net.cn/article/37365)
此方法可以做出微信、抖音、微博等应用的启动页适配效果。 
最新的HBX已经支持.9.png的云打包。 

# 注意事项
* 此方案不能满足用照片做背景的需求，会导致拉伸变形；建议使用纯色背景。
* 图片分辨率不能太小，否则在高分辨率手机上会导致内容过小。

# 效果预览操作步骤
1. 使用HBX导入此插件项目。 
2. 打开manifest.json，选择“APP图标配置”后点击“自动生成所有图标并替换”。 
3. 进行云打包后安装启动即可预览效果。 

# 目录结构
+ static `静态资源`
	- logo.png `图标`
	- splash.9.png `主角：启动页正方形.9.png图片；`

# 免费帮助
如你需要制作一张简单的.9.png的启动页，但又没有图片的编辑环境时；
可以把你的需求发至的我邮箱,我空闲时可以免费帮忙制作。 
邮箱账号：xiaohui.brook@foxmail.com

需求中应该包含： 
背景颜色、内容（文字内容、图标等）、显示区域（上中下左右）等基础信息。