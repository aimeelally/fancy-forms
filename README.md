# fancy-forms

Fancy Forms is a pure SCSS library of fully accessible native form elements.<br/>
Go to www.aimeelally.com/fancy-forms/index.html to see examples of each element.<br/>

Native form elements are sometimes limited in their styling capabilities (I'm looking at you select boxes!). I have come across instances where some major companies have even tried to mock the behaviour of a select box using javascript instead of using the native element. This creates a whole host of issues: 

1. Accessibility
Screenreaders need native form elements. If you care at all about accessibility, use them.

2. Keyboard shortcuts
There are built-in keyboard shortcuts for native form elements e.g. press the space key or down arrow to open a select box.

3. Default browser behaviour
Your browser automatically knows what to do with <select></select>. It does not on the other hand know what to do with <div class="select"></div>. 

To combat this I set out to show why you do not have to (badly) reinvent the wheel to achieve the beautiful form elements you are striving for.

## HOW TO USE
- copy the variables and imports below into whatever file you use to compile your SASS e.g. base.scss.
- To modify the colours, change the variables.

@import '~fancy-forms/styles/fancy-forms/base';<br/>
$ff-color-primary: #F90093;<br/>
$ff-color-answer-correct: #70C1B3;<br/>
$ff-color-answer-incorrect: #ff6666;<br/>
$ff-color-bg: #ffffff;<br/>
$ff-color-initial-state: #a1a1a1;<br/>

## FANCY FORM ELEMENTS
- input boxes
- checkboxes
- radio buttons
- select boxes
- radio buttons with images
- checkboxes with images
- fancy labels using radio buttons
- fancy labels using checkboxes