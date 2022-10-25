# ObsidianScripts
Some scripts for Obsidian

## 使用说明
首先需要你的`Obsidian`安装`Dataview`插件，并且打开js功能。~~想必大家应该都有装这个插件~~

之后将本项目`clone`或者打包下载，解压到你的`Obsidian`仓库目录。

最后将`Template`目录中的模板文件复制到你的模板目录。

### 纪念日 anniversary

#### 页面内输出代码

```javascript
    ```dataviewjs
    dv.view("anniversary")
    ```
```

#### 使用`anniversary`模板

```yaml
---
type: anniversary
date: {{date}} # 填入纪念日的初次发生日期
isLunar: false # 是否按农历计算，适用于农历生日、新年等
---
```

#### 实现效果

![](https://cdn.jsdelivr.net/gh/mouyase/ObsidianScripts@master/preview/anniversary.png)

### 域名续费计划 domain-renew-project

#### 页面内输出代码

```javascript
    ```dataviewjs
    dv.view("domain-renew-project")
    ```
```

#### 使用`domain-renew-project`模板

```yaml
---
type: domain
renew: {{date}} # 域名下次续费日期
provider: # 域名的提供商
provider_url: # 域名提供商的网址
---
```

#### 实现效果

![](https://cdn.jsdelivr.net/gh/mouyase/ObsidianScripts@master/preview/domain-renew-project.png)