hubot-qq
------

[原项目](https://github.com/xhan/qqbot)对新协议二维码登录的支持不太好,  
其中一个 [fork](https://github.com/floatinghotpot) 支持的很不错, 但是却不直接支持 hubot,  
于是我简单 merge 了两者形成该 repo.  

Install
-------

因为新增了canvas库，所以在Ubuntu下需要安装相关包

    sudo apt-get install pkg-config libcairo2-dev libjpeg-dev libgif-dev


TODO
---
* 自动收集链接, 图片
* 图片发送支持
* 集成 tuling123 api
