# Helix Plugins(unofficial)

How it works:

*   This repo's purpose is to have a list of the most desired helix plugins.
*   You could suggest preexisting plugins from editors such as vscode, emacs,
    vim, etc. or you could describe your new plugin idea & give it a name.
*   In case you do not understand a specific plugin's purpose from just it's
    name then please refer to the "plugin description" right below or just
    click on the plugin name.

## Plugins and Plugin Ideas

1.  [ colorizer ](#colorizer)
2.  [ easymotion ](#easymotion)
3.  [ ghosttext ](#GhostText)
4.  [ helix-remote-development ](#helix-remote-development)
5.  [ magit ](#magit)
6.  [ org-mode ](#org-mode)
7.  [ shade ](#shade)
8.  [ table-mode ](#table-mode)
9.  [ tabout ](#tabout)
10. [ vim-move ](#vim-move)
11. [ wakatime ](#wakatime)

## Plugin/Idea Description

### Colorizer:

*   Description: Color previewer in files
*   Issues/Discussions: None
*   References: <https://github.com/norcalli/nvim-colorizer.lua>
*   Implementation: Builtin

### Easy Motion:

*   Description: Simpler way to use motions by highlighting choices
*   Issues/Discussions: zim0369/helix\_plugins/issues/7
*   References: <https://github.com/easymotion/vim-easymotion>
*   Implementation: Plugin

### Ghost Text:

*   Description: Use your text editor in the browser
*   Issues/Discussions: helix-editor/helix/issues/3339
*   References: <https://ghosttext.fregante.com/>
*   Implementation: Plugin

### Helix Remote Development

*   Description: Seamlessly edit code from ssh host machine
*   Issues/Discussions: helix-editor/helix/issues/3721, zim0369/helix\_plugins/issues/2
*   References: <https://code.visualstudio.com/docs/remote/remote-overview>
*   Implementation: Plugin

### Magit:

*   Description: Magit is an interface to the version control system Git,
    implemented as an Emacs package.
*   Issues/Discussions: helix-editor/helix/issues/227
*   References: <https://github.com/magit/magit>
*   Implementation: Plugin

### Org Mode:

*   Description: A GNU Emacs major mode for keeping notes.
*   Issues/Discussions: helix-editor/helix/issues/2825
*   References: <https://orgmode.org/>
*   Implementation: Plugin

### Shade:

*   Description: Dim your inactive windows, making it easier to see the active
    window at a glance.
*   Issues/Discussions: None
*   References: <https://github.com/sunjon/Shade.nvim>
*   Implementation: Builtin

### Table Mode:

*   Description: Automatic table creator & formatter allowing one to create neat tables as you type.
*   Issues/Discussions: helix-editor/helix/issues/2819
*   References: <https://github.com/dhruvasagar/vim-table-mode>
*   Implementation: Plugin

### Tabout:

*   Description: [Tabbing out from parentheses, quotes, and similar contexts.](https://github.com/helix-editor/helix/issues/1587#issue-1115976332)
*   Issues/Discussions: <https://github.com/helix-editor/helix/issues/1587>
*   References: <https://github.com/abecodes/tabout.nvim>
*   Implementation: Builtin

### Vim Move:

*   Description: This is a plugin for vim to move lines.
*   Issues/Discussions: helix-editor/helix/issues/2245
*   References: <https://github.com/matze/vim-move>
*   Implementation: Plugin

### Wakatime:

*   Description: Code stats right from your editor
*   Issues/Discussions: helix-editor/helix/discussions/3477, zim0369/helix\_plugins/issues/6
*   References: <https://wakatime.com/help/creating-plugin>
*   Implementation: Plugin

## Contributing

Users can contribute by either opening an issue or making a PR. Just make sure
to follow the below format for issues and pull requests:

### Format:

```markdown
### Plugin Name
  * Description: Description of the plugin.
  * Issues/Discussions: Links to any issues/discussions about this in the helix repo or this repo(comma
    separated). Leave empty if it's a new idea.
  * References: Links to any references like preexisting plugins, etc. Leave
    empty if it's a new idea.
  * Implementation: Plugin/Builtin
```

### Issues:

*   Check the list to prevent duplicates.
*   If it's a new idea then give it a short descriptive name.
*   Add the information according to the format.

### Pull Requests:

*   Rules similar to rules for issues follow here.
*   Follow alphabetical order while changing the list.
*   Names should be lowercase.
