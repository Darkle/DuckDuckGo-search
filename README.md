DuckDuckGo Search
=============

Search DuckDuckGo for the currently selected text/word, or an input in Sublime Text 2/3.

This package adds: 

* A `DuckDuckGo Search` command to the context menu for the selected 
* A pallete command for the current selection(or word)
* A pallete command that will ask you what to search

## Install

Go to your Sublime packages directory(Sublime Text/Packages) Then run this command `git clone https://github.com/Darkle/DuckDuckGo-search.git`.

## Settings
```js
{
    "suffix": "", // will be after the query
    "prefix": "", // will be added before the query
    "default_browser": "", // chrome, firefox, more valid values here https://docs.python.org/2/library/webbrowser.html#webbrowser.register
    "domain": "https://duckduckgo.com" // duckduckgo domain to perform the search
}
```
You can edit the settings by going to Preferences -> Package Settings -> DuckDuckGo Search -> Settings - User

## Usage

Place the cursor inside a word or select some text and press `Ctrl+Shift+G`.

Context Menu
![context menu][4]

Command Pallette

![pallete][5]

![pallete][6]

  [1]: http://www.sublimetext.com
  [2]: https://sublime.wbond.net/
  [3]: https://github.com/nwjlyons/google-search/archive/master.zip
  [4]: http://i.stack.imgur.com/MJMC1.png
  [5]: http://puu.sh/9DyUy/b89bbcd3ce.png
  [6]: http://puu.sh/9Dz30/cd502986cd.png
