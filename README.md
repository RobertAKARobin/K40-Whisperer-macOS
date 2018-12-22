# k40 Whisperer for macOS

In this repo you can find the necessary files to build K40 Whisperer v0.27 for macOS. The files regarding Linux and Windows systems have been removed.

## Build instructions

```bash
pip install -r requirements.txt
sh build_app.sh
```

You'll need to install the [USB drivers](https://www.ftdichip.com/Drivers/VCP.htm) to be able to control the machine.

## Known problems
There's a some weird behavour in macOS Mojave that maket Tkinter buttons not show for an app built with py2app. **To make the buttons show just resize the window.**



Original K40 Whisperer by [Scorch Works](http://www.scorchworks.com/K40whisperer/k40whisperer.html)