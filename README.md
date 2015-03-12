# app-configs

Configuration files for various applications

You can use soft or hard links to separate your repo directory and file names from the actual configuration files.
This allows for easier editing and organization from outside the configuration directories.

Copy or link each file into the correct locations as listed below.

# Chrome

1. Place file in Rainbow DevTools Theme extension folder and rename to "styles.css".
	
#### Windows:
`C:\Users\[username]\AppData\Local\Google\Chrome\User Data\Default\Extension\[signature]\[version]\`
	
#### Mac:
`/Users/[username]/Library/Application Support/Google/Chrome/Default/Extensions/[signature]/[version]/`

- Enable DevTools experiments in chrome://flags.
- Open DevTools and check "Allow UI themes" in the experiments settings panel.

# Dreamweaver

## color-schemes

Rename to "Colors.xml":

#### Windows:
`C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\CodeColoring\`

#### Mac:
`/Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/CodeColoring/`

## doc-templates

Copy only, do not hard link. On Mac, set permissions to 775 and owner:group to root:admin:

#### Windows:
`C:\Programs Files (x86)\Adobe\Adobe Dreamweaver[version]\configuration\DocumentTypes\NewDocuments\`

#### Mac:
`/Applications/Adobe\ Dreamweaver[version]/Configuration/DocumentTypes/NewDocuments/`

## extensions

### Extensions.txt:

#### Windows:
`C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\`

#### Mac:
`/Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/`

### MMDocumentTypes.xml:

#### Windows:
`C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\DocumentTypes\`

#### Mac:
`/Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/DocumentTypes/`

## keyboard-shortcuts

Custom keyboard shortcuts must be set within Dreamweaver from the keyboard shortcuts preference menu.

#### Windows:
`C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\Menus\Custom Sets\`

#### Mac:
`/Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/Menus/Custom Sets/`

## toolbars

Copy only, do not hard link. On Mac, set permissions to 775 and owner:group to root:admin:

#### Windows:
`C:\Programs Files (x86)\Adobe\Adobe Dreamweaver[version]\configuration\Toolbars\`

#### Mac:
`/Applications/Adobe\ Dreamweaver[version]/Configuration/Toolbars/`

## workspaces

Workspaces must be selected in Dreamweaver after they have been added to the configuration folder.

#### Windows:
`C:\Users\[username]\AppData\Roaming\Adobe\Dreamweaver[version]\[language]\Configuration\Workspace\`

#### Mac:
`/Users/[username]/Library/Application\ Support/Adobe/Dreamweaver[version]/[language]/Configuration/Workspace/`

# Terminal

All file paths in the `terminal` directory represent relative paths from the user home directory. Hard or soft links can be created in the directories where these files need to be placed to enable them.

To use the custom bash configurations, include the following code at the top or `.bash_profile`:

	if [ -f ~/.bash_common_profile ]; then
		. ~/.bash_common_profile
	fi

The above snippet will load the custom cofigurations into bash.

The remaining files and directories should be hard or soft links wherever applicable.

