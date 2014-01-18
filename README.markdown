CoffeeScript.tmbundle
---------------------

A **TextMate Bundle** for the **CoffeeScript** programming language.
    
Installation:
-------------

    cd ~/Library/Application\ Support/TextMate/Bundles (Textmate 1)
    cd /Applications/TextMate.app/Contents/SharedSupport/Bundles (Textmate 1.5.10 & 2)
    git clone git://github.com/KingHenne/coffee-script-tmbundle CoffeeScriptBundle.tmbundle

The bundle includes syntax highlighting, the ability to compile or evaluate CoffeeScript inline, convenient symbol listing for functions, and a number of expando snippets.

Patches for additions are always welcome.

![screenshot](http://jashkenas.s3.amazonaws.com/images/coffeescript/textmate-highlighting.png)

If your TextMate.app is having trouble finding the `coffee` command, remember that [TextMate doesn't inherit your regular PATH](http://wiki.macromates.com/Troubleshooting/TextMateAndThePath). 

This fork also includes basic [Eco](https://github.com/sstephenson/eco) syntax highlighting by [Radosław Pietruszewski](https://github.com/radex) and a handful of Mocha BDD snippets by [Mark Bates](https://github.com/markbates).
