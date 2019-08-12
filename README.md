# go-desktop-app
Desktop App with Go and Vue.js using Wails framework

## Build app in debug mode

```
$ cd cpustats/
$ sudo wails build -d
Wails v0.17.0 - Building Application

✓ Skipped frontend dependencies (-f to force rebuild)
✓ Building frontend...
✓ Ensuring Dependencies are up to date...
✓ Installing Mewn asset packer...
✓ Packing + Compiling project (Debug Mode)...
Awesome! Project 'cpustats' built!
```

## Run app

```
$ cd cpustats/
$ ./cpustats
cpustats - Debug Build
----------------------
INFO[0000] [App] Starting
INFO[0000] [WebView] Initialised
INFO[0000] [Events] Starting
INFO[0000] [IPC] Starting
INFO[0000] [Events] Listening
INFO[0000] [Bind] Starting
INFO[0000] [Bind] Binding Go Functions/Methods
INFO[0000] [Bind] Bound Function: main.basic()
INFO[0000] [WebView] Run()
```
