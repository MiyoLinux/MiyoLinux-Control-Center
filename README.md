# MiyoLinux-Control-Center

![alt text](http://miyolinux.weebly.com/uploads/1/3/7/0/13707080/editor/screenshot-from-2018-03-06-17-38-05.png?1520376381)

Requires: yad

You will also need to create folders containing applications copied from /usr/share/applications (or elsewhere), and you'll need to create text editor links in order to open configuration files.

The MiyoLinux Control Center simply groups applications together (under tabs) allowing a user to change the look, settings, and configuration of their Openbox system from a central location.

Each tab has its own set of applications that have been placed into a specific folder for that specific tab. You will need to edit the current code in order to point to your own folders that you create. You can simply copy and paste applications from /usr/share/applications into the folders that you create. As an example, you will see in the snippet of code below that the "System" tab (of the Control Panel) points to a specific folder named system as created in /usr/share/miyolinux/control-panel/

--read-dir="/usr/share/miyolinux/control-panel/system"

Within that "system" folder, I copied and pasted the applications from /usr/share/applications that I wanted to appear in that tab. 

As you look over the code, you will see that each tab points to its own end folder. However, under the Configuration Files tab are buttons that merely link to the configuration files that will open with your designated text editor.

Please note, in the code, the EDITOR is designated as Leafpad, so you may need to change that to your preferred text editor also.


<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://miyolinux.weebly.com/">
    <span property="dct:title">MiyoLinux</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">MiyoLinux Accessories</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="http://miyolinux.weebly.com/">
  United States</span>.
</p>
