## ResizedIcons
![image](https://github.com/abredo/ResizedIcons/blob/master/ResizeIcon.gif) 
===========
iOS 自动生成对应尺寸图标的脚本，只需要更改脚本里面的尺寸数组和对应的文件名数组，就可以生成对应大小的图标。
A Shell Script for generating resized icons for uploading iOS App to AppStore
*  Generating resized icons for uploading iOS App to AppStore, matches  the size like 'Icon-29.png' 'Icon-29@2x.png' 'Icon-29@3x.png' 'Icon-40.png' 'Icon-40@2x.png' 'Icon-40@3x.png' 'Icon-60@2x.png' 'Icon-60@3x.png' 'Icon-76.png' 'Icon-76@2x.png' 'Icon-83.5@2x.png'
* Getting Started
    * 1. Replace the "icon.png" with your icon that matches the size 1024 * 1024
    * 2. Open your terminal in OS X, 'cd' into the folder that contains 'icon.png' and 'ics.sh'
    * 3. Use the shell command 'chmod +x' to make the 'ics.sh' executable and execute it.

## More
   * For customized needs, change the contents of  'name_array' or  'size_array' in  ics.sh. And make sure the 'filename' consistent with      the name of your icon file.
