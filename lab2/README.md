# Summary
In this lab you will analyze a set of digital objects and determine what they are and how they are different.

# Recommended Tools
In order to identify these objects, you can use any of the tools below. The only tool that is necessary is the Siegfried [online interface](https://www.itforarchivists.com/siegfried). If you'd like to install, DROID see instructions at the bottom of this document.

Not all objects will be accessible with all tools.

## Format Identification
* [Siegfried](https://github.com/richardlehane/siegfried)
* [DROID](https://www.nationalarchives.gov.uk/information-management/manage-information/preserving-digital-records/droid/)

### Installing DROID

#### macOS
1. Download the most recent version from [this page](http://www.nationalarchives.gov.uk/information-management/manage-information/preserving-digital-records/droid/), unzip the package, and open it in a Finder window
2. Open a terminal window
    * open Finder, go to Applications, then Utilities, and open Terminal
    * press ⌘ + spacebar, and search for Terminal and press enter.
3. In Terminal, navigate to your unzipped package
    * type `cd` and a space, drag the unzipped folder's icon from Finder to the Terminal, and press enter
4. In Terminal, make the program executable. Copy-paste and press enter for each of the following lines
    * `chmod +x droid.sh`
    * `chmod +x droid-ui-6.4.jar`
    * `chmod +x droid-command-line-6.4.jar`
5. In Terminal, start the program by typing `./droid.sh`
    * If you get an error about JDK, you'll have to [install JDK](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). After installing JDK, try step 5 again.
    * If you get an error about Java, you'll have to [install Java](https://www.oracle.com/technetwork/java/javase/downloads/index.html). After installing Java, try step 5 again.
    * For other errors, copy-paste your terminal in an email to me.

#### Windows
1. Download the most recent version from [this page](http://www.nationalarchives.gov.uk/information-management/manage-information/preserving-digital-records/droid/), unzip the package, and open it.
2. Double-click the `droid.bat` file.
    * If you get an error about Java, you'll have to [install Java](https://www.oracle.com/technetwork/java/javase/downloads/index.html). After installing Java, try step 5 again.
    * For other errors, please email to me.
    
### Installing Siegfried
#### macOS
1. With homebrew installed, open a terminal window
    * `brew install richardlehane/digipres/siegfried`

#### Windows
1. Download latest version ([1.7.9](https://github.com/richardlehane/siegfried/releases/download/v1.7.9/siegfried_1-7-9_win64.zip))
2. Copy to a location in your system path. `C:/Program Files` will probably work, but if not check the values as described [here](https://www.computerhope.com/issues/ch000549.htm).
3. Open a terminal and run the `sf -update` command to download the latest signatures.


## Format Knowledgebase
* [PRONOM](https://www.nationalarchives.gov.uk/PRONOM/BasicSearch/proBasicSearch.aspx?status=new)
* [Sustainability of Digital Formats](https://www.loc.gov/preservation/digital/formats/)
* [TRiD](http://mark0.net/soft-trid-deflist.html)
* [Just Solve It](http://fileformats.archiveteam.org/wiki/Main_Page)
* [Digipres.org](http://www.digipres.org/formats/)
* Wikipedia

## Hex Editors
* [Hexed.it](hexed.it)
* [Binvis](binvis.io)


