# iOS APP ICONS Generator

### Description
ios-icon-generator is a shell script which aim to generate iOS APP icons easier and simply.
![image](https://github.com/wacumov/ios-icon-generator/blob/master/ios-icon-generator.gif)
<pre>
VERSION: 2.0.0
USAGE:
    ./ios-icon-generator.sh srcfile dstpath

DESCRIPTION:
    This script aim to generate iOS APP icons easier and simply.

    srcfile - The source png image. Preferably above 1024x1024
    dstpath - The destination path where the icons generate to.

AUTHOR:
    smallmuou<smallmuou@163.com>

EXAMPLE:
    ./ios-icon-generator.sh 1024.png ~/123

</pre>

### Usage

1. Clone
```bash
git clone https://github.com/wacumov/ios-icon-generator
cd ios-icon-generator
chmod 777 ios-icon-generator.sh
```

2. Run
	
```bash
smou:ios-icon-generator $ ./ios-icon-generator.sh 1024.png ~/output/
[INFO] Generate Icon-20.png ...
[INFO] Generate Icon-20@2x.png ...
[INFO] Generate Icon-20@3x.png ...
[INFO] Generate Icon-29.png ...
[INFO] Generate Icon-29@2x.png ...
[INFO] Generate Icon-29@3x.png ...
[INFO] Generate Icon-40@2x.png ...
[INFO] Generate Icon-40@3x.png ...
[INFO] Generate Icon-60@3x.png ...
[INFO] Generate Icon-50.png ...
[INFO] Generate Icon-50@2x.png ...
[INFO] Generate Icon-57.png ...
[INFO] Generate Icon-57@2x.png ...
[INFO] Generate Icon-72.png ...
[INFO] Generate Icon-72@2x.png ...
[INFO] Generate Icon-76.png ...
[INFO] Generate Icon-76@2x.png ...
[INFO] Generate Icon-83.5@2x.png ...
[INFO] Generate Icon-1024.png ...
[INFO] Congratulation. All icons for iOS APP are generate to the directory: ~/output.
```
PS: You can find out the icons in ~/output directory.

### Refer
* [iOS Icons Size](https://developer.apple.com/design/human-interface-guidelines/ios/icons-and-images/app-icon/)

### License
This script follow MIT license.
