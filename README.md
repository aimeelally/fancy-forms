# fancy-forms

>Fancy Forms is a pure SCSS library of fully accessible native form elements.<br/>
Head to [aimeelally.com/fancy-forms](www.aimeelally.com/fancy-forms/index.html) to see examples of each element.<br/>

Native form elements are sometimes limited in their styling capabilities (I'm looking at you select boxes!). I have come across instances where some major companies have even tried to mock the behaviour of a select box using javascript instead of using the native element. This creates a whole host of issues. 

### Accessibility
Screenreaders need native form elements to work correctly. If you care at all about accessibility, use them.

### Keyboard shortcuts
There are built-in keyboard shortcuts for native form elements e.g. press the space key or down arrow to open a select box. Unless you intend to spend a huge amount of time rebuilding all of these, it's just not worth it.

### Default browser behaviour
Your browser automatically knows what to do with `<select></select>`. It does not on the other hand know what to do with `<div class="select"></div>`. 

>To combat this I set out to show why you do not have to (badly) reinvent the wheel to achieve the beautiful form elements you are striving for.

## HOW TO USE
- Copy the code below into whatever file you use to compile your SASS e.g. base.scss.
- Change the variables to modify the colours to fit your own brand.

`@import '~fancy-forms/styles/fancy-forms/base';  
$ff-color-initial-state: grey;
$ff-color-primary: blue;
$ff-color-bg: white;
$ff-color-answer-correct: green;
$ff-color-answer-incorrect: red;
`

## ACCESSIBILITY AND COLOUR BLINDNESS
Use the variables `$ff-color-answer-correct` and `$ff-color-answer-incorrect` to utilise this module in question players where **correct** and **incorrect** classes are applied to form elements. See [aimeelally.com/fancy-forms](www.aimeelally.com/fancy-forms/index.html) for examples.

>**ff-color-answer-incorrect** puts a line beneath form elements with the **incorrect** class. The most common type of colour blindness is red/green, which also happen to be the most common colours to indicate correct and incorrect states. The extra line beneath incorrect elements makes them accessible for anyone suffering from colour blindness.

## VARIABLE VALUES
**ff-color-initial-state** is the colour the elements take when no state is applied.</br>
**ff-color-primary** is the primary colour. This is the colour you will see when you hover any of the form elements.</br>
**ff-color-bg** is the background colour of each of the elements.</br>
**ff-color-answer-correct** is the colour you will see when a state is applied to 'correct-answer' form elements.</br>
**ff-color-answer-incorrect** is the colour you will see when a state is applied to 'incorrect-answer' form elements.</br>

## FANCY FORM ELEMENTS
- input boxes
- checkboxes
- radio buttons
- select boxes
- radio buttons with images
- checkboxes with images
- fancy labels using radio buttons
- fancy labels using checkboxes