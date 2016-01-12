Installing and configuring Sublime on your home Macintosch computer
=============================

To use Sublime at home, you will need to install Processing as well as Sublime.

Download Sublime Text 3 and download and install Processing
---------------
1. Go to [http://www.sublimetext.com/3](http://www.sublimetext.com/3) and download Sublime Text 3 for OSX. 
2. Don't install Sublime just yet
3. Download version 3 of [Processing](https://processing.org/download/?processing)
4. Drag the Processing icon into your applications folder
5. Once you have moved the Processing icon, double click on it in applications and it will open to a new project. Once in processing, go to *Tools* and click on *Install processing.java*.
6. When asked if you want to install processing for all users, you must click *yes* (processing will not work with sublime otherwise)
After clicking *yes*, input you computer login and processing will install.
7. Now in order for processing to install correctly, restart your computer

Install Sublime Text 3
------------------
1. After you restart, Install Sublime Text 3 from downloads by double clicking on the .dmg file.
2. When promoted, agree to everything, and drag Sublime Text into your application folder in the opened window


Install Package Control for Sublime
---------------
1. Start Sublime
2. Choose *View | Show Console*
3. Open a browser, and go to [https://packagecontrol.io/installation](The Sublime Package Control Installation page)
4. Copy the code that sarts with `import urllib.request`
5. Paste that in the console in Sublime and press enter
6. (If Package control gives you an error or a message saying “missing dependencies”, just ignore it and click *ok*, the next step will fix this.)
7. In order for package control to install without errors, we need restart the computer again (don’t ask me why it work, it just does)

Install the Processing plugin for Sublime
---------------
1. Once you’ve restarted, open Sublime and check that under *Sublime Text > Preferences* it says *package control* at the bottom of the list (or anywhere in Sublime Text > Preferences)
2. Click on the line that says “package control” and it will open the package control console.
3. Type “Install Package” into the search bar, and click on the line in the results that says “Package Control: Install Package”
4. Once you click install package, you will be taken to a list of packages. Search “Processing” and click on the result that simple says “Processing” to install processing.
5. Once processing is install, Right clock on Sublime in the Dock, and click quit. (simple clicking the red bottom will NOT stop the Sublime background scripts.)


Configure the Processing plugin for Sublime
---------------
1. Restart Sublime
2. In Sublime choose *Tools | Build System | Processing*
3. Choose *View | Syntax | Processing*

Congratulations, you’ve installed Sublime Text 3 with Processing!

