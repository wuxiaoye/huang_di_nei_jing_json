# 黄帝内经-书籍-json文件

#### 介绍
黄帝内经-书籍-json文件


#### 使用说明
用户打开APP, 
1, 首先会读取本地数据, 然后检测对比 update_version.json 中的版本号(目录版本号, 书籍内容版本号); 
如果有更新版本, 则重新加载 huang_di_nei_jing_mu_lu.json / huang_di_nei_jing_content.json 文件; 
如果没有更新, 直接使用本地数据.

2, 维护者如果有更新书籍内容, 在本地电脑修改内容, 打包好 json 文件, 再替换上来.

### CDN加速

如果是github 仓库, 可以使用 jsdelivr CDN 加速, 
格式 : https://cdn.jsdelivr.net/gh/用户名/仓库名/文件路径

示例:

https://cdn.jsdelivr.net/gh/wuxiaoye/huang_di_nei_jing_json/update_version.json

https://cdn.jsdelivr.net/gh/wuxiaoye/huang_di_nei_jing_json/huang_di_nei_jing_mu_lu.json

https://cdn.jsdelivr.net/gh/wuxiaoye/huang_di_nei_jing_json/huang_di_nei_jing_content.json


