# Insidious Launcher 1.1
It seems you have stumbled upon the official InsidiousRP Launcher!
Full disclosure: I'm not artistic or creative 😕

### Installation:
Installing this launcher is easy as no-bake cookies.
All you have to do is this:
- Click the green "Code" button, then select "Download Zip."
- Extract the zip file (drag & drop contents) to any directory (folder) of your choosing, but remember to keep the files together!
- (Optional) Right click the Insidious.exe file and select "Send To" > "Desktop" for a shortcut you can move anywhere in your computer!

And that's all there is to it! Happy gaming!

PS: Please update when updates are available, I don't want to force them. 😊

# [Insidious Discord](discord.gg/insidiousrp)

### Cache Clearing

If you seem to be having issues where the cache clearing button isn't actually clearing the cache,
edit the "cache.bat" file that comes with the launcher.

Replace all
```
C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\
```
instances with the directory of your game's cache. Be sure not to remove anything after the cache directory's trailing slash.

For example:
old:
```
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\browser" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\db" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\dunno" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\priv" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\servers" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\subprocess" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\unconfirmed" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\crashometry" /s /f /q
del "C:\Users\%username%\AppData\Local\FiveM\FiveM.app\cache\launcher_skip_mtl2" /s /f /q
```
new:
```
del "New-Directory-To-Cache\browser" /s /f /q
del "New-Directory-To-Cache\db" /s /f /q
del "New-Directory-To-Cache\dunno" /s /f /q
del "New-Directory-To-Cache\priv" /s /f /q
del "New-Directory-To-Cache\servers" /s /f /q
del "New-Directory-To-Cache\subprocess" /s /f /q
del "New-Directory-To-Cache\unconfirmed" /s /f /q
del "New-Directory-To-Cache\crashometry" /s /f /q
del "New-Directory-To-Cache\launcher_skip_mtl2" /s /f /q
```