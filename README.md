# myProxy
使用Go语言实现socks5协议

经验证亦可以在arm架构的设备上代理网络

GOOS=linux GOARCH=arm go build myProxy.go

e.p. ./myProxy --listen 0.0.0.0:9999
