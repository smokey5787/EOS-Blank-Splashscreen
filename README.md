# EOS-Blank-Splashscreen
A simple splash screen
A quick guide to make a custom splashscreen for KDE Plasma

This is just a quick guide I have put together for anyone wanting to customise their splashscreen in KDE Plasma, It is not complete and mainly to help people get a quick start.

1. Rename the folder to what you want to call your splashscreen
2. Inside the folder oppen metadata.desktop and change the following lines to match the name of the folder
-Comment, Name, X-KDE-PluginInfo-Name
and change to your name
X-KDE-PluginInfo-Author
3. Open contents/splash/images and copy the image you wish to use for the background, rename this image background.png
-If the file is not a png you can either convert the image or change the following line in Splash.qml source: "images/background.png" to the name and extension of your picture.
4.You can also change the logo the same way
5. Other colours etc you may want to change can be found in Splash.qml and use a hex code

![alt text](https://github.com/smokey5787/EOS-Blank-Splashscreen/blob/main/EOS-Blank/contents/previews/splash.png "preview")
