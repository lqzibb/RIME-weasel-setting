# 配置文件作用说明

## 输入方案


### 极光拼音

#### `aurora_pinyin.schema.yaml`

**极光拼音输入方案**

### 小鹤双拼

#### `double_pinyin_flypy.schema.yaml`
小鹤双拼输入方案，是从官方Github地址下的，我未作直接修改。


#### `double_pinyin_flypy.custom.yaml`


默认方案配置并不能满足我的需求，这是我自定义添加的`patch`，可以通过查看备注知晓。

## 词库

#### `aurora_pinyin.dict.yaml`
**极光拼音词库**
默认「朙月拼音」的词库是繁体，需要经过`opencc`进行转换，虽然没发现什么问题，但还是转为简体词库比较放心。

#### `luna_pinyin.cn_en.dict.yaml`

朙月拼音」融合词词库。

什么是融合词？例子：U盘，T恤

#### `luna_pinyin.english.dict.yaml`

英语词库，中英混输。

#### `luna_pinyin.website.dict.yaml`

网站名称。

## 安装配置

#### `installation.yaml`

配置备份路径与备份文件夹名称；

## 用户配置

#### `user.yaml`

未作修改；

## 全局输入配置

#### `default.custom.yaml`

做了大量修改，可以查看其中备注知晓；

## 全局外形配色配置

#### `weasel.custom.yaml`

做了大量修改，可以查看其中备注知晓；