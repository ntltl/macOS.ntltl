# macOS.ntltl

### Forums & Blogs

* [Apple Developer Forums](https://developer.apple.com/forums/)

### Resources

* [Apple Services Performance Partners](https://affiliate.itunes.apple.com/resources/)

### Q & A

1. Want to connect with the currently logged in user when using a VNC viewer rather than seeing the Login Window (ARD 3.5/OS X 10.7 and later)?
```
sudo defaults write /Library/Preferences/com.apple.RemoteManagement VNCAlwaysStartOnConsole -bool true
```
