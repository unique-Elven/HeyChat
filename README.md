# 简介
这是一个一可以调用OPENAI的API实现诸多有意思功能的小软件
可惜唯一的不足就是需要科学上网才能使用哟!而且需要干净没被OPENAI封的代理
# 注意
我先在软件内置了我自己的付费API供大家使用，请大家来尝试优化吧！
请慎用接口哟，如果有天失效那就是我的API失效啦！
不用灰心，在软件的最上方我提供了输入API的框口，大家也可以使用自己的API试试
# 使用
relase 版本的已经封装打包好了，应该只要网好就能使用
如果是下源码，解释运行那么请记得安装对应的库

大坑：由于国内用户使用需要挂代理，urlib3的库版本太高挂代理会报错的，所以请退回旧版本
```
pip install urllib3==1.25.11
#或者
pip install urllib3==1.25.11 -i http://pypi.douban.com/simple --trusted-host pypi.douban.com
```