# AutoScript
## 动态抽奖  
通过Github Actions挂载Nodejs脚本  
> [Actions官方文档](https://docs.github.com/en/free-pro-team@latest/actions/reference/workflow-syntax-for-github-actions)

默认整点运行,只转发非官方抽奖
## 操作步骤22
1. fork本仓库  

2. 填入COOKIE  
    >具体获取Cookie的方法参考[BILIBILI-HELPER](https://github.com/JunzhouLiu/BILIBILI-HELPER)
    
    COOKIE格式如下:  
    `DedeUserID=填入此处;·SESSDATA=填入此处;·bili_jct=填入此处;·`  
    (**点号**表示一个**空格**实际填写时**须去掉** 注意**顺序与空格**要求)  
    ![步骤1](https://ftp.bmp.ovh/imgs/2020/11/c4e7ac036199551c.png)
    ![步骤2](https://ftp.bmp.ovh/imgs/2020/11/dcc3f30e22f6b12a.png)

3. 如果想使用**微信推送**服务请用同样的方法填入`SCKEY`  
    [Server酱](http://sc.ftqq.com/3.version)  123
    具体方法可以参考同样参考[BILIBILI-HELPER](https://github.com/JunzhouLiu/BILIBILI-HELPER)

4. 随便改一下此文件再作一次提交便自动运行  
## 效果
![效果](https://ftp.bmp.ovh/imgs/2020/11/87d483cea98563fa.png)

