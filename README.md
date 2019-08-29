
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


___
## License

All files in this repository are released under GNU General Public License v3.0
or the latest version available on http://www.gnu.org/licenses/gpl.html

1. The [LICENSE](LICENSE) file for the GPL v3.0 license
1. The website https://www.gnu.org/licenses/gpl-3.0.en.html

For more information.

