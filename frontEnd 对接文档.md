#frontend 对接文档

##工作环境
- 前端代码由两部分组成，主控程序由思远完成，样式展示经伟完成。

- 采用webpack对于代码进行打包编辑，使用时首先安装对应的依赖库即可 例如npm install express等，详细参见package.json的配置部分。

- 代码采用github进行同步，版本管理。（权限由思远赋予）

##调试环境

###本地调试环境

- 开启服务器方式。github代码中的mock_server.js的模拟服务器的部分，window7中在cmd页面中找到对应的文件夹，输入start npm进行开启服务。配置端口为4999。其中可以看到前后端api的配置。
- 本地输入js代码，在浏览器的console中
```
(function(){var s=document.createElement("script");s.src="http://127.0.0.1:4999/adkalava-bundle.js";document.head.appendChild(s);})()
```

###线上demo展示环境
- 在有图片的页面浏览器中找到console页面输入代码，根据代码的提示即可。
```
(function(){
        var s=document.createElement("script");
        s.src="http://www.adkalava.cn/adkalava/adkalavaJs/adkalava-bundle.js";
        document.head.appendChild(s);
    })();
```
##配置
具体程序逻辑请参看程序代码

###打包js代码放置位置
- 在公司90服务器上位置为 "/data/www/yof/public/adkalava/adkalavaJs"
- 每次更新代码之后，就放在这这里，方便访问。如需更改位置则要群发邮件告知。

###前端设置的icon放置位置
- 位置"/data/www/yof/public/adkalava/class"
- 在程序的对应中为adsUtils里面的内容，这里因后端程序更改，现在需要重新映射，详情跟小林协调

##前端经伟联系方式
- 邮件 wujingwei@yunshitu.cn
- 号码 15155129701
- 如有不明可以直接约时间联系