<!-- CSS -->

<!-- 
Cascading Style Sheet makeup
It is a language that is used to describe the style of a document. -->

<!-- Basic Syntax
Selector (h1)
h1 {
color: red; //Property :Value
}
 -->

 # Including Style
 1. Inline
   <h1 style="color: red">

 2. <style> tag
   <style>
        h1 {
        color : red;
        }
    </style>

# External Stylesheet
 Writing CSS in a separate document & linking it with HTML file


# Color Property
 Used to set the color of foreground
 color:  red;

# Background Color Property
 Used to set the color of background
 background-color:  red;

 # Color Systems
 # RGB 
   - color: rgb(255,0,0)
   - color: rgb(0,255,0)
   - color: rgb(0,0,255)
   - color: rgb(0,255,255)

 # HEX (00 - ff)
   - color : #ff0000
   - color : #00ff00
   - color : #0000ff
   - color : #ffff00

 # Selectors

 - Universal Selector
   * { }

 - Element Selector
    h1 { }

 - Id Selector
    #myId {}

 - Class Selector
    .myClass { }

 # Text Property
   -  text-align : start (left) / end (right) / center 
   -  text-decoration : underline / overline / line-through
   -  font-weight : normal / bold / bolder / lighter
      font-weight : 100-900
   -  font-family : arial 
      font-family : arial, roboto

        <!-- A generic family name only 
        font-family: serif;
        font-family: sans-serif;
        font-family: monospace;
        font-family: cursive;
        font-family: fantasy;
        font-family: system-ui;
        font-family: ui-serif;
        font-family: ui-sans-serif;
        font-family: ui-monospace;
        font-family: ui-rounded;
        font-family: emoji;
        font-family: math;
        font-family: fangsong; -->

    # Units in CSS
        - Absolute
            - pixels (px)
                96px = 1 inch = 2.54cm
                font-size: 2px   
    - line-height (distance between lines)
      line-height : 2px
      line-height : 3
      line-height : normal

    - text-tranform : uppercase / lowercase / capitalize / none                  

 
  