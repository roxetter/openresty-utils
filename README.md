# openresty-utils

自己写的一些用于openresty的小工具。

## lua_shared_dic_utils

操作lua_shared_dic的小工具，实现设置指定dic的键值对、打印所有dic内容等功能。

### 打印所有dic的内容

#### 调用方法

访问url：/listdics

#### 输出效果：

    dogs:
        name=Wangcai
        age=2
        color=yellow


### 设置某个键值对到指定dic

#### 调用方法

访问url：/setdic/{dic}/{key}={value}

如：/setdic/dogs/name=Biggy

#### 输出效果

    ok
