Screenshot
==========
![Screenshot](https://raw.github.com/hdni/dotfiles/master/userstyles/screenshot.png)

Installation (assuming Firefox)
===============================

* Recommended method: Install the Stylish extension to manage your userstyles: once installed, just click on "Write New Style", give it a name, and paste the CSS there.
* Go to your Firefox profile directory and make a directory called "chrome". In there, create two files: "userChrome.css" and "userContent.css". In the former, you can put CSS to theme Firefox's user interface; the latter affects websites. If you choose this method, you *will* experience issues with checkboxes and buttons not being affected by some properties (in other words, the QR and its icon won't look right). This is due to Firefox's forms.css overriding modifications made using userContent.css.

If you don't use Firefox, you'll have to adapt the 4chan stylesheet so it does not make any reference to the Gecko engine (lines starting with "-moz"). Note that since there are three websites affected by the stylesheet, each defined using @-moz-document, you might have to split the stylesheet in three parts. Needless to say, the userChrome.css won't work on other browsers.

For Firefox, I also use the FXChrome theme, and the Movable Firefox Button and Favicon Restorer extensions.