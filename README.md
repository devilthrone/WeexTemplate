# WeexTemplate
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

    $ git clone https://github.com/kairyou/SublimeTmpl.git
    
* On the Sublime Text Menu, Go to `Preferences` / `Browse Packages`, open the "Packages" directory.
 
* Copy the project cloned form github onto "Packages" directory, and rename to "Weex"

Usage
-----

- Create a weex file with Menu or SideMenu
   `File - New File (Weex)-Weex(.we)` : create a .we file
   `File - New File (Weex)-Weex(.vue)` : create a .vue file
   
- Create a weex file with shortcut key

    --------------------
        MacOs platform:
        command+ctrl+w   .we file
        command+ctrl+e   .vue file
        
        Window platform:
        ctrl+alt+w   .we file
        ctrl+alt+e   .vue file
        
- Customize shortcut key        
you can modify the shortcut key by  
 `Preferences - Package Settings - Weex - Key Bindings(User)  ` 
 
 for example:
        
         --------------------
               [
               	
                   {
                       "keys": ["shift+command+w"], "command": "weex",
                       "args": {"type": "weex"}, "context": [{"key": "weex.weex"}]
                   },
                    {
                       "keys": ["shift+command+e"], "command": "weex",
                       "args": {"type": "vue"}, "context": [{"key": "weex.vue"}]
                   }
                   
               ]

- Customize weex templte

 Default template files in : Packages/Weex/templates/vue.tmpl, you can customize the weex template file: 
 
`Packages/User/Weex/templates/vue.tmpl ` (create directory if not exist )

