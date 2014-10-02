app-configs
=============

Configuration files for various applications

You can use hard links to separate your repo directory and file names from the actual configuration files.
This allows for easier editing and organization from outside the configuration directories.

Copy or hard link each file into the correct locations as listed below.

--------------------
Chrome
--------------------

1. Place file in Rainbow DevTools Theme extension folder and rename to "styles.css".

Windows: C:\\Users\[username]\AppData\Local\Google\Chrome\User Data\Default\Extension\[signature]\[version]\
Mac: /Users/[username]/Library/Application Support/Google/Chrome/Default/Extensions/[signature]/[version]/

2. Enable DevTools experiments in chrome://flags.
3. Open DevTools and check "Allow UI themes" in the experiments settings panel.

--------------------
Dreamweaver
--------------------

1. color-schemes

Rename to "Colors.xml":

Windows: C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\CodeColoring\
Mac: /Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/CodeColoring/

2. doc-templates

Copy only, do not hard link. On Mac, set permissions to 775 and owner:group to root:admin:

Windows: C:\Programs Files (x86)\Adobe\Adobe Dreamweaver[version]\configuration\DocumentTypes\NewDocuments\
Mac: /Applications/Adobe\ Dreamweaver[version]/Configuration/DocumentTypes/NewDocuments

3. extensions

Extensions.txt:

Windows: C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\
Mac: /Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/

MMDocumentTypes.xml:

Windows: C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\DocumentTypes\
Mac: /Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/DocumentTypes/

