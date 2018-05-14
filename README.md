# 二维码活码管理系统 v 2.0

### 什么是活码?

二维码生成后,二维码图案不变,内容可随时变更,极大提高营销效率,配合美术设计二维码能力大大提升.
并且可以做到实时统计二维码扫描数据,传播效果一目了然;根据地域/网络/设备等多维度分析数据,提升管理效率.

### 二维码的活码的技术实现本质是什么?

二维码活码团主要存储一个固定的 php 路径及码的 id,扫描二维码后,服务器根据请求内容从数据库中查找二维码的信息,作跳转并记录访问信息.

### 系统技术

![技术](info/1.png)

### 重点技术

1. 使用插件绘制二维码 
2. 查询数据库记录跳转页面


### 安装步骤

1. 导入 sql 数据库
2. 添加 conn_sql.php , 连接你自己的库
3. 修改 js 中 ajax 的请求地址 ( 连接你的服务器路径 )

### 效果演示:

[点击](//jxjweb.gz01.bdysite.com/2code/2code_web/index.html)

### 完整代码:

[github](//github.com/jxj322991/2code)

### TODO

-. 彩色二维码
