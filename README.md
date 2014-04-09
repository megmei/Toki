Introduction
====

```Toki``` is an incremental update tool based on [node.js][] and [node-webkit][]. Using Toki, you can package you project files which will be uploaded and upload them to remote machine. Meanwhile the configuration file auto generated by this software and linux replace shell will be uploaded and executed in order to replace old project files.

References:

[http://www.baike.com/wiki/%E5%A2%9E%E9%87%8F%E6%9B%B4%E6%96%B0][]

[http://en.wikipedia.org/wiki/Incremental_backup][]

Features
===

* Toki is written by ```node-webkit```, also user-friendly operation by using ui mode;
* Automatic connect remote machine using ssh and upload files and execute shell in background;
* ~~Automatic using some conditions to scan folder which is chosen by user and copy them to target folder~~(not achieved now);
* Toki support file and folder operate(include new, rename, delete, update, refresh and ~~view~~)

DownLoad
===
Prebuilt binaries(v0.1.0 release - Apr 4, 2014):

Windows: [win32][]

Screenshot
===
![Win32](https://github.com/JackieLin/forkme/raw/gh-pages/images/Toki/screenshot.png)

How to run Toki source code
===
* Clone Toki to the local;
* Download node.js **v0.10.x** and install;
* Download node-webkit **v0.8.x** prebuilt binaries to your computer;
* Copy ffmpegsumo.dll, icudt.dll, libEGL.dll, libGLESv2.dll, nw.exe, nw.pak, nwsnapshot.exe files to project folder;
* Open console and input ```npm install``` to install dependence node_module;
* Double click **nw.exe**(or in console input **nw** command to run);

How to release Toki using source code
===
* Clone Toki to the local;
* Download node.js **v0.10.x** and install;
* Download node-webkit **v0.8.x** prebuilt binaries to your computer;
* Open console and input ```npm install grunt-cli -g``` to install grunt-cli global;
* Open console and input ```npm install --dev``` to install dependence node_module;
* Open console and input ```grunt default``` to build the project;
* Copy ffmpegsumo.dll, icudt.dll, libEGL.dll, libGLESv2.dll, nw.exe, nw.pak, nwsnapshot.exe files to project **build folder**;
* Double click **nw.exe**(or in console input **nw** command to run);

License
===
```Toki```'s code uses MIT lincense, see our ```LICENSE``` file.

[node.js]: http://nodejs.org/
[node-webkit]: https://github.com/rogerwang/node-webkit
[http://www.baike.com/wiki/%E5%A2%9E%E9%87%8F%E6%9B%B4%E6%96%B0]: http://www.baike.com/wiki/%E5%A2%9E%E9%87%8F%E6%9B%B4%E6%96%B0
[http://en.wikipedia.org/wiki/Incremental_backup]: http://en.wikipedia.org/wiki/Incremental_backup
[win32]: http://toki.qiniudn.com/Toki_v0.1.0.exe