# openresty-utils

自己写的一些用于openresty的小工具。

## list_lua_shared_dic

打印所有lua_shared_dic的当前内容。

### 配置方法

使用lua_shared_dic/nginx.conf作为openresty的nginx配置文件。

### 访问方式

http://hostip:12000/listdic

### 输出效果：

    dogs:
        name=Wangcai
        age=2
        color=yellow
