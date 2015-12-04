# Better xampp applet for Cinnamon panel
Xampp panel applet with additional features. Originally developed by backids99@gmail.com.
![2014-12-20 20 38 27-1](https://cloud.githubusercontent.com/assets/6773202/5892977/9d5deb48-a4dc-11e4-85fb-f26955ac3cbd.png)

## Installation

* Clone the repository and install the files into the cinnamon applet directory;
<pre>
    $ git clone https://github.com/probil/cinnamon-better-xampp-applet.git --depth=1
    $ cp -r cinnamon-better-xampp-applet/better-xampp-applet@m_lyashuk ~/.local/share/cinnamon/applets
</pre>
* Alternatively, if you don't have GIT installed you can just download zip file
<pre>
    $ wget https://github.com/probil/cinnamon-better-xampp-applet/archive/master.zip -O better-xampp-applet.zip
    $ unzip better-xampp-applet.zip
    cp -r better-xampp-applet/better-xampp-applet@m_lyashuk ~/.local/share/cinnamon/applets
</pre>
* You may need to restart cinnamon, press ALT-F2 and enter 'r'
* Finally, enable the applet by going to Menu->Settings->Applets

## Changelog

### Version 0.2-1
* New SVG-icon. Applet now looks like other cinnamon applets.
* Remove old icons

### Version 0.2
* Added Xampp Control Panel item
* Original icon changed by b/w icon with opacity (look better on dark panels)
* Added SVG icon disabled by default (need color change)
