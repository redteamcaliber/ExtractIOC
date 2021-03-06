<p align="center"> 
<img src="http://i.imgur.com/8OOlw8V.png"></p>

### About
ExtractIOC is a Windows application built to provide assistance to cyber threat intelligence analysts. This application allows a user to import one or more IoC (Indicator of Compromise) reports and export a sorted list or report of user-specified IoC types. For example, if a user has a large list of IoC (IP and email addresses, domains, and MD5 hashes), they can specify which IoC type they want to export, export it as a flat text file or comma separated (CSV) file, implement security brackets (e.g., google[.]com instead of google.com), and filter out IoC through a user specified whitelist.


<p align="center"> 
<img src="http://www.threatfix.com/uploads/5/1/4/0/51408561/5842073.png"></p>

### Usage
To use the current version of ExtractIOC, find the "ExtractIOC.exe" file in the "\Executable" folder. No dependencies are needed to execute and use this application. In addition, find sample IoC files in the "\Executable\Test IoC Files" folder. These can be used to test the application for yourself. Finally, a whitelist example file can be found in the "\Executable\Whitelist Files" directory.

### Release Notes
* Provides user with ability to input text files that include IoC.
* Provides user with ability to select specific IoC to output.
* Provides user with ability to export IoC to a flat text or CSV file.
* Provides user ability to leverage a whitelist to prevent the extraction of unwanted IoC.
* Provides user ability to modify IoC by adding brackets to periods.

### Future Release
* Provide user with context for application functions.
* Allow user to import/export filetypes other than text files.
* Reduce false positives.
* Implement text boxes to allow for easier user modification
* Virustotal check on IoC

### Disclaimer 

ExtractIOC is not fully complete (e.g., Filenames sometimes show as domains) and as such you may (probably will) experience bugs and issues. is in beta at the moment, and you may experience issues with this app. If you're having trouble compiling or executing ExtractIOC, or have identified
a bug, or simply crashed the application - [Report it to me]. I'll do my best
to fix any issues you're having.

[Report it to me]: https://github.com/threatfix/ExtractIOC/wiki

### About
![ThreatFix](http://cdn1.editmysite.com/uploads/5/1/4/0/51408561/background-images/1387838909.png)

[Threatfix.com](http://www.threatfix.com)
