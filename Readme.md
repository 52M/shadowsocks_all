# 所有shadowsocks分支一键安装脚本 

感谢teddysun大神的一键脚本，感谢B大开发对shadowsocks-R项目的开发，感谢shadowsocks原作者对互联网的贡献，本项目只作为个人自用项目，对部分内容作出下列修改：
*默认加密为：rc4-md5
*默认协议为：auth_sha1_compatible
*默认混淆为：http_post_compatible（兼容http_simple,客户端可以直接用http_simple）
*使用git的方式安装，以方便以后使用git来升级
*增加了修改时区的操作。把时区设置成了北京-上海时间。

shadowsocks.sh
===============
* Description: Auto Install Shadowsocks(Python) Server for CentOS/Redhat/Debian/Ubuntu
* Intro: https://teddysun.com/342.html

shadowsocks-libev.sh
===============
* Description: Auto Install Shadowsocks(libev) Server for CentOS/Redhat
* Intro: https://teddysun.com/357.html

shadowsocks-libev-debian.sh
===============
* Description: Auto Install Shadowsocks(libev) Server for Debian/Ubuntu
* Intro: https://teddysun.com/358.html

shadowsocks-go.sh
===============
* Description: Auto Install Shadowsocks(Go) Server for CentOS/Redhat/Debian/Ubuntu
* Intro: https://teddysun.com/392.html

shadowsocks-crond.sh
===============
* Description: Check Shadowsocks(All version) Server is running or not, and start it if not running
* Intro: https://shadowsocks.be/6.html

shadowsocksR.sh
===============
* Description: Auto Install ShadowsocksR Server for CentOS/Redhat/Debian/Ubuntu
* Intro: https://shadowsocks.be/9.html

haproxy.sh
===============
* Description: Auto Install haproxy for Shadowsocks Server
* Intro: https://shadowsocks.be/10.html

shadowsocks-nodejs.sh (Deprecated)
===============
* Description: Auto Install Shadowsocks(NodeJS) Server for CentOS/Redhat
* Intro: https://teddysun.com/355.html

Copyright (C) 2014-2016 Teddysun <i@teddysun.com>