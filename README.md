
部署：https://dashboard.heroku.com/new?template=https://github.com/liuzhijie443/special-disco
## 0. 注意

部署需要注册heroku帐号

## 1. 验证

服务端部署后，地址补上path后(例如：<https://test.herokuapp.com/static>)访问显示404页面，表示部署成功。

## 2. 客户端配置

二维码地址： https://test.herokuapp.com//img_4643e19301a5437c90c947e95cd4d60f/v2.png

配置文件地址：https://test.herokuapp.com//img_4643e19301a5437c90c947e95cd4d60f/

打开后复制，在客户端导入即可。

```sh
服务器地址: test.herokuapp.com
端口: 443
密码: 部署时填写的密码
解密方式： RC4-MD5
插件程序: ./v2/v2ray.exe
插件选项: path=/4643e19301a5437c90c947e95cd4d60f;host=ssr1.k452b.cn;tls
命令行参数: -mode websocket
Path： path=/4643e19301a5437c90c947e95cd4d60f;host=ssr1.k452b.cn;tls
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0MGU3MDdlNzIyZGQ0MmVmOTEwYTcyNTA3NzI5NzQyNw@superk452b.herokuapp.com:443/?plugin=.%2fv2%2fv2ray.exe%3bpath%3d%2f4643e19301a5437c90c947e95cd4d60f%3bhost%3dsuperk452b.herokuapp.com%3btls
```

Android：

[shadowsocks](https://github.com/shadowsocks/shadowsocks-android/releases/download/v5.0.5/shadowsocks--universal-5.0.5.apk) [v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin-android/releases/download/v1.3.1/v2ray-arm64-v8a-1.3.1.apk)

windows:

<https://github.com/shadowsocks/shadowsocks-windows/wiki/Shadowsocks-Windows-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E>
