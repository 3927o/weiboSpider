# 如何获取cookie

1. 用Chrome打开微博并登陆；
2. 登录成功后访问<https://weibo.com>;
3. 按F12键打开Chrome开发者工具，在地址栏输入并跳转到<https://weibo.com>，跳转后会显示如下类似界面:
![chrome debugger network tab](https://picture.cognize.me/cognize/github/weibospider/cookie2.png)
4. 依此点击Chrome开发者工具中的Network->Name中的weibo.com->Headers->Request Headers，"Cookie:"后的值即为我们要找的cookie值，复制即可，如图所示：
![cookie in request headers section](https://picture.cognize.me/cognize/github/weibospider/cookie3.png)
