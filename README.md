
# Toggle Settings In Batch

Allow you to create your own keybindings which change view, window or global settings:
```js
// @param same_value, if True, will set either all settings to True or False,
// depending on the first setting value.
{ "keys": ["ctrl+k", "ctrl+n"], "command": "toggle_settings", "args":
        {"settings": ["line_numbers", "fold_buttons", "mini_diff"],
            "same_value": true, "scope": "view"} },

{ "keys": ["ctrl++"], "command": "increment_setting", "args":
        {"setting": "font_size", "increment": 1, "scope": "window"} },

{ "keys": ["ctrl+-"], "command": "increment_setting", "args":
        {"setting": "font_size", "increment": -1, "scope": "global"} },
```


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `ToggleSettingsInBatch` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


___
## License

All files in this repository are released under GNU General Public License v3.0
or the latest version available on http://www.gnu.org/licenses/gpl.html

1. The [LICENSE](LICENSE) file for the GPL v3.0 license
1. The website https://www.gnu.org/licenses/gpl-3.0.en.html

For more information.

