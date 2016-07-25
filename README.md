# Packages and settings

This repository contains the packages and settings that I use for [Sublime Text 3](https://www.sublimetext.com/3).

### Packages

  - [AdvancedNewFile]()
  - [AlignTab]()
  - [All Autocomplete]()
  - [AutoFileName]()
  - [Blade Spacer]()
  - [BracketHighlighter]()
  - [Case Conversion]()
  - [Color Highlighter]()
  - [DocBlockr]()
  - [Dotfiles Syntax Highlighting]()
  - [EditorConfig]()
  - [Emmet]()
  - [FuzzyFilePath]()
  - [Git]()
  - [GitGutter]()
  - [Gulp]()
  - [Hasher]()
  - [HTML Boilerplate]()
  - [HTML-CSS-JS Prettify]()
  - [Inc-Dec-Value]()
  - [INI]()
  - [jQuery]()
  - [Laravel Blade Highlighter]()
  - [Markdown Extended]()
  - [Material Theme]()
  - [Origami]()
  - [Package Control]()
  - [Sass]()
  - [SideBarEnhancements]()
  - [SideBarFolders]()
  - [Stylus]()
  - [SublimeCodeIntel]()
  - [SublimeLinter]()
  - [SublimeLinter-contrib-htmllint]()
  - [SublimeLinter-contrib-sass-lint]()
  - [SublimeLinter-contrib-stylint]()
  - [SublimeLinter-csslint]()
  - [SublimeLinter-jshint]()
  - [SublimeLinter-json]()
  - [SublimeLinter-phplint]()
  - [Syntax Highlighting for Sass]()
  - [Terminal]()
  - [Text Pastr]()

## Preferences

```
{
  "always_show_minimap_viewport": true,
  "auto_complete_cycle": true,
  "auto_complete_with_fields": true,
  "auto_indent": true,
  "bold_folder_labels": true,
  "caret_style": "phase",
  "close_windows_when_empty": false,
  "color_scheme": "Packages/User/Color Highlighter/themes/Material-Theme-OceanicNext (SL).tmTheme",
  "ensure_newline_at_eof_on_save": true,
  "font_face": "Fira Code",
  "font_options":
  [
    "subpixel_antialias"
  ],
  "font_size": 14,
  "highlight_line": true,
  "highlight_modified_tabs": true,
  "ignored_packages":
  [
    "Vintage"
  ],
  "indent_guide_options":
  [
    "draw_normal",
    "draw_active"
  ],
  "line_padding_bottom": 3,
  "line_padding_top": 3,
  "material_theme_bold_tab": true,
  "overlay_scroll_bars": "enabled",
  "show_encoding": true,
  "spacegray_tabs_xlarge": true,
  "tab_size": 2,
  "theme": "Material-Theme.sublime-theme",
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "update_check": false,
  "word_wrap": false,
  "wrap_width": 120
}
```

### Key Bindings

```
[
    { "keys": ["home"], "command": "move_to", "args": {"to": "bol"} },
    { "keys": ["end"], "command": "move_to", "args": {"to": "eol"} },
    { "keys": ["shift+end"], "command": "move_to", "args": {"to": "eol", "extend": true} },
    { "keys": ["shift+home"], "command": "move_to", "args": {"to": "bol", "extend": true } },
    { "keys": ["super+shift+t"], "command": "open_mac_terminal" },
    { "keys": ["super+v"], "command": "paste_and_indent" },
    { "keys": ["super+shift+v"], "command": "paste" },
    { "keys": ["super+shift+r"],  "command": "reindent" },
    { "keys": ["super+\\"], "command": "toggle_side_bar" },
    { "keys": ["super+shift+s"], "command": "save_all" },
    { "super_awesome_paste.format_hex_colors": "lowercase" },

    // Laravel Blade
    {
        "keys": [
            "tab"
        ],
        "command": "expand_abbreviation_by_tab",
        "context": [
            {
                "operand": "source.blade.php, source",
                "operator": "equal",
                "match_all": true,
                "key": "selector"
            },
            {
                "match_all": true,
                "key": "selection_empty"
            },
            {
                "operator": "equal",
                "operand": false,
                "match_all": true,
                "key": "has_next_field"
            },
            {
                "operator": "equal",
                "operand": false,
                "match_all": true,
                "key": "setting.disable_tab_abbreviations"
            },
            {
                "operand": false,
                "operator": "equal",
                "match_all": true,
                "key": "auto_complete_visible"
            },
            {
                "match_all": true,
                "key": "is_abbreviation"
            }
        ]
    }
]
```

