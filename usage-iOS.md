# 配置指南（iOS）

## Cisco AnyConnect

1. 从App Store安装“Cisco AnyConnect"
2. 打开App "AnyConnect"
3. 选择Connections -> Add VPN Connection…
4. Decription输入自定义名称
5. Server Address填写vpn.zlix.tech
6. Advanced -> Certificate 选择 Disable
7. 保存VPN配置并返回首页
8. 连接VPN，根据提示输入用户名密码

## PPTP

1. 打开Settings->VPN->Add VPN Configuration
2. Type选择PPTP
3. Description输入自定义名称
4. Server输入所需服务器地址
5. Account填写用户名
6. Password填写密码（如不填则会每次连接时询问）
7. 确认勾选Send All Traffic（默认勾选）
8. 点击右上角的Done，然后连接VPN

## L2TP

1. 打开Settings->VPN->Add VPN Configuration
2. Type选择L2TP
3. Description输入自定义名称
4. Server输入所需服务器地址
5. Account填写用户名
6. Password填写密码（如不填则会每次连接时询问）
7. Secret填入ustcaf
8. 确认勾选Send All Traffic（默认勾选）
9. 点击右上角的Done，然后连接VPN

## OpenVPN

1. OpenVPN已在中国App Store下架。请先注册一个非中国区的Apple ID（比如美国区）。
2. 使用这个账号登录App Store
3. 在App Store中搜索并下载OpenVPN
4. 打开配置文件，打开程序选择OpenVPN
5. 打开OpenVPN，点击+号，确认导入配置
6. 输入用户名密码，连接。

## IKEv2（iOS 8 or later）（部署中）
