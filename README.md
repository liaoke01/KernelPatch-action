# KernelPatch-action
# 1首先fork本项目
# 2修改配置文件config.env,boot-url是你手机内核下载地址,boot的提取以及上传下载，强烈建议用https://github.com/liaoke01/BootIMGExtractActio ，工作流运行完成之后直接复制artifacts中的Boot文件的下载链接。skey自行修改（magiskboot url不懂不要动
# 3 Actions界面执行本工作流，然后待修补完毕，滑到最下面，下载修补过后的内核。
# 4将修补过后的内核 rec or fastboot刷入
