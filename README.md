# _2710
手游H5名扬三界梦幻西游手工架设一键服务端完整版_附架设教程
<br/></br>
[下载地址](https://www.uuid2.com/2710.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>手游H5名扬三界梦幻西游手工架设一键服务端修复版带小白架设教程<p>
<p>西游H5多区授权后台：修复部分BUG+异界+神器+ 除魔+三界+挖矿+灵装+授权后台+本地注册+内充<p>
<p>要求系统 Centos7.2<p>
<p>配置要求 2核 4G内存 宽带随意 建议5M<p>
<p>安装宝塔<p>
<p>yum install -y wget && wget -O install.sh http://download.bt.cn/install/install.sh && sh install.sh<p>
<p>★进入宝塔安装软件<p>
<p>选择左边一键安装<p>
<p>Nginx 1.14<p>
<p>mysql5.6<p>
<p>php5.4<p>
<p>phpMyAdmin 4.4<p>
<p>★添加数据库<p>
<p>宝塔 – 数据库 – root密码 修改密码为123456 其他不用动<p>
<p>mysql -u root -p123456<p>
<p>创建数据库<p>
<p>GRANT ALL PRIVILEGES ON *.* TO ‘root’@’127.0.0.1’ IDENTIFIED BY ‘123456’ WITH GRANT OPTION;<p>
<p>FLUSH   PRIVILEGES;<p>
<p>GRANT ALL PRIVILEGES ON *.* TO ‘root’@’localhost’ IDENTIFIED BY ‘123456’ WITH GRANT OPTION;<p>
<p>FLUSH   PRIVILEGES;<p>
<p>quit<p>
<p>★添加网站<p>
<p>宝塔 – 网站 – 添加站点 输入IP（例如：192.168.1.1）根目录/www/wwwroot/<p>
<p>★放行端口<p>
<p>宝塔 – 安全 – 放行端口 – 添加1:65535<p>
<p>★上传文件解压<p>
<p>xyh5.zip 上传根目录 并 解压<p>
<p>给权限 如果命令用不了 就手动宝塔给下权限<p>
<p>chmod -R 777 /root/config<p>
<p>chmod -R 777 /root/server<p>
<p>chmod -R 777 /www/wwwroot<p>
<p>输入口令<p>
<p>ldconfig<p>
<p>yum install gcc* -y<p>
<p>yum install libtocmalloc* -y<p>
<p>修改服务端 、关闭防火墙、启动游戏、游戏上线赠送修改、修改充值金额和元宝等请查看资源内教程文档。<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202105/f9d3d39870.jpg" alt="手游H5名扬三界梦幻西游手工架设一键服务端完整版_附架设教程">
