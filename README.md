# openresty-utils

自己写的一些用于openresty的小工具。

## list_lua_shared_dic

打印所有lua_shared_dic的当前内容。

请参考list_lua_shared_dic/nginx.conf中"location = /listdic"区块的内容。

访问方式：http://host:port/listdic

输出效果：

    dogs:
        name=Wangcai
        age=2
        color=yellow
