# sublime-redux

Simple sublime-text boiler-plate for quick config after a fresh install. 

The purpose of this: quick and easy way to customize sublime-text to get it ready for some sweet coding.

Current version: for windows.

#### steps

1. [Install Package Control](http://wbond.net/sublime_packages/package_control/installation)

2. Install Soda UI theme

    copy `Made of Code.tmTheme` to `C:\Users\[user]\AppData\Roaming\Sublime Text 2\Packages`

3. Change icon

    get icon from: [icon_link](https://github.com/dmatarazzo/Sublime-Text-2-Icon/raw/master/sublime_text.ico) (see changing the icon below)
    
4. Reset windows icon cache by running included .bat file


#### changing the icon

* download [ResEdit](http://www.resedit.net/)
* navigate to the installation folder for Sublime Text 2 (this should be in C:\Program Files\Sublime Text2). Copy `sublime_text.exe` to your desktop.*
* run ResEdit, choose `File > Open Project ...`. Select the `sublime_text.exe` you copied to your desktop.
* in the Resources pane of ResEdit, right-click the Icon folder and choose `Add Resource > Icon...`.
* navigate to the folder containing the `sublime_text.ico` file. Add it.
* right-click the icon named `103 [English (Australia)]`, select `Remove from Project`.
* save.
* copy the `sublime_text.exe` on your desktop back to the Program Files folder from step 1.  
 
 
#### nice packages

* [helps with encodin strings](https://github.com/colinta/SublimeStringEncode)


#### credits

* [Sublime Text](http://www.sublimetext.com)
* [The article that started all this](http://opensoul.org/blog/archives/2012/01/12/getting-started-with-sublime-text-2)
* [Resource Editor](http://www.resedit.net)
* [Awesome icon by dmatarazzo](https://github.com/dmatarazzo/Sublime-Text-2-Icon)
* [Rebuild cache by Shawn Brink](http://www.sevenforums.com/tutorials/49819-icon-cache-rebuild.html)