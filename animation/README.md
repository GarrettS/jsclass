#CSS Transition Homework:

##Warmup
Modify the example transition, index-no-js.html, to use three transition timing properties, each at a different duration, and with a different timing function.

##Assignment
Create either an animated, toggleable menu or a toggleable split pane.

Complete the HTML and CSS before adding any JavaScript.

###Animated menu
Create an animated menu list that slides out from the left side of the document. Use an unordered list. Use the w3c HTML4 reference (google: html4 unordered list ul) (and do not use any W3Schools).

```
++
||
||
||
||
||
++
[toggle menu]
```
####Transition state:

```
+-------+
|m 1    |
|m 2    |
|m 3    | 
|m 4    |
|t item |
+-------+
```
###Expanded state:

```
+-----------+
| item 1    |
| item 2    |
| item 3    | 
| item 4    |
| last item |
+-----------+
[toggle menu]
```

###Content
A list of five items 1...4 with another item having longer text and whitespace (e.g. "last item")

###Appearance
List has 8px padding on each side. list items have padding top and bottom of 2px to 4px each.

###Behavior
List is shown by clicking a button.

####Show/hide transition:

Two properties of your choosing are animated on the list's show/hide action. Each property animation has a different duration and a different timing.


###Split Pane
 Split Pane

For this assignment, you'll create a layout with a list on the left hand side. 

###Expanded view:

```
[Collapse]
+------------+-----------------------------+
|.Item 1 . . |         Contents            |
| Item 2  . .|                             |
|.Item 3 . . |                             |
| Item 4  . .|                             |
|. . . . . . |                             |
| . . . . . .|                             |
+------------+-----------------------------+
```
###Collapsed view:

```
[Expand]
++-----------------------------------------+
||                 Contents                |
||                                         |
||                                         |
||                                         |
||                                         |
||                                         |
++-----------------------------------------+
```

##Content
A split pane with list in the left side and the text "Contents", cenetered in the content pane. 

A button toggles the state of the split pane.

##Appearance
List has 8px padding on each side.

##Behavior
Left side pane collapses using 

###Show/hide transition:

Two properties of your choosing are animated on the list's show/hide action. Each property animation has a different duration and a different timing.