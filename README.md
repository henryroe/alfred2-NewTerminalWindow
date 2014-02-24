alfred2-NewTerminalWindow
=========================

Alfred2 workflow to open a new Terminal.app window of type ['Basic', 'Grass', 'Homebrew', etc..]

# Installation

[Download current version from here](https://github.com/henryroe/alfred2-NewTerminalWindow/blob/master/New%20Terminal%20Window.alfredworkflow?raw=true)

# Usage

Type `nt` to see a list of available types of Terminal.app windows to open.  

Select the one you want with ⌘-[#] or arrow keys and then Return.

Or, restrict the list with a minimum match, e.g. `ntg` will show all options starting with a *g*.

# Screenshots

![Basic usage with `nt`](https://dl.dropboxusercontent.com/u/6753318/github/screenshots/alfred2-NewTerminalWorkflow-screenshot1.png)
![Basic usage with minimum match completion, e.g. `ntr`](https://dl.dropboxusercontent.com/u/6753318/github/screenshots/alfred2-NewTerminalWorkflow-screenshot2.png)


# Extending to additional Terminal.app window profiles

The list of offered terminal types is gathered from screen snapshots sitting inside the workflow.  The names of the snapshots must match exactly (spaces and capitalization) the menu item in Terminal, e.g. to get the Red Sands profile the screenshot file should be named `Red Sands.png`.  (If you need to manipulate the files on the command line, recall that spaces need to be escaped as `"\ "`.)

To remove options, simply remove the appropriate *png* file from the Workflow directory.

To add options, open a new terminal window of the new profile, take a screen snapshot (⌘-4 followed by space bar followed by clicking on the window; the screenshot will then be on your Desktop).  Rename the screenshot as above and move to the Workflow directory.
