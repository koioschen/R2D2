# r2d2
1. 用于对Cacti的扩展，直接读取数据库数据，对阈值以及设备在线状态进行监控
2. 对X品牌的UPS进行监控，通过SNMP获取UPS供电状态及剩余电量
3. 内置syslog服务，并对关键字进行过滤产生告警
4. 对5680T的syslog进行分析，对PON口下线，以及PON未下线ONU批量下线的情况进行告警； 过滤只告警Losi下线原因
5. 对接微信企业号进行微信告警
6. 对接云之讯平台进行电话告警
7. 增加了值班表功能
8. 增加了数据包分析功能

2018年5月14日
1. 使用metronic框架修改了UI，更名为Orca
2. 修改了部分后台业务逻辑
3. 修复了用户添加的bug
