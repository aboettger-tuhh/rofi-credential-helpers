# rofi-credential-helper

## rofi-keepassxc

### What this script is

This is a **rofi-based GUI wrapper around `keepassxc-cli`**. It lets you:

- Open a KeePassXC database (optionally using a **YubiKey challenge-response slot**),
- Pick an entry from a searchable list,
- Then **clip** username/password (or other fields) to the clipboard, **show/edit info**, **delete**, or **add** a new entry.

It relies on these external tools:

- `rofi` (in `-dmenu` mode for prompts/menus, and `-e` for error popups)
- `keepassxc-cli` (to list/show/edit/add/remove entries)
- `xclip` (to put text into the X11 clipboard)
- Standard Unix tools: `grep`, `cut`, `sort`, `wc`, etc.

### Small behaviors are worth noting

- Das Passwort


