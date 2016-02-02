
# ST_SublimeSlides

Easily create slide presentations in Sublime Text with SublimeSlides

Also includes a customizable file launcher

## FEATURES

### Slides

* Divide your document with Slides
* Navigate through the document slide by slide ( any content not in the current slide is folded )

![SlideDemo](http://i.imgur.com/q02FrPm.gif?1)

### MediaLink

* Launch files during your presentation with MediaLinks
* MediaLinks can be launched automatically upon clicking, or with a hotkey
* List your MediaLink+Path at the beginning of the document, and access it anywhere else in the document
* Define applications & extensions @ SublimeSlides.sublime-settings

![MediaLinkDemo](http://i.imgur.com/0UxRYbf.gif?1)

### Snippets

* Slide dividers & MediaLinks are generated automatically via hotkey
* MediaLinks can be generated with or without path ( use with path to define MediaLink, use without path to launch MediaLink anywhere else in the document )

![SnippetDemo](http://i.imgur.com/RUvj93C.gif?1)

## USAGE

These are the included commands & default keybindings:

### Navigation

Zoom  ( zoom to selected Slide - Slide title line must be selected )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>equals</kbd>

NavigateDown ( show next Slide - automatically shows first slide on first use )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>equals</kbd>

NavigateUp ( show previous Slide - automatically shows first slide on first use )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>minus</kbd>

Reset ( exit Slide & show full document )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>minus</kbd>

### Snippets

Insert_Title ( insert Slide divider )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

Insert_MediaFile ( insert MediaLink + path )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>super</kbd>+<kbd>period</kbd>

Insert_MediaLink ( insert MediaLink + wrapper )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>period</kbd>

### MediaLink

Open_MediaLink  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>o</kbd>

Toggle_MediaLink ( enable/disable automatically opening MediaLinks on click )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

### Slide Titles

Collapse ( remove endcaps from Slide titles for easy editing )  
<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

Build ( restore endcaps to Slide titles )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>period</kbd>
