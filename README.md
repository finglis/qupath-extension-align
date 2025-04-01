# QuPath Align extension

Welcome to the image alignment extension for [QuPath](http://qupath.github.io)!

This was previously the *Interactive image alignment* command in QuPath v0.2.
Not much loved by its creator, this command has proven useful to numerous people 
on the [Scientific Community Image Forum](http://image.sc).

It has been separated out to its own repository so that it can be developed 
independently from the main QuPath project.
And perhaps so someone will fork it and make a better version.


## Installing

The QuPath Align extension can be downloaded and managed within QuPath using 
the extension mananger which can be found under the menu `Extensions -> Manage Extensions`. 
The extension will be listed under "QuPath catalog" and can be downloaded and installed 
by selecting the green plus button. 

Alternatvley, the align extension can be installed by downloading the latest 
`qupath-extension-align-[version].jar` file from [releases](https://github.com/qupath/qupath-extension-align/releases) 
and drag it onto the main QuPath window.

If you haven't installed any extensions before, you'll be prompted to select a QuPath user directory.
The extension will then be copied to a location inside that directory.

You might then need to restart QuPath (but not your computer).


## Building

You can build the extension from source with

```bash
gradlew clean build
```

The output .jar will be under `build/libs`.

