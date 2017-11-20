# Turing Prework

## DAY 1

### Chapters 1 and 2
1.  HTML code describes the structure of a document using different elements.
2.  Elements are used to specify attributes of parts of a document.  Tags are used to indicate the beginning and end of an element.
3.  Attributes are used to provide additional information about an element such as height and width, CSS style, or the URL for a hyperlink.
4.  HEAD: Contains information about the page, such as the title.

    TITLE: Defines the title of the page to be displayed in thew browser toolbar, favorites, and search engine results.
    
    BODY: Contains all the contents of a page to be displayed in a browser.
5.  From the View pull-down menu, go to Developer and select View Source.  Alternatively, you can use the following keyboard shortcut: option-control-U.
6.  Five different elements:
    * `<h1></h1>` is a level 1 heading element and is used for main headings.
    * `<b></b>` is a bolded element and is used to make characters appear bold.
    * `<hr />` is a horizontal rule and it displays a horizontal line at the specified part of a page.
    * `<em></em>` is an emphasis element.  It indicates emphasis that subtly changes the meaning of a sentence and is shown in italic.
    * `<abbr></abbr>` is an abbreviation element.  It is used to specify the full term of an abbreviation or acronym using a title attribute in the opening tag.
7.  Empty elements are elements that do not have any words between an opening and closing tag.  They usually contain only one tag.
8.  Semantic markup is elements that add extra information to text such as emphasis or block quotes.
9.  `<header>`, `<nav>`, and `<article>` are three new elements introduced in HTML5.

Link to my pen:  https://codepen.io/mngatewood/pen/WXdjqQ

## DAY 2

### Chapters 3 and 4
1.  Ordered lists are numbered lists, while unordered lists are bulleted.  Definition lists do not have numbers or bullets, but contain an additional row of characters referred to as a definition.
2.  The basic structure of an element used to link to another website is: 

    `<a href="https://www.website.com>Website</a>`.

3.  You should include the target="blank" attribute to open a link in a new window.
4.  To link to a specific part of a page, first insert an id attribute inside the opening tag of the element where you would like the page loaded.  Secondly, add the name of the id given--preceded by a #--at the end of the URL.

### Chapters 10-12
1.  The purpose of CSS is to specify how different elements are displayed.
2.  CSS stands for Cascading Style Sheets.  In this case, cascading refers to how rules fall from broad/general down to more specific rules.
3.  The basic structure of a CSS rule is: `p {property: value;}`.
4.  You link a CSS stylesheet to your HTML document by entering a <link> element inside the <head> element to indicate where the style sheet file is located.
5.  It useful to use external stylesheets because you can link multiple pages to a single CSS file, rather than creating unique CSS rules for each individual page.
6.  Color hex codes are six-digit codes preceded by a #.  The values represent the amount of red, green, and blue in a given color.
7.  The three parts of an HSL color property are hue, saturation, and lightness.
8.  The three main categories of fonts are:
    * Serif.  Serif fonts have extra details at the end of each stroke of the character.
    * Sans-Serif.  Sans-serif fonts have straight ends.
    * Monospace.  Monospace characters all have the same width.
9.  The main three units used for specifying font size are pixels, percentages, and ems.

## DAY 3

### Chapter 7
1.  The `type` attribute controls the behavior of an input element.
2.  The `<select>` element is used to create a drop-down box.
3.  The `type` attribute should be set to "submit" in order to send form data to a server.
4.  The `<fieldset>` element is used to group similar form items together.

### Chapters 13 and 15
1.  The border is the box that surrounds an element.  It separates the margin (space immediately outside the border) from the padding (space between the border and the element's content).
2.  For a CSS rule padding: 1px 2px 5px 10px; the top padding is 1 pixel, the right padding is 2 pixels, the bottom padding is 5 pixels and the left padding is 10 pixels.
3.  Block-level elements will always begin on a new line while inline elements sit within block-level elements and do not start a new line.
4.  Because fixed positioning is relative to the screen and not the rest of the page, it remains in the same position on the screen regardless of which part of the page you are viewing.  Z-index is important because in the case of overlap, it specifies which element is visible and which is covered by the other element.
5.  Fixed width content remains the same size (indicated in pixels), regardless of the size of the browser window.  Liquid layout content stretches and compacts as the browser window changes size.  Percentages are used in liquid layouts.

## DAY 4

### Chapter 5
1.  The alt attribute is important because it provides a description of the image in the event that the image cannot be displayed.
2.  Where you place the image in your code determines whether it is displayed block-level or inline.  If the image is inside a block-level parent element, it will be displayed as block-level.  If it is in an inline element, it will be displayed inline.
3.  The jpg format is suitable for images with many colors, while png is better suited for images with fewer colors.

### Chapter 16
1.  Specifying the image size in CSS allows the browser to render the rest of the page without waiting for the image to download.  It also facilitates consistent image sizes by defining the properties for all images in CSS.
2.  An image sprite is when a single image is used for several different parts of an interface.  The advantage of using sprites is that the web browser only needs to request one image rather than many images, which can make the web page load faster.

## DAY 5

### Chapters 1 and 2
1.  In JavaScript, number data types are numbers, strings are text, and booleans are true/false values.
2.  And, or, and not are the three logical operators that JavaScript supports.
3.  Variables can be any word that is not a reserved word.  They can contain numbers, but cannot begin with a number.  They cannot contain punctionation other than $ and _.
4.  An expression is code that results in a value.  A statement is a series of expressions.
5.  Var, true, and false are three examples of JavaScript reserved words.  It is important to not use these words as variable names because JavaScript will attempt to execute them in the manner for which they were reserved, not as a named variable.
6.  Control flow is the order in which statements and expressions are executed by JavaScript.  Control flow is useful in programming because it makes a program more predictable.

### Google Console
1.  You could change the expression `5 > 3` to return a value of false by changing the operator to <.
2.  `"2" === 2` returns a value of false because the operator prevents the console from converting the string to a number.
3.  
````
    if (10 == "ten")
      {console.log("Console converted the string ten to a number.")}
    else
      {console.log("Console did not convert the string ten to a number.")};
````
      
### Variable Exercises
1.  var childrenNum = 2, spouseName = "Juana", residenceCity = "Broomfield", jobTitle = "Student";
    {console.log("You will be a " + jobTitle + " living in " + residenceCity + " and married to " + spouseName + " with " + childrenNum + " kids.")};
2.  var yearCurrent = 2017, yearBirth = 1975, ageOptOne = yearCurrent - yearBirth, ageOptTwo = ageOptOne - 1;
    {console.log("You are either " + ageOptOne + " or " + ageOptTwo + ".")};
3.  var ageCurrent = 42, ageMax = 99, vapeMilsPerDay = 5, daysUntilBDay = 48, vapeMilsTotal = (((ageMax - ageCurrent - 1) * 365.25) + daysUntilBDay) * vapeMilsPerDay;
    {console.log("You will vape approximately " + vapeMilsTotal + " milligrams of eJuice until the ripe age of " + ageMax + ".")};

### Eloquent JavaScript Practice
1.  for (var x = "x"; counter = x.length <= 7; x = x + "x")
    console.log(x);
2.  var number = 0;
    var counter = 0;

    while (counter < 100) 

    if (number % 3 == 0 && number % 5 == 0) {
      number ++;
      counter ++;
      console.log("FizzBuzz");
    }
    else if (number % 3 == 0) {
      number ++;
      counter ++;
      console.log("Fizz");
    }
    else if (number % 5 == 0) {
      number ++;
      counter ++;
      console.log("Buzz");
    }
    else {
      number ++;
      counter ++;
      console.log(number);
    }
3.  var length = 1;
    var height = 1;
    var grid = ""

    while (height <=8) {

      while (length <=8)
            if (length % 2 == 0) {
              grid = grid + "#";
              length ++;
            }
            else {
              grid = grid + " ";
              length ++ ;
            }
            console.log(grid);
            length = 1;
            grid = "";
            height ++;

      while (length <=8)
          if (length % 2 == 0) {
            grid = grid + " ";
            length ++;
          }
          else {
            grid = grid + "#";
            length ++;
          }
            console.log(grid)
            length = 1;
            grid = "";
            height ++;
    }

DAY 6

Chapter 3
1.  Entering SayHello in the console returns the function, while entereing SayHello() returns the result of the function.
2.  The keyword return is used to determine the value the function returns.
3.  Parameters are values that are specified by the caller of the function.
4.  The naming convention for functions is the same as for variables.

Function Exercises
1.  function tellFortune(childrenNum, spouseName, residenceCity, jobTitle) {
    var fortune = "You will be a " + jobTitle + " living in " + residenceCity + " and married to " + spouseName + " with " + childrenNum + " kids.";
    console.log(fortune);
}
2.  function calculateAge(yearCurrent, yearBirth) {
    var ageOptOne = yearCurrent - yearBirth;
    var ageOptTwo = ageOptOne - 1;
    {console.log("You are either " + ageOptOne + " or " + ageOptTwo + ".")};
    }
3.  function calculateSupply(ageCurrent, ageMax, daysUntilBDay, vapeMilsPerDay) {
    var vapeMilsTotal = (((ageMax - ageCurrent - 1) * 365.25) + daysUntilBDay) * vapeMilsPerDay;
    {console.log("You will vape approximately " + vapeMilsTotal + " milligrams of eJuice until the ripe age of " + ageMax + ".")};
    }

Eloquent JavaScript Exercises
1.  function min(a, b) {
      if (a < b)
        return a;
      else
        return b;
    }
2.  function isEven(n) {
    if (n == 0)
      return true;
    else if (n == 1)
      return false;
    else if (n > 1)
      return isEven(n - 2);
    else if (n < 0)
      return isEven(-n);
    else
      return "Not a number.";
    }
3.  function countChar(string, ch) {
      var counted = 0;
      for (var i = 0; i < string.length; i++)
        if (string.charAt(i) == ch)
          counted += 1;
      return counted;
    }

    function countBs(string) {
      return countChar(string, "B");
    }
//I cheated on #3.

DAY 7

Five Main Ingredients of UX
1.  Psychology: How does this make them feel?
    Good: 4rsmokehouse.com
    Bad: art.yale.edu
    The former website makes me crave a steak dinner and a night out, while the latter gives me anxiety and makes me question the credibility of this "art" school.
2.  Usability: Is it easy to find (good), hard to miss (better), or subconsciously expected (best)?
    Good: facebook.com
    Bad: arngren.net
    Facebook makes good use the most frequently used navigation tools at the top of the page and they are intuitive.  The latter is so cluttered that the index, search tool, and contact information (all in different parts of the page) get lost in the chaos.
3.  Design: Does it communicate the purpose and function without words?
    Good: us.polaroidoriginals.com
    Bad: alfredsung.com
    The purpose of the polaroid website is immediately clear and further supported by its navigation tools.  The latter tries to use images in a similar manner, but they are so unrelated that it fails to convey a clear message.  Navigation on this site is not as clear as it could be.
4.  Copyright: Does it reduce anxiety?
    Good: apple.com
    Bad: jamilin.com
    Apple uses short statements that are compelling and straight-forward.  Navigation text is also short and simple.  Text in the latter page is unorganized, verbose, and unfocused.
5.  Analysis:  How can you use this analysis to make improvements?
    Good: ahrefs.com
    Bad: theroommovie.com
    This question is diffucult to answer without assumptions.  So the assumption is that the first site's product is analytics, so they must be efficient with analysis of their own site.  The next assumption is that if the second site used any type of analytics, they would invest the time to build some navigation tools and place some of the less popular content in separate pages. 
