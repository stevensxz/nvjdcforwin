# nvjdcforwin


# 第一步安装ASP.NET Core Runtime 5.0.12

安装地址:https://dotnet.microsoft.com/download/dotnet/5.0
下载之后无脑下一步

#下载WEB压缩包  

下载地址：https://www.lanzouw.com/i2cyvwchj1g

在仓库里解压压缩修改配置文件夹中的Config.json

# 下载浏览器

在解压的WEB文件夹中根目录创建一个.local-chromium\Win64-884014\chrome-win 这些文件夹

下载浏览器地址:https://mirrors.huaweicloud.com/chromium-browser-snapshots/

根据自己情况选择 884014 版本的浏览器 有WIN win64的 下载完成解压到.local-chromium\Win64-884014\里


# 最后启动 
 管理员打开CMD CD到web文件夹中  输入 dotnet NETJDC.dll --urls=http://*:5000
