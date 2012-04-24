# sublime-redux

Simple sublime-text boiler-plate for quick config after a fresh install. 

The purpose of this: quick and easy way to customize sublime-text to get it ready for some sweet coding.

Current version: for windows.

#### steps

1. Install Package Control
   
    [command_to_install_pc](http://wbond.net/sublime_packages/package_control/installation)

2. Install Soda UI theme

        copy it to C:\Users\[user]\AppData\Roaming\Sublime Text 2\Packages

3. Change icon

    get icon from: [icon_link](https://github.com/dmatarazzo/Sublime-Text-2-Icon/raw/master/sublime_text.ico)
    
	Download [ResEdit](http://www.resedit.net/)

	* Navigate to the installation folder for Sublime Text 2 (this should be in C:\Program Files\Sublime Text2). Copy `sublime_text.exe` to your desktop.*
	* Run ResEdit, choose `File > Open Project ...`. Select the `sublime_text.exe` you copied to your desktop.
	* In the Resources pane of ResEdit, right-click the Icon folder and choose `Add Resource > Icon...`.
	* Navigate to the folder containing the `sublime_text.ico` file. Add it.
	* Right-click the icon named `103 [English (Australia)]`, select `Remove from Project`.
	* Save.
	* Copy the `sublime_text.exe` on your desktop back to the Program Files folder from step 1.  

4. Reset windows icon cache by running included .bat file


#### credits

* [Sublime Text](http://www.sublimetext.com)
* [The article that started all this](http://opensoul.org/blog/archives/2012/01/12/getting-started-with-sublime-text-2)
* [Resource Editor](http://www.resedit.net)
* [Awesome icon by dmatarazzo](https://github.com/dmatarazzo/Sublime-Text-2-Icon)
* [Rebuild cache by Shawn Brink](http://www.sevenforums.com/tutorials/49819-icon-cache-rebuild.html)