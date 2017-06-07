# WeexTemplate
一款可以方便创建weex模版文件的SublimeText 插件

特性
------------
* 支持vue语法高亮
* 支持在菜单栏快捷创建weex文件
* 支持在侧边栏快捷创建weex文件
* 支持自定义快捷键
* 支持自定义weex模板


安装方式
------------
**Package Control(墙裂推荐)**

* 打开Sublime Package Controll(快捷键 shift+command+P)
* 输入Install Package加载插件库列表
* 搜索WeexTemplate回车 搞定！

**Github**

* 从下面的地址clone github仓库:

    $ git clone https://github.com/devilthrone/WeexTemplate.git
    
* 在Sublime菜单栏, 点击Sublime Text的 `Preferences` / `Browse Packages`, 打开"Packages" 目录.
 
* 把从github clone下载的项目拷贝到 Packages 目录下，并命名为 WeexTemplate

用法
-----

- 从菜单栏或者侧边栏创建weex文件
   `File - New File (Weex)-Weex(.we)` : 创建  .we 文件
   `File - New File (Weex)-Weex(.vue)` : 创建  .vue 文件
   
- 用快捷键创建weex文件

    --------------------
        MacOs 平台:
        command+ctrl+w   创建.we 文件
        command+ctrl+e   创建.vue 文件
        
        Window 平台:
        ctrl+alt+w   创建.we 文件
        ctrl+alt+e   创建.vue 文件
        
- 自定义快捷键       
你可以通过一下方式自定义快捷键：  
 打开 `Preferences - Package Settings - Weex - Key Bindings(User)  ` 
 
 下面是创建快捷键的示例配置:
        
         --------------------
               [
               	
                   {
                       "keys": ["shift+command+w"], "command": "weex_template",
                       "args": {"type": "weex"}, "context": [{"key": "weex_template.weex"}]
                   },
                    {
                       "keys": ["shift+command+e"], "command": "weex_template",
                       "args": {"type": "vue"}, "context": [{"key": "weex_template.vue"}]
                   }
                   
               ]

- 自定义weex模板

 默认的模板文件存放在: Packages/WeexTemplate/templates/vue.tmpl, 你可以参考默认模版例子来自定义weex模板， 
 
比如： 新建模板文件：`Packages/User/WeexTemplate/templates/vue.tmpl ` 

