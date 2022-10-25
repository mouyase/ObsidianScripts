# ObsidianScripts
Some scripts for Obsidian

## 使用说明
首先需要你的`Obsidian`安装`Dataview`插件，并且打开js功能。~~想必大家应该都有装这个插件~~

之后将本项目`clone`或者打包下载，解压到你的`Obsidian`数据库目录。

最后将`Template`目录中的模板文件复制到你的模板目录。

### 纪念日anniversary

输出代码

    ```javascript
        ```dataviewjs
        dv.view("anniversary")
        ```
    ```

使用`anniversary`模板
```
---
type: anniversary
date: {{date}} #填入纪念日的初次发生时间
isLunar: false #是否按农历计算，适用于农历生日，新年等
---
```
