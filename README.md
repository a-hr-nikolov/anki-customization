## Install addons
Addons are installed by going to `Tools > Addons > Get Addons..` and pasting the ID of the addon.

1. Install https://ankiweb.net/shared/info/295889520 by pasting `295889520`
When installed, press Config on the addon page (with the addon selected), and paste this in:
```json
{
    "actions": [
        {
            "hotkey": "alt+shift+5",
            "name": "strikeThrough",
            "tooltip": "Apply strikethrough"
        },
        {
            "hotkey": "ctrl+shift+alt+a",
            "label": "&lt;abbr&gt;",
            "name": "abbr",
            "tooltip": "Apply &lt;abbr&gt; tag"
        },
        {
            "hotkey": "ctrl+.",
            "name": "formatBlockPre",
            "tooltip": "Insert code block"
        },
        {
            "hotkey": "ctrl+alt+s",
            "name": "formatInlineCode",
            "tooltip": "Insert inline code"
        },
        {
            "hotkey": "ctrl+shift+alt+_",
            "name": "insertHorizontalRule",
            "tooltip": "Insert horizontal line"
        },
        {
            "hotkey": "ctrl+[",
            "name": "insertUnorderedList",
            "tooltip": "Toggle unordered list"
        },
        {
            "hotkey": "ctrl+]",
            "name": "insertOrderedList",
            "tooltip": "Toggle ordered list"
        },
        {
            "hotkey": "ctrl+shift+]",
            "name": "indent",
            "tooltip": "Indent"
        },
        {
            "hotkey": "ctrl+shift+[",
            "name": "outdent",
            "tooltip": "Outdent"
        },
        {
            "hotkey": "ctrl+shift+alt+s",
            "name": "justifyCenter",
            "tooltip": "Center text"
        },
        {
            "hotkey": "ctrl+shift+alt+l",
            "name": "justifyLeft",
            "tooltip": "Align text to the left"
        },
        {
            "hotkey": "ctrl+shift+alt+r",
            "name": "justifyRight",
            "tooltip": "Align text to the right"
        },
        {
            "hotkey": "ctrl+shift+alt+b",
            "name": "justifyFull",
            "tooltip": "Justify text"
        }
    ]
}

```

2. Install https://ankiweb.net/shared/info/566351439 by pasting `566351439`
Paste this in its config:
```json
{
    "hotkey": "Alt+s",
    "limitToLangs": [
        "Python",
        "JavaScript",
        "TypeScript",
        "Go",
        "HTML",
        "CSS",
        "SQL",
        "Bash",
        "JSX",
        "TSX",
        "C",
        "Docker",
        "JSON",
        "YAML",
        "Protocol Buffer"
    ],
    "style": "github-dark"
}
```

Also make sure to go to `Tools > Syntax Highlighting Options > Uncheck the Line Numbers`, they add clutter

3. Go to `Tools > Manage Note Types > Select Basic type > Cards on the sidebar`
4. Paste the contents of `basic-front.html` in the Front Template window, `basic-back.html` in the Back Template window, and `basic-reduced.css` in the Style window. Then `Save`.
5. When in the editor, choose a language from the dropdown menu (in the formatting options of the editor), highlight your pasted code, and press `Alt + S` for a code block.
6. If you only want inline code without syntax highlighting (e.g. something `like this`), highlight the text and press `Ctrl + Alt + S`