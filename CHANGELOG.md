# Change Log
## 1.1.0 - 2021 July 17
### Theme Changes
### **PREVIEW: Office Dark Theme (Word) is out!**
([#7](https://github.com/huacat1017/huacat.office-theme/pull/7))
Thanks ([YazeedAlKhalaf](https://github.com/YazeedAlKhalaf)) for support.
#### Activity Bar Changes
Because I'm using Office 2019 now, so I'll modify a few colors:
- `activityBar.foreground`<br>
`activityBar.inactiveForeground` : `#f3f3f3` -> `#ededed`
`activityBarBadge.background`
- Added `activityBar.dropBorder` -> `#ffffff`
## 1.0.2 - 2020 July 19
### Theme Changes
([#4](https://github.com/huacat1017/huacat.office-theme/pull/4))
- `minimap.background` sat color to `#fafafa`
- `panel.background` sat color to `#f3f3f3`
- `terminal.background` sat color to `#fafafa`
- `terminalCursor.background` sat color to `#fafafa`
- exchange terminal ansi colors and ansi bright colors (Not #4)

## 1.0.1 - 2020 June 26
### Fixed issues
- Published extension to [open-vsx.org](https://open-vsx.org) ([#1](https://github.com/huacat1017/huacat.office-theme/issues/1))
- README.md improved readability ([#2](https://github.com/huacat1017/huacat.office-theme/pull/2))

### Theme Changes
- `editor.lineHighlightBackground` and `editor.lineHighlightBorder` recolored to `#f3f3f3`
- `editor.hoverHighlightBackground`,`editor.selectionHighlightBackground`, and `editor.wordHighlightStrongBackground`
set opacity to `a0` (It could cover something before) 

## 1.0.0 - 2020 June 22
### HUGE UPDATE \! Added the other 4 themes \!
\- Excel, Onenote, Access and Publisher

### Theme Colors
- Fixed `list.highlightForeground` was still blue in PowerPoint Theme
- `list.activeSelectionForeground` and `list.inactiveSelectionForeground` changed to Theme's titlebar background color
- The color of `textLink` changed to Theme's titlebar  background color
- Office Theme (Powerpoint) was ranamed to Office Theme (PowerPoint)
- `editor.hoverHighlightBackground` and `editor.selectionHighlightBackground` set opacity to `ff` (Microsoft fixed the bug in terminal at 0.46)

### Syntax Colors
- Added `punctuation.definition.string.end.cpp` and `punctuation.definition.string.begin.cpp`
to `Punctuation` group

## 0.1.1 - 2020 June 6
- `editor.hoverHighlightBackground` and `editor.selectionHighlightBackground` set opacity to `80`
- Fix README.md Powerpoint label position.

- Added color to following theme keys:
`editor.wordHighlightBackground`
`editor.wordHighlightStrongBackground`
`list.highlightForeground`

## 0.1.0 - 2020 May 18
- **Powerpoint Theme is out\!**

### Theme Colors
- No opacity in `editorGroup.dropBackground`
- `textLink.activeForeground` changes color to `#4472c4`
- Added `notification` settings
- Changed `progressBar.background` to themes' titlebar color

### Syntax Colors
- Changes some `punctuation` settings
- `CSS Classes` changes color to `#a8d08d`
- `CSS: Property Names` changes color to `#70ad47`

### Package structure changes
- All of the images (except logo.png) are moved to image folder and delete from extension (they are at github)

## 0.0.1 - 2020 May 3
- Initial release