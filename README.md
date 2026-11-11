# rCommander for Scoop

The Scoop bucket of [rCommander](https://rcommander.net), a two-panel file manager with
terminals, SSH and SFTP, for Windows x86-64.

```powershell
scoop bucket add rcommander https://github.com/degoya/scoop-rcommander
scoop install rcommander
```

rCommander is in the Start menu and on the `PATH` as `rcommander`. `scoop update rcommander`
brings the next release; rCommander installed through Scoop does not replace itself, and its
update window shows that command. Its settings and connections live in the user's data folder
(`%APPDATA%\degoya\rCommander`), not in Scoop's app folder, so an update or reinstall keeps them.

Current version: 0.22.0. The manifest is written by the release workflow of
[degoya/rCommander](https://github.com/degoya/rCommander) with every release - issues and changes go there,
not here. The handbook's installation page:
<https://github.com/degoya/rCommander/wiki/installation>.
