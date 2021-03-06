# Chrome extension for miscellaneous keyboard command driven functions.

![Demo gif](https://github.com/ThePaavero/ff/blob/master/demo-gif.gif)

## Install
1. Download or clone this extension onto your computer
2. Go to `chrome://extensions`
3. Turn on "Developer mode" in the upper right corner
4. Click "Load unpacked"
5. Paste the path to this extension (or navigate to it via the GUI)

## Usage
* Doubletap `f` on your keyboard to open up the prompt bar.
* Start typing for searching.
* Start your command with a `:` to use CSS selectors instead of text search.
* Start your command with a `>` to enter "commands", more on that below.
* Tab your way to the one element you want to click -> Press enter to click the selected element.
* Alternatively, type the corresponding match number to click the element instantly.

## Commands
Start your string with `>` and enter a command.

#### Available commands
- `show-classes` (this is just a test for creating "commands" for now)
- `css` Toggle all CSS imported via `<link>`
- `stfu` Mute all `video` and `audio` elements

## Todos
- [x] Don't block normal use of PgUp and pgDown to scroll the site
- [x] Automatically scroll to matching element that has current "tab index"
- [x] Come up with "commands"
- [x] Directly typing indexes to click has some issues (especially with zeros) 
