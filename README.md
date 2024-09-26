Greenshot - a free screenshot tool optimized for productivity
=============================================================

Welcome to the source repository for Greenshot

What is Greenshot?
------------------

Greenshot is a light-weight screenshot software tool for Windows with the following key features:

* Quickly create screenshots of a selected region, window or fullscreen; you can even capture complete (scrolling) web pages from Internet Explorer.
* Easily annotate, highlight or obfuscate parts of the screenshot.
* Export the screenshot in various ways: save to file, send to printer, copy to clipboard, attach to e-mail, send Office programs or upload to photo sites like Flickr or Picasa, and others.
and a lot more options simplyfying creation of and work with screenshots every day.

Being easy to understand and configurable, Greenshot is an efficient tool for project managers, software developers, technical writers, testers and anyone else creating screenshots.


[If you find that Greenshot saves you a lot of time and/or money, you are very welcome to support the development of this screenshot software.](https://getgreenshot.org/support/)


About this repository
---------------------
This repository is for Greenshot 1.3, currently in development, but is the next planned release

Releases
--------

You can find a list of all releases (stable and unstable) in the [Github releases](https://github.com/greenshot/greenshot/releases) or in the [version history on our website](https://getgreenshot.org/version-history/).
The [downloads page on our website](https://getgreenshot.org/downloads/) always links to the latest stable release.

Getting Started for Developers:
-------------------------------

These instructions are made to assist developers in getting started with Greenshot so they can contribute to the repository. Please verify system prerequisites are met before trying to build.

IDE System Requirements:
------------------------

* Windows OS environment
* Greenshot is build using (as of this writing) .net Framework 4.7.2. This means any version between .net Framework 4.7.2-4.8.1 will suffice. 
* Visual Studio 2017 or newer

Build Instructions:
-------------------

* Open Visual Studio
* Clone GitHub Repository using Visual Studio, using the link in the green code button above. Alternatively, you can download the repository to your machine and open the solution file located in /src/Greenshot.sln.
* Choose Build->Build Solution in Visual Studio to build binaries.
* Verify all components are built successfully.
* You are ready to start contributing to Greenshot.

How to contribute:
------------------

* Create your own fork of the main repository
* Make desired changes (REMEMBER: keep commits small and concise, don't try to add multiple separate changes at once)
* Submit a pull request for review. Your request will be reviewed and either accepted, denied, or you may be asked to make revisions before your code is accepted.
