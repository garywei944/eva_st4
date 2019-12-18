# Ær1S_ST3
## Description
Custom configuration for Sublime Text 3. It sets up ST3 as the most powerful and fantastic IDE for all languages on all 3 popular operating systems. 
#### ***[Package Control](https://packagecontrol.io) is indispensable.***

## Why you may need it?
Sublime Text 3 is a powerful, concise, and graceful text editor that allows you to extend it with numerous fantastic packages maintained by the community and configure it nicely as a coder. At the meantime it's not as complicated as emacs or vim. Anyway it's my first love.  
  
However, it's always hard to ice break. Trying out all popular packages, figuring out which are better, which are necessary, and setting up the configuration to make it works as an IDE took me plenty of time. Same problem happens to everyone who begins to use a new software. So if you're first to ST3 and want to try out fantastic packages people are using, clone the repository and give it a shoot.

## Usage
1. ***(IMPORTANT) Install [Package Control](https://packagecontrol.io/installation)***
2. Click the `Preferences` > `Browse Packages…` menu
3. Change to last level directory, usually named `Sublime Text 3`
4. Delete `Packages` Folder
5. Download or clone the whole repository and rename it to `Packages`
```
git clone git@github.com:garywei944/aris_st3.git Packages
```
6. Restart Sublime Text 3 and the packages will be installed automately.  
***If error occurs during installation, restart ST3 several times and it will be fixed automatically.***
7. There is some personal information at `./User/SublimeTmpl.sublime-settings`, please change it if you want to use `SublimeTmpl`.
8. Install the dependencies followed if needed.

## Dependencies
Most of the dependencies are not necessary, but some packages may not work with full features then.
### Environments
* [`git`](https://git-scm.com/)
* [**Python**](https://www.python.org/) and `pip` (or **Python 3** and `pip3`)
* [**Node.js**](https://nodejs.org/en/)(`npm`)
* [**Tex Live**](https://www.tug.org/texlive/)(*Windows* and *Linux*) or [**MacTex**](http://www.tug.org/mactex/)(*Mac OS*)

### Packages
* **CodeIntel** (`pip3 install --upgrade --pre CodeIntel`) - SublimeCodeIntel
* **jshint** (`npm install -g jshint`) - SublimeLinter-jshint
* **csslint** (`npm install -g csslint`) - SublimeLinter-csslint
* **xg-htmlhint** (`npm install -g xg-htmlhint`) - SublimeLinter-contrib-htmlhint

### Terminals
*These terminals are optional, and can be changed via `./User/Terminal (<System>).sublime-settings`*
* **Windows**: [*Cmder*](https://cmder.net/)
* **Mac OS**: [*iTerm2*](https://iterm2.com/)

## Sublime Packages
### Function Enhancement
* A File Icon
* AdvancedNewFile
* Codecs33
* ConvertToUTF8
* FileDiffs
* HexViewer
* Package Control
* PlainTasks
* *~~Preferences Editor~~ (Temporary unavailable)*
* ReadmePlease
* SideBarEnhancements
* SublimeTmpl
* Terminal
* TodoReview
* View In Browser

### Git
* Git
* Github Tools
* Gitignore
* GitGutter

### General Coding
* Alignment
* All Autocomplete
* BracketHighlighter
* CodeFormatter
* Color Highlighter
* ColorPicker
* CTags
* DocBlockr
* HTML-CSS-JS Prettify
* Pretty JSON
* SublimeAStyleFormatter
* TrailingSpaces

### Language-Spec
#### HTML
* Emmet

### C/C++
* C Improved
* CMake
* CMakeBuilder

#### Java
* JavaIME

#### LaTex
* LaTex-cwl
* LaTeXTools
* LaTeXYZ

#### Markdown
* MarkdownEditing
* MarkdownLivePreview
* MarkdownPreview
* OmniMarkupPreviewer
* Table Editor

#### Python
* Anaconda
* SublimeCodeIntel
* SublimeREPL

#### R
* R-Box

#### SublimeLinter
* SublimeLinter
* SublimeLinter-contrib-htmlhint
* SublimeLinter-csslint
* SublimeLinter-jshint

#### VBScript
* VBScript

#### Wechat Mini Program
* wxapp
