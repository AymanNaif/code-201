# Basics of HTML, CSS & JS

## HTML (Chapter 2: TEXT)
### Heading
![Heading](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQU46NNp2hk-fxbKgiYpDkPTUUgh_50fbZ2hA&usqp=CAU)
#### HTML has six level of heading start from h1 untel h6,the browsers display the contents of headings at different sizes. The contents of an <h1> element is the largest, and the contents of an <h6> element is the smallest.The exact size at which each browser shows the headings can vary slightly.
#### *note* : h1 is used for main headings h2 is used for subheadings.

### Paragraphs
#### To create a paragraph, surround the words that make up the paragraph with an opening < p > tag and closing < /p > tag.

### Bold & Italic
#### By enclosing words in the tags < b > and < /b > we can make characters appear bold.
#### By enclosing words in the tags < i > and < /i > we can make characters appear italic.

### Superscript & Subscript
#### The < sup > element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 2<sup>2</sup>.
#### The < sub > element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H<sub>2</sub>O.

#### *note* :When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing.

### Line Breaks & orizontal Rules 
#### the browser will automatically show ach new paragraph or heading n a new line. But if you wanted o add a line break inside themiddle of a paragraph you can se the line break tag <br />.
#### To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the <hr /> tag.

### Strong & Emphasis
#### The use of the < strong >  element indicates that its content has strong importance.
#### The < em > element indicates emphasis that subtly changes the meaning of a sentence.

### Quotations
#### The <blockquote > element is used for longer quotes that take up an entire paragraph. Note how the <p> element is still used inside the <blockquote> element.
#### The <q > element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the <q > element, however Internet Explorer does not — therefore many people avoid using the <q >  element.

### Abbereviations & Acronyms
#### If you use an abbreviation or an acronym, then the <abbr > element can be used. A title attribute on the opening tag is used to specify the full term.

### Citations & Definitions
#### When you are referencing a piece of work such as a book, film or research paper, the <cite > element can be used to indicate where the citation is from.
#### The <dfn > element is used to indicate the defining instance of a new term.

### Author Details
#### The <address > element has quite a specific use: to contain contact details for the author of the page. It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address.

### Changes to Content
#### The < lns > element can be used to show content that has been inserted into a document, while the < del > element can show text that has been deleted from it.
#### The < s > element indicates something that is no longer accurate or relevant (but that should not be deleted). Visually the content of an < s > element will usually be displayed with a line through the center.

## CSS (chapter 10:INTRODUCING CSS)
### Understanding CSS: Thinking Inside the Box
#### The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
#### *note* : CSS works by associating rules with HTML elements. These rules govern ow the content of specified elements should be displayed. A CSS rule ontains two parts: a selector and a declaration. > the Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

#### *note* : CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon. > Properties indicate the aspects of the element you want to change. For example, color, font, width, height and border, Values specify the settings you want to use for the chosen properties. For example, if you want to specify a color property then the value is the color you want the text in these elements to be.

### Using External CSS
![external](https://codebridgeplus.com/wp-content/uploads/download-5.png)

#### The < link >  element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes 
- #### href This specifies the path to the CSS file (which is often placed in a folder called css or styles).
- #### type This attribute specifies the type of document being linked to. The value should be text/css.
- #### rel This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

### Using Internal CSS
#### < style > You can also include CSS rules within an HTML page by placing them inside a < style > element, which usually sits inside the < head > element of the page. The < style > element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.

### CSS Selectors
#### There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. 
![selector](https://i1.wp.com/learn-automation.com/wp-content/uploads/2015/12/Css-Selector-Table.png?resize=1209%2C466)

### How Css Rules Cascade
- #### LAST RULE: If the two selectors are identical, the latter of the two will take precedence.
- #### SPECIFICITY : If one selector is more specific than the others, the more specific rule will take precedence over more general ones 
- #### IMPORTANT: You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element. 
<Enter>
- ### note : we use external CSS sheet beacuse when building a website there are several advantages to placing your CSS rules in a separate style sheet.

### Summary INTRODUCING CSS
![image](https://user-images.githubusercontent.com/79092103/109427944-6a2db800-79fd-11eb-85e6-ffdd465a91b9.png)


## JavaScript (Chapter 02: Basic of JavaScript)

### Basic JavaScript Instructions
As we know before a script is a series of instructions that a computer can follow one-by-one.
Each step called **statment** that should end with a semicolon.
The semicolon also tells the JavaScript interpreter when a step is over, indicating that it should move to the next step.

Some statements are surrounded by curly braces;
these are known as *code blocks*

JAVASCRIPT is case sensitive, so we should be careful during coding.

We can add a single line comment by starting the line with // and for multi-line comments starting the comments with the /* characters and ending with the */ characters.

**Variable** 

It is something like container with dynamic value that can be changed dynamically.
Before using variable we should declare it (give it name) like this *var quantity;*

**Data Types**
* Number like (var price=10;)
* String like (var Name='SUN';)
* Boolean true or false like (var inStock=false;)

**Rules for naming variable**
* The name must begin with a letter, dollar sign ($),or an underscore (_).
* The name can contain letters, numbers, dollar sign ($), or an underscore (_).
* We cannot use keywords or reserved words.
* All variables are case sensitive.
* Use a name that describes the kind of information that the variable stores.
* Use a capital letter for the first letter of
every word after the first word when the variable has more than word.

**Arrays**

An array is a special type of variable. It doesn't
just store one value; it stores a list of values.

It is helpful when we do not know how
many items a list will contain.

![arrays type](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/how-to-create-JavaScript-array.jpg)

**Array Literal** like this ( colors= ['white',
'black',
'custom']; )

**Array constructor** like this ( var colors=new Array('white ' ,
'black',
'custom ' ); )

**VALUES IN ARRAYS**

Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).

We can change the value of an item an array by selecting it and assigning it a new value just as
we would any other variable (using the equals sign and the new value for that item).

**EXPRESSIONS**
It is evaluating into a single value.

Type of expressions 

* That just assign a value to a variable, like this var color = 'beige';
* That use two or more values to return a single value, like this var area = 3 * 2;

**OPERATORS**

They allow programmers to create a single value from one or more values.

* Assignment operators ( color = 'beige'; )
* Comparison operators (buy = 3 > 5;)
* Arithmetic operators (area = 3 * 2;)
* String operators (greeting= 'Hi'+ 'Molly';)
* Logical operators (buy= (5 > 3) && (2 < 4);)


#### Decisions and Loops


**Decision Making**
Flowcharts can help us plan for which lines of code should be run next.
There are 2 components to a decision :
* An expression is evaluated , which return a value
* A conditional statement says what to do in a given situation

We evaluate a situation by comparing one value in the script to what we expect it might to be.
The result will be a Boolean (true or false).

![Comparison operator](https://i.ytimg.com/vi/wFB-ywsNPwg/maxresdefault.jpg)

![logical operator](https://chunxuchai.files.wordpress.com/2019/05/logical-operator.jpg)

**IF statement**

If statement evaluates or check the condition. If the condition is true , any statements in the subsequent code block are excuted.

**The IF ... else statement**

It checks a condition if it is true , the first code block is excuted . If the condition is false , the second code block is run instead.

![if else statement](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-if-else-statment.png)
