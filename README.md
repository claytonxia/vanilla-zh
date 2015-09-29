#Vanilla
*Vanilla是一个基于Openresty开发的Web应用开发框架.*
<p><a href="http://idevz.github.io/vanilla/"><img border="0" src="http://m1.sinaimg.cn/maxwidth.300/m1.sinaimg.cn/120d7329960e19cf073f264751e8d959_2043_2241.png" alt="LuaRocks" width="150px"></a></p>

##install
```
yum install lua-devel luarocks
luarocks install https://raw.githubusercontent.com/idevz/vanilla/master/vanilla-0.0.1-1.rockspec
```

##set
```
content_by_lua_file ./pub/index.lua;
```

##useage
```
vanilla new app
cd app
vanilla start
```