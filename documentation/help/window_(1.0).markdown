---
layout: page
title: "Help: window (1.0)"
---

{% comment %}

Please submit changes to
- https://github.com/irssi/irssi/blob/master/docs/help/in/window.in
- https://github.com/irssi/irssi/blob/master/src/fe-common/core/fe-log.c
- https://github.com/irssi/irssi/blob/master/src/fe-common/core/window-commands.c
- https://github.com/irssi/irssi/blob/master/src/fe-text/mainwindows.c


{% endcomment %}
<nav markdown="1">
[Help index](/documentation/help/index_(1.0))
</nav>

<nav markdown="1">
[ v1.0 ] - [ [v1.1](/documentation/help/window) ] - [ [v1.2](/documentation/help/window_(1.2)) ]
</nav>

### Subcommands


#### [window/split window creation](/documentation/help/window_creation)

<div markdown="1" class="helpindex">

* window new 
* window close 
* window list 
* window hide 
* window show 

</div>

#### [window changing](/documentation/help/window_changing)

<div markdown="1" class="helpindex">

* window refnum 
* window goto 
* window next 
* window last 
* window previous 
* window left 
* window right 

</div>

#### [window attribute manipulation](/documentation/help/window_properties_(1.0))

<div markdown="1" class="helpindex">

* window level 
* window immortal 
* window server 
* window number 
* window name 
* window history 
* window theme 
* window stick 

</div>

#### [window items](/documentation/help/window_items)

<div markdown="1" class="helpindex">

* window item prev 
* window item next 
* window item goto 
* window item move 

</div>

#### [window moving/number changing](/documentation/help/window_moving)

<div markdown="1" class="helpindex">

* window number 
* window move prev 
* window move next 
* window move first 
* window move last 
* window move 
* window move left 
* window move right 

</div>

#### [split window resizing](/documentation/help/window_resizing)

<div markdown="1" class="helpindex">

* window grow 
* window shrink 
* window size 
* window balance 

</div>

#### [split window navigation](/documentation/help/window_navigation)

<div markdown="1" class="helpindex">

* window up 
* window down 

</div>

#### [split window moving](/documentation/help/window_split_moving)

<div markdown="1" class="helpindex">

* window stick 
* window move up 
* window move down 

</div>

#### [logging](/documentation/help/window_logging)

<div markdown="1" class="helpindex">

* window log 
* window logfile 

</div>



### Parameters ###


   Add the required arguments for the given command. Without arguments, the details (size, immortality, levels, server, name and sticky group) of the currently active window are displayed. If used with a number as argument, same as WINDOW REFNUM.

### Description ###

Manipulates the window layout and positioning attributes.

### Examples ###

    /WINDOW CLOSE
    /WINDOW ITEM MOVE 10
    /WINDOW GOTO 15
    /WINDOW GOTO ACTIVE
    /WINDOW GOTO mike
    /WINDOW GOTO #irssi
    /WINDOW NEW HIDDEN
    /WINDOW LOG OFF
    /WINDOW LOG ON ~/logs/debug.log
    /WINDOW LEVEL -ALL +NOTICES
    /WINDOW LOGFILE ~/logs/notices.log

### See also ###
[JOIN](/documentation/help/join), [LEVELS](/documentation/help/levels), [LOG](/documentation/help/log), [QUERY](/documentation/help/query)

