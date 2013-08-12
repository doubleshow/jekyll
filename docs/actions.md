---
layout: docs
title: Actions
prev_section: usage
next_section: usage
permalink: /docs/actions/
---

This page gives a comprehensive overview of all the actions supported by Sikuli Slides.

## Click

Execute a mouse left click action on a target. To define a click action,  write the word `click` in a text box and draw a rectangle around the target. The word is *not* case sensitive. You can style the text box and the rectangle using any font, color, or line width.

<img src="/img/click1.jpg" class="one-third img-polaroid">
<img src="/img/click2.jpg" class="one-third img-polaroid">
<img src="/img/click3.jpg" class="one-third img-polaroid">

---

## Right Click

Execute a mouse right click action on a target. To define a right-click action, write the word `right click` in a text box. You can also write aliases such as `right-click` or `rightclick`. Then, draw a rectangle around the target.

<img src="/img/rightclick1.jpg" class="one-third img-polaroid">
<img src="/img/rightclick2.jpg" class="one-third img-polaroid">
<img src="/img/rightclick3.jpg" class="one-third img-polaroid">

---

## Double Click

Execute a mouse double click action on a target. To define a double-click action, write the word `double click` in a text box. You can also write aliases including `double-click` or `doubleclick`. Then, draw a rectangle around the target.

<img src="/img/doubleclick1.jpg" class="one-third img-polaroid">
<img src="/img/doubleclick2.jpg" class="one-third img-polaroid">
<img src="/img/doubleclick3.jpg" class="one-third img-polaroid">

---

## Type

Type a string in a target. To define a type action, write the word `type` in a text box. In the same text box, write the string that should be typed after the word *type*. Then, draw a rectangle around the input target. Another way to specify what string to type is to write it in the target rectangle, like the third example below.

<img src="/img/type1.jpg" class="one-third img-polaroid">
<img src="/img/type2.jpg" class="one-third img-polaroid">
<img src="/img/type3.jpg" class="one-third img-polaroid">

---

## Drag and Drop

Drag a target and drop it onto another destination target. To define a drag and drop action, create two slides. On the first slide, write the word `drag` in a text box, insert a screenshot, and draw a rectangle around the target to drag. On the second slide, write the word `drop` in a text box, insert a screenshot, and draw a rectangle around the destination target.

<img src="/img/dragdrop1.jpg" class="one-third img-polaroid">
<img src="/img/dragdrop2.jpg" class="one-third img-polaroid">
	
---

## Caption		

Display caption text on the screen. To define a caption action, write the caption text in a text box. In the absence of other action words such as click or type, this text box will be interpreted as a caption. 

 * **Styling** You can specify the style of the text box using any font size, color, and background. Sikuli Slides will try to render the caption following the style you've specified as closely as possible.

 * **Positioning** If no screenshot of a GUI is on the slide (first example below), the caption is positioned in the center of the screen. If a screenshot of a GUI is on the slide, the caption is positioned in the same relative location to the GUI. For instance (third example below), suppose a caption *HERE* is placed above an OK button on the slide. When the slide is executed, the OK button will first be identified on the screen and the caption will be shown in the same relative position above the OK button.

<img src="/img/caption1.jpg" class="one-third img-polaroid">
<img src="/img/caption2.jpg" class="one-third img-polaroid">
<img src="/img/caption3.jpg" class="one-third img-polaroid">

---

## Browser 
	
Open a web page in the default web browser. To define a browser action, write the word `Browser` in a text box followed by an URL. Alternatively, the URL can be written in a separate text box.

<img src="/img/browser1.jpg" class="one-third img-polaroid">

---

## Delay

Delay the execution by some amount of time. To define a delay action, write the word `Delay`, `Sleep`, or `Pause` in a text box followed by the amount and time unit. The time unit can be in milliseconds, seconds, minutes, or hours. If no unit is given explicitly, it is default to seconds.

<img src="/img/delay1.jpg" class="one-third img-polaroid">
<img src="/img/delay2.jpg" class="one-third img-polaroid">
<img src="/img/delay3.jpg" class="one-third img-polaroid">

---


## Exist

Check if a target exists. If the target *cannot* be found, slides execution is aborted. It can be used to test if the right picture or message is shown after a certain event (e.g., clicking a tab).

<img src="/img/exist1.jpg" class="one-third img-polaroid">
<img src="/img/exist2.jpg" class="one-third img-polaroid">
<img src="/img/exist3.jpg" class="one-third img-polaroid">

---
	
## Not Exist

Check if a target does not exist. If the target *can* be found, slides execution is aborted. It can be used to check if contents that are supposed to disappear after a certain event (e.g., clicking another tab) indeed becomes invisible

<img src="/img/notexist1.jpg" class="one-third img-polaroid">
<img src="/img/notexist2.jpg" class="one-third img-polaroid">
<img src="/img/notexist3.jpg" class="one-third img-polaroid">
