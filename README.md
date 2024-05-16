# Serv00 - 控制面板自动登录脚本
## 使用方法

1、创建复刻

![image](https://github.com/xiaofeivip/Serv00_Auto_Login/assets/37949125/9f05437f-2d71-48e1-b26b-cad29b293c00)


![1](https://github.com/xiaofeivip/Serv00_Auto_Login/assets/37949125/8411f772-16fa-4f93-94b1-9659be45d4b8)

2、设置变量

![image](https://github.com/xiaofeivip/Serv00_Auto_Login/assets/37949125/79e8d81c-edee-4bb3-89c2-bbdb17a3dc6b)


然后创建一个名为`ACCOUNTS_JSON`的`Secret`，将 JSON 格式的账号密码字符串作为它的值，如下格式：

username: 用户名
password：密码
panelnum：其中`panelnum`参数为面板编号，即为你所收到注册邮件的`panel*.serv00.com`中的`*`数值
```
[  
  { "username": "qinshihuang", "password": "linux.do", "panelnum": "0" }
]
```

3、设置定时运行

![image](https://github.com/xiaofeivip/Serv00_Auto_Login/assets/37949125/659656ea-be45-4494-8046-95ce06c5acb7)

5、登录Serv00后台，就可以查看登录纪录了

![image](https://github.com/xiaofeivip/Serv00_Auto_Login/assets/37949125/8bb6d5f2-0531-4a87-a480-b8a6e3baec52)
