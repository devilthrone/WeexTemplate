# WeexTemplate
[中文文档点我](https://github.com/devilthrone/WeexTemplate/README-cn.md)

Create Weex(.we or .vue) File  Conveniently Form Weex Template for SublimeText 

Feature
------------
* Support Vue Syntax Highlight
* Support Create File form Menu
* Support Create File form SideMenu
* Support Customize shortcut key
* Support Customize weex templte


Installation
------------
**Github**

* clone this repository:

    $ git clone https://github.com/devilthrone/WeexTemplate.git
    
* On the Sublime Text Menu, Go to `Preferences` / `Browse Packages`, open the "Packages" directory.
 
* Copy the project cloned form github onto "Packages" directory, and rename to "WeexTemplate"

Usage
-----

- Create a weex file with Menu or SideMenu
   `File - New File (Weex)-Weex(.we)` : create a .we file
   `File - New File (Weex)-Weex(.vue)` : create a .vue file
   
- Create a weex file with shortcut key

    --------------------
        MacOs platform:
        command+ctrl+w   create .we file
        command+ctrl+e   create .vue file
        
        Window platform:
        ctrl+alt+w       create .we file
        ctrl+alt+e       create .vue file
        
- Customize shortcut key        
you can modify the shortcut key by  
 `Preferences - Package Settings - Weex - Key Bindings(User)  ` 
 
 for example:
        
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

- Customize weex template

 Default template files in : Packages/WeexTemplate/templates/vue.tmpl, you can customize the weex template file: 
 
`Packages/User/WeexTemplate/templates/vue.tmpl ` (create directory if not exist )

