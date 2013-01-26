# sublime-redux

Simple sublime-text boiler-plate for quick config after a fresh install.

The purpose of this: quick and easy way to customize sublime-text to get it ready for some sweet coding.

#### steps

1. [Install Package Control](http://wbond.net/sublime_packages/package_control/installation)

2. Install Soda UI theme and [Tomorrow Theme color scheme](https://github.com/chriskempson/tomorrow-theme)

    ```
    Package Control Install Package : Tomorrow Theme color scheme
    Package Control Install Package : Soda UI theme
    ```

3. Install [Phoenix theme](https://github.com/netatoo/phoenix-theme) : `Package Control Install Package Phoenix theme`

    ```JS
    {
      "theme": "Phoenix Dark.sublime-theme",
      "phoenix_color_red": true,
	    "phoenix_highlight_current_tab": true,
	    "phoenix_eighties": true,
	    "phoenix_solid_current_tab": true,
	    "phoenix_dirty_bottom_bar": true,
	    "phoenix_tabs_auto_width": true
    }
    ```

4. Change icon

    get icon from: [icon_link](https://github.com/dmatarazzo/Sublime-Text-2-Icon/raw/master/sublime_text.ico) (see changing the icon below) or from the icons folder

5. Reset windows icon cache by running included .bat file

7. You can also try the awesome [Boron](https://github.com/mjio/boron.tmtheme) Color scheme : `Package Control Install Boron theme`

8. Also added Faenza Icon (in icon folder) via [stsmuniz](http://gnome-look.org/content/show.php/?content=147424)


#### changing the icon

* download [ResEdit](http://www.resedit.net/)
* navigate to the installation folder for Sublime Text 2 (this should be in C:\Program Files\Sublime Text2)
* Copy `sublime_text.exe` to your desktop
* run ResEdit (as Admin), choose `File > Open Project ...`. Select the `sublime_text.exe` you copied to your desktop.
* in the Resources pane of ResEdit, right-click the Icon folder and choose `Add Resource > Icon...`.
* navigate to the folder containing the `sublime_text.ico` file. Add it.
* right-click the icon named `103 [English (Australia)]`, select `Remove from Project`.
* save.
* copy the `sublime_text.exe` on your desktop back to the Program Files folder from step 1.


#### nice packages

* [helps with encodin strings](https://github.com/colinta/SublimeStringEncode)


#### soft tabs with two spaces (Preferences->Settings->User)

```JS
{
  "tab_size": 2,
  "translate_tabs_to_spaces": true
}
```


#### my current config file:

```JS
{
  "color_scheme": "Packages/Tomorrow Color Schemes/Tomorrow-Night-Eighties.tmTheme",
  "font_size": 14,
  "font_face": "Consolas",
  "font_options":
  [
    // "standardantialias" or "noantialias" or "cleartypeantialias"
    "subpixel_antialias"
  ],
  "ignored_packages": [ "Vintage" ],
  "tab_size": 2,
  "theme": "Soda Dark.sublime-theme",
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "draw_white_space": "all",
  "rulers":
  [
      70, 80
  ],
  "sublimelinter_popup_errors_on_save": true
}
```

#### useful key bindings for hiding project pane and minimap

`go to Preferences > Key Bindings — User and add`

```JS
[
  { "keys": ["super+ctrl+h"], "command": "toggle_minimap" },
  { "keys": ["super+ctrl+b"], "command": "toggle_side_bar" }
]

```

#### SublimeText with Rails

* [Tips for Rails](https://github.com/mhartl/rails_tutorial_sublime_text)

#### credits

* [Sublime Text](http://www.sublimetext.com)
* [The article that started all this](http://opensoul.org/blog/archives/2012/01/12/getting-started-with-sublime-text-2)
* [Resource Editor](http://www.resedit.net)
* [Awesome icon by dmatarazzo](https://github.com/dmatarazzo/Sublime-Text-2-Icon)
* [Rebuild cache by Shawn Brink](http://www.sevenforums.com/tutorials/49819-icon-cache-rebuild.html)
