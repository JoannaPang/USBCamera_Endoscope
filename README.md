# USBCamera_Endoscope
- Provide services for endoscope related work（select/cut/take photo）

###Origin APP版本
- 仅实现了页面三个按钮（登录/注册/拍照）
- 拍照功能需要登录后才可使用，可以点击切换本机所有摄像头

###Version 0.7
- 拟实现拍照操作，还未完成

###Version 1.0
- 拍照功能实现
- 可点击切换按钮切换设备摄像头
- 可点击拍照/重拍按钮拍摄照片
- 可点击保存按钮，将照片存储至本地storge/SDcard/Endoscope文件夹下

###Version 2.0
- 登录注册功能实现
- 附带了简单的Server.py配合测试
- 可进行用户 - 服务器的交互与通信

###Version 3.0
- 优化了前端
- 拍照功能改由YaYa APP完成
- 完善了Server.py的流程
- 使用方法：打开内窥镜，手机连接内窥镜wifi。拍照后上传图像，服务器返回结果

###Version 3.4
- 裁剪功能初步

###Version 4.0
- 裁剪功能实现，目前上传图像前必定经过裁剪步骤
- 服务器和端口号修改功能实现（暂时顶替注册功能位置，后续前端重新排版设计)

###Version 5.0
- 修改了应用名和应用图标
- 更改了登录/注册界面的位置，目前更新为  欢迎界面 - 登录/注册界面 - 主页面。即必须登录/注册后才可使用APP
- 修复了登录/注册时字体过浅的问题
- 修复了部分版本机型无法跳转图片裁剪的问题