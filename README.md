# Sublime - React Create Component

A plugin for creating React Components in Sublime Text 2 and 3.

This plugin adds a context menu to Sublime's side bar that makes it simple
to create a React Component in a parent folder. Simply give the component a
name and answer the prompts, then a folder is created inside the parent with:

```
parent/
|-- ComponentName/
|---- index.js
|---- style.less
```

The stylesheet extension can be chosen from `.css`, `.less`, `.scss`, or
`.sass`, and can optionally include `*.module.*` (for css-modules)
automatically.

The `index.js` file can be a Functional or Class component and will
contain some helpful skeleton code.


## Installation

With [Package Control](http://wbond.net/sublime_packages/package_control):
1. Run "Package Control: Install Package" command
2. Find and install `React Create Component` plugin
3. Restart Sublime Text (if required)

Manually:
1. Clone or download this git repo into your packages folder (click
Browse Packages to open this folder)
3. Restart Sublime Text (if required)


## Usage

Whenever you need to create a new component, just right click on the base
folder and select Create React Component. It will:

  1. Ask for a component type (select, then press `ENTER`)
  2. Ask for a stylesheet type (select, then press `ENTER`)
  3. Ask if you want CSS Modules enabled (select, then press `ENTER`)
  4. Ask for a component name (type, then press `ENTER`)
  5. Create a new folder for the component with the given name
	6. Add an `index.js` file with skeleton code
  7. Add a stylesheet based on the given preferences


## More Info and Bug Tracking

You can get the latest code, make suggestions or report bugs at
[https://github.com/acsands13/](https://github.com/acsands13/).

Based off
[Python Create Package](https://github.com/curaloucura/SublimePythonPackage)
by [curaloucura](https://github.com/curaloucura).
