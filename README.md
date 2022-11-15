反向看戏，脑抽常有；若看到我的项目请自重



@echo off
systeminfo >> .\parameter.txt
Netsh WLAN show drivers >> .\NetworkDrivers.txt
wmic nic list brief >> .\Network.txt
echo 配置已导出
echo _________________________________
