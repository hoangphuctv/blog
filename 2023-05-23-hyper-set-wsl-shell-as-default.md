Use Ubuntu bash shell in wsl as default shell for [Hyper Terminal](https://hyper.is/) (Windows)
Press `Ctrl + ,` for open `.hyper.js` file

set `shell` and `shellArgs` like this
```
        shell: 'C:\\Windows\\System32\\wsl.exe', 
        shellArgs: ['-d', 'Ubuntu', 'bash'],
```
Save reload.
