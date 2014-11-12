This is a little experiment in system tray integration on Mac OS X, inspired and
informed by:

- https://github.com/xilp/systray
- https://github.com/merlinran/systray/compare/tray-menu-for-osx#diff-b7913550f26df0fe93932596ef6086c2R56
- http://th30z.blogspot.com/2008/10/cocoa-system-statusbar-item-aka-traybar_2086.html (thanks @atavism)
- http://golang.org/cmd/cgo/
- https://code.google.com/p/go-wiki/wiki/LockOSThread

After cloning it, you can run it from the local cloned directory using:

`go run *.go`

For some reason, go install doesn't work - need to look into this.