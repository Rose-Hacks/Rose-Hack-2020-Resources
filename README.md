<!-- a normal html comment -->
# Rose Hack 2020 - Hacker Resources
Welcome to Rose Hack 2020! Here we've compiled some helptul guides and tutorials that you might find useful this weekend. If you have any further questions about anything here, you can request help from mentors from Slack. Happy hacking!

## :computer: terminal
The terminal on your computer is one of the most powerful resources you have when building a project. Terminal setups can be different for different operating systems; Once you get yours up and running you'll be pushing pixels in no time.
### MacOS
* [XCode](https://developer.apple.com/xcode/)
  * an IDE (integrated development environment) created by Apple with a large variety of programming language support
  * an all-in-one package with a text editor, compiler, and build system
* [Homebrew](https://brew.sh)
  * a package manager for macOS and Linux
  * allows you to easily install packages you might want to use that macOS or Linux didn't already come with
 
### Windows
* [Ubuntu](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab)
    * a Linux subsystem for your Windows machine
    * Don't forget to enable Windows Subsystems: (https://developerinsider.co/stepwise-guide-to-enable-windows-10-subsystem-for-linux/)
    * Tip: the Ubuntu bash should have access to your Windows-based disks under `/mnt`. You can add a `cd` statement to your sybsystem's .bashrc (you can open yours in vim by entering `vim ~/.bashrc`, and add yours to the bottom).
      * Example: `cd /mnt/c/Users/janin/Documents`

## :octocat: GitHub/Git
* [Git](https://git-scm.com/)
   * version control and file version management system
   * lets you maintain consistent versions of code
   * useful for collaborating on a potentially large code base with several people
* [GitHub](https://github.com/)
   * a web-based hosting service for version control using Git
   * offers all of the distributed version control and source code management functionality of Git as well as adding its own features
* Git Commands - save, branch, checkout, track, upload, download, share, collaborate on, control versions of, revert, delete, nuke, etc. 
* Get free access to lots of powerful developer tood with the [GitHub Student Developer Pack](https://education.github.com/pack).
* Forgot a Git command? Here's the [GitHub's Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf).
* ReadMe Documents and Markdown
  * you're reading a README.md document right now! ReadMe documents contain information for the user about your software, tool, game, etc. 
  * [Markdown Cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Text Editors/IDE's: Places to Edit Your Code
1. [Sublime Text 3](https://www.sublimetext.com/3) - light-weight, highly customizable, now has a companion app for [git integration](https://www.sublimemerge.com/)
2. [Visual Studio](https://visualstudio.microsoft.com) - integrated development environment, used to develop computer programs, as well as websites, web apps, web services and mobile apps, developed by Microsoft
3. [Visual Studio Code](https://code.visualstudio.com) - light-weight, highly customizable source-code editor developed by Microsoft
4. [IntelliJ](https://www.jetbrains.com/idea/) - optimized integrated environment for developing in Java, developed by JetBrains
5.  [Android Studio](https://developer.android.com/studio) - the official integrated development environment for Google's Android operating system
6. [XCode](https://developer.apple.com/xcode/) - optimized for building iOS apps, includes 10+ gigabytes of other useful general purpose languages/libraries/tools
7. [Atom](https://atom.io/) - has plug-ins written in Node.js, embedded Git Control, developed by GitHub
8. [Vim](https://www.vim.org/) - highly customizable, edit code without having to leave your terminal
9. [Emacs](https://www.gnu.org/software/emacs/tour/) - extensible, customizable, self-documenting real-time display editor
10. [Arduino IDE](https://www.arduino.cc/en/Main/Software) - optimized for uploading code to Arduino microcontrollers

### XYZ Domain Service
[Video On XYZ Domain Service](https://www.dropbox.com/s/7v8tch5i24h0vv2/video-instructions_how-to-rregister-domain-xyz.mp4?dl=0)

Instructions on registering your free .xyz domain:
1. [Search for your .xyz domain](https://gen.xyz/register), then “Go to checkout”
2. Select a 1 year term
3. Click “Next: Recommended Add-Ons” and choose any add-ons you’d like
4. Click “Next: Information & Checkout”
o Enter promo code: ROSEHACK20 new total is $0.00
5. Enter your contact details
6. Choose PayPal or Credit Card as preferred payment method
7. Check ✓ the box next to “I agree to...”
8. Click “Submit Order”

### Package Managers (runs on any OS)
* [Pip](https://pypi.org/project/pip/)
   * the recommended package manager/installer for the Python language
   * lets you quickly install and import libraries and packages to run in Python
* [npm](https://www.npmjs.com)
   * a package manager specifically for the JavaScript Language
   * the go to tool for getting packages for Node.JS

## General Purpose Programming Languages
1. [C++](http://www.cplusplus.com/) - object-oriented, allows for low level data manipulation 
   * [Learn C++ - The Definitive Guide](https://www.programiz.com/cpp-programming)
   * [Learn-Cpp.org](https://www.learn-cpp.org/)
   * [Tutorials Point - C++](https://www.tutorialspoint.com/cplusplus/)
2. [C#](https://www.microsoft.com/net/download) - intended to modernize paradigms set up by C++ and C, object-oriented
   * [C# repo on GitHub](https://github.com/dotnet/csharplang)
   * [CSharp Station](https://csharp-station.com/)
   * [Learn-CS.org](https://www.tutorialspoint.com/cplusplus/)
3. [Python](https://www.python.org/) - high level, emphasizes code readability
   * [Python.org's "Python For Beginners"](https://www.python.org/about/gettingstarted/)
   * [LearnPython.org](https://www.learnpython.org/)
   * [The Hitchhiker's Guide to Python](https://docs.python-guide.org/intro/learning/)
4. [Java](https://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html) - heavily class-based and object-oriented 
   * [LearnJavaOnline.org](https://www.learnjavaonline.org/)
    * [Net Beans - Learning Java Resources](https://netbeans.org/kb/articles/learn-java.html)
5. [JavaScript](https://www.javascript.com/) - high level, the dominant programming language of the web
   * [W3 Schools - Learn JavaScript](https://www.w3schools.com/js/)
   * [Mozilla Developer Network - JavaScript Tutorial](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
   * [The Modern JavaScript Tutorial](https://javascript.info/)

## Web Development
### Starting Out
  1.  [HTML](https://html.com/) - the "content" of a web page
      * [Mozilla Developer Network - HTML Tutorial](https://developer.mozilla.org/en-US/docs/Learn/HTML)
      * [Learn-HTML.org](https://www.learn-html.org/)
      * [W3 Schools - HTML Tutorial](https://www.w3schools.com/html/)
  2.  [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - dictates the style and character of a web page
      * [CSS Zen Garden](http://www.csszengarden.com/)
      * [CSS-Tricks.com](https://www.css-tricks.com/)
      * [Zen Dev - Ultimate Guide to CSS](https://zendev.com/ultimate-guide-to-learning-css.html)
3. [JavaScript](https://www.javascript.com/) - high level, the dominant programming language of the web, makes webpages dynamic
   * [W3 Schools - Learn JavaScript](https://www.w3schools.com/js/)
   * [Mozilla Developer Network - JavaScript Tutorial](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
   * [The Modern JavaScript Tutorial](https://javascript.info/)


### More Advanced Stuff
***Back-End Development:*** code that connects the web-page to a database, manages user connections, and powers the web application itself

Common Back-End Frameworks/Tools
 * JavaScript
    * [Node.JS](https://nodejs.org/en/) - JavaScript run-time environment that executes JavaScript code outside of a browser
    * [Express](https://expressjs.com/) - web application framework for Node.js, designed for building web applications and APIs
 * Python
    * [Flask](http://flask.pocoo.org/) - micro web framework written in Python, easy to pick up
    * [Django](https://www.djangoproject.com/) - model-view-template oriented, highly customizable (citrushack.com was built with this!)
    * [.NET](https://dotnet.microsoft.com/download/dotnet-framework) -  a software framework optimized for building any kind application for Windows, developed by Microsoft

***Front-End Development:*** the practice of converting data to graphical interface for user to view and interact with data through digital interaction using HTML, CSS and JavaScript

Common Front-End Frameworks/Tools (used in conjunction with vanilla HTML/CSS/JavaScript)
 * HTML/CSS/JS
    * [Bootstrap](https://getbootstrap.com/) - CSS/JS library that makes responsiveness between mobile and desktop web pages easy
    * [Semantic UI](https://semantic-ui.com/) - quickly build web pages with sleek, modern, and dynamically designed elements  
   * [Font Awesome](https://fontawesome.com/) - font and icon toolkit for simple yet effective icons and typography
   * [jQuery](https://jquery.com) - JavaScript library designed to simplify HTML DOM tree traversal and manipulation
 * pure JavaScript (all of which are extremely powerful and robust)
    * [AngularJS](https://nodejs.org/en/) - structural framework for dynamic web apps, good for single-page applications, maintained by Google
    * [ReactJS](https://reactjs.org/) - JavaScript library for building user interfaces, 'reacts' to user and dynamically changes the content of a web page, maintained by FaceBook
   * [VueJS](https://vuejs.org/) - open-source JavaScript library for building dynamic user interfaces, easy to pick up

## Hardware Hacking


Arduino IDE
* the [official integrated development environment](https://www.arduino.cc/en/Main/Software) for Arduino programming
* optimized for uploading code to Arduino microcontrollers

## Virtual/Augmented Reality
[Unity]([https://unity3d.com/unity/whats-new/unity-2017.3.1)
* a real-time 3D development platform
* drag and drop static assets into your 3D scene
* code dynamic elements events and elements using the C# language

[Oculus - Unity SDK](https://developer.oculus.com/unity/)
* the official software development kit for Oculus Rift hardware within Unity

[VRTK - The All In One Virtual Reality Tool Kit for Unity](https://vrtoolkit.readme.io/)
* comes with integrated GearVR and OculusVR SDKs
* prebuilt libraries for locomotion, object-interaction, clipping, and more


## Mobile Development
[React Native](https://facebook.github.io/react-native/docs/getting-started.html)
* build mobile apps in a React JS integrated environment
* good for both Android and iOS applications

    
[Swift](https://docs.swift.org/swift-book/GuidedTour/GuidedTour.html)
* for iOS app development
*  Xcode is the proprietary development environment
    

[Java](https://developer.android.com/studio/) 
* for Android app development
* Android Studio is the recommended development environment

[Flutter](https://flutter.dev)
* an open-source mobile application development framework
* good for both Android and iOS applications
