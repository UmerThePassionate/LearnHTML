# LearnHTML
 

### Hi there Welcome!👋

Today we are going to start HTML development course.We will cover all the features that we need in 2024.


# Let's start

<h1> HTML Introduction </h1>


<h3> What is HTML? </h3>

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

<h2> A Simple HTML Document </h2>

#### Example

``` 
   
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```


### Example Explained


- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document.
- The `<html>` element is the root element of an HTML page.
- The `<head>` element contains meta information about the HTML page.
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
- The `<body>` element defines the document's body, and is a container for all the  visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph.

<h2> What is an HTML Element? </h2>

An HTML element is defined by a start tag, some content, and an end tag:

     <h3> <tagname> Content goes here... </tagname> </h3>

The HTML element is everything from the start tag to the end tag:
```
 <h1>My First Heading</h1> 
 <p>My first paragraph.</p> 
```

     
<h2>Web Browsers</h2>


The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

![variableExample1](https://www.w3schools.com/html/img_chrome.png)<br><br>


<h2>HTML Page Structure</h2>

Below is a visualization of an HTML page structure:


![variableExample2](https://scontent.fisb1-2.fna.fbcdn.net/v/t1.6435-9/179112594_106814681559996_3638101514266665353_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=5f2048&_nc_ohc=9v9PwiApR34Q7kNvgHREgRf&_nc_ht=scontent.fisb1-2.fna&oh=00_AYCqNdF-MhE1E33_AWuMpCxl2JtWXbP-em2j5Mm6r2I4ow&oe=666D2246)<br><br>




<h1>HTML Editors</h1>

A simple text editor is all you need to learn HTML.

### Learn HTML Using Notepad or TextEdit

Web pages can be created and modified by using professional HTML editors.

However, for learning HTML we recommend a simple text editor like Notepad (PC) or TextEdit (Mac).

We believe that using a simple text editor is a good way to learn HTML.

Follow the steps below to create your first web page with Notepad or TextEdit.

<h2> Step 1: Open Notepad (PC) </h2>

- Windows 8 or later:

- Open the Start Screen (the window symbol at the bottom left on your screen). Type Notepad.

- Windows 7 or earlier:

- Open Start > Programs > Accessories > Notepad

<h2>Step 1: Open TextEdit (Mac)</h2>

- Open Finder > Applications > TextEdit

- Also change some preferences to get the application to save files correctly. In Preferences > Format > choose "Plain Text"

- Then under "Open and Save", check the box that says "Display HTML files as HTML code instead of formatted text".

- Then open a new document to place the code.

<h2>Step 2: Write Some HTML</h2>

Write or copy the following HTML code into Notepad:

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```
![example](https://www.w3schools.com/html/img_notepad.png)<br><br>

<h2>Step 3: Save the HTML Page </h2>

Save the file on your computer. Select File > Save as in the Notepad menu.

Name the file "index.htm" and set the encoding to UTF-8 (which is the preferred encoding for HTML files).

![example2](https://www.w3schools.com/html/img_saveas.png)<br><br>

<h2>Step 4: View the HTML Page in Your Browser </h2>

Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose "Open with").

The result will look much like this:

![example3](https://www.w3schools.com/html/img_chrome.png)<br><br>





<h1>HTML Basic Examples</h1>

In this chapter we will show some basic HTML examples.

Don't worry if we use tags you have not learned about yet.

<h3>HTML Documents</h3>


All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

<h2>The <!DOCTYPE> Declaration</h2>

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The `<!DOCTYPE>` declaration is not case sensitive.

The `<!DOCTYPE>` declaration for HTML5 is:

```
<!DOCTYPE html>
```

<h2>HTML Headings</h2>


HTML headings are defined with the `<h1>` to `<h6>` tags.
`<h1>` defines the most important heading. `<h6>` defines the least important heading: 


```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

<h2>HTML Paragraphs</h2>


HTML paragraphs are defined with the `<p>` tag: 

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

<h2>HTML Links</h2>

HTML links are defined with the `<a>` tag:

```
<a href="https://www.codewithumer.com">This is a link</a>
```

The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.

You will learn more about attributes in a later chapter.


<h2>HTML Images</h2>

HTML images are defined with the `<img>` tag.

The source file `(src)`, alternative text `(alt)`, width, and height are provided as attributes:

```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```

<h1>HTML Elements</h1>

The HTML element is everything from the start tag to the end tag:

```
<tagname>Content goes here...</tagname>
```

Examples of some HTML elements:

```
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

<h2>Nested HTML Elements</h2>

HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

```The following example contains four HTML elements (<html>, <body>, <h1> and <p>):```

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
<h3>Example Explained </h3>

The `<html>` element is the root element and it defines the whole HTML document.

It has a start tag `<html>` and an end tag `</html>`.

Then, inside the <html> element there is a <body> element:

```
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
```

The `<body>` element defines the document's body.

It has a start tag `<body>` and an end tag `</body>`.

Then, inside the `<body>` element there are two other elements: `<h1>` and `<p>`:

```
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

The `<h1>` element defines a heading.

It has a start tag `<h1>` and an end tag `</h1>`:

```
<h1>My First Heading</h1>
```
The `<p>` element defines a paragraph.

It has a start tag `<p>` and an end tag `</p>`:

```
<p>My first paragraph.</p>
```

<h2>Never Skip the End Tag</h2>

Some HTML elements will display correctly, even if you forget the end tag:

```
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
```

<h3>Empty HTML Elements</h3>

HTML elements with no content are called empty elements.

The `<br>` tag defines a line break, and is an empty element without a closing tag:

```
<p>This is a <br> paragraph with a line break.</p>
```

<h2>HTML is Not Case Sensitive</h2>

HTML tags are not case sensitive: `<P>` means the same as `<p>`.

The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

<h1>HTML Attributes</h1>

HTML attributes provide additional information about HTML elements.

<h3>HTML Attributes</h3>

- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"

<h3>The href Attribute</h3>

The `<a>` tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

```
<a href="https://www.codewithumer.com">Visit W3Schools</a>
```

<h3>The src Attribute</h3>

The `<img>` tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

```
<img src="img_girl.jpg">
```

There are two ways to specify the URL in the src attribute:

<h3>Absolute URL</h3>

Links to an external image that is hosted on another website. Example: src="https://www.codewithumer.com/images/img_girl.jpg".

<h5>Notes:</h5>External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

<h3>Relative URL</h3>

Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

<h3>The width and height Attributes</h3>

The `<img>` tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

```
<img src="img_girl.jpg" width="500" height="600">
```

<h3>The alt Attribute</h3>

The required alt attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

```
<img src="img_girl.jpg" alt="Girl with a jacket">
```

<h3>The style Attribute</h3>

The style attribute is used to add styles to an element, such as color, font, size, and more.

```
<p style="color:red;">This is a red paragraph.</p>
```

<h3>The lang Attribute</h3>

You should always include the lang attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:

```
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```
Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.




The following example specifies English as the language and United States as the country:

```
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

<h3>The title Attribute</h3>

The title attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

```
<p title="I'm a tooltip">This is a paragraph.</p>
```

<h2>Chapter Summary</h2>

- All HTML elements can have attributes
- The href attribute of <a> specifies the URL of the page the link goes to
- The src attribute of <img> specifies the path to the image to be displayed
- The width and height attributes of <img> provide size information for images
- The alt attribute of <img> provides an alternate text for an image
- The style attribute is used to add styles to an element, such as color, font, size, and more
- The lang attribute of the <html> tag declares the language of the Web page
- The title attribute defines some extra information about an element


<h1>HTML Headings</h1>

HTML headings are titles or subtitles that you want to display on a webpage.

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>


<h2>HTML Headings</h2>

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

<h2>Headings Are Important</h2>

Search engines use the headings to index the structure and content of your web pages.

Users often skim a page by its headings. It is important to use headings to show the document structure.

`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

<h2>Bigger Headings></h2>

```
<h1 style="font-size:60px;">Heading 1</h1>
```


<h1>HTML Paragraphs</h1>

The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

<h2>HTML Display</h2>

You cannot be sure how HTML will be displayed.

Large or small screens, and resized windows will create different results.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.

The browser will automatically remove any extra spaces and lines when the page is displayed:

```
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```

<h2>HTML Horizontal Rules</h2>

The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The `<hr>` element is used to separate content (or define a change) in an HTML page:

```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
The `<hr>` tag is an empty tag, which means that it has no end tag.


<h2>HTML Line Breaks</h2>

The HTML `<br>` element defines a line break.

Use `<br>` if you want a line break (a new line) without starting a new paragraph:

```
<p>This is<br>a paragraph<br>with line breaks.</p>
```
The `<br>` tag is an empty tag, which means that it has no end tag.


<h2>The Poem Problem</h2>

This poem will display on a single line:

```
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

## Solution - The HTML <pre> Element

The HTML `<pre>` element defines preformatted text.

The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:  

```
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre
```


<h1>HTML Styles</h1>


The HTML style attribute is used to add styles to an element, such as color, font, size, and more.


<h2>The HTML Style Attribute<h2>


Setting the style of an HTML element, can be done with the style attribute.
The HTML style attribute has the following syntax:

```
<tagname style="property:value;">
```
The property is a CSS property. The value is a CSS value.


<h2>Background Color</h2>

The CSS background-color property defines the background color for an HTML element.

<h5>Set the background color for a page to powderblue:</h5>

```
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

<h5>Set background color for two different elements:</h5>

```
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```

<h2>Text Color</h2>

The CSS color property defines the text color for an HTML element:

```
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

<h2>Fonts</h2>

The CSS font-family property defines the font to be used for an HTML element:

```
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```

<h2>Text Size</h2>

The CSS font-size property defines the text size for an HTML element:

```
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```

<h2>Text Alignment</h2>

The CSS text-align property defines the horizontal text alignment for an HTML element:

```
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```

<h1>Chapter Summary</h1>

- Use the `style attribute` for styling HTML elements
- Use `background-color` for background color
- Use `color` for text colors
- Use `font-family` for text fonts
- Use `font-size` for text sizes
- Use `text-align` for text alignment





<h1>HTML Text Formatting</h1>

HTML contains several elements for defining text with a special meaning.

<h2>HTML Formatting Elements</h2>

Formatting elements were designed to display special types of text:

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
-`<del>` - Deleted text
- `<ins>` - Inserted text
-`<sub>` - Subscript text
- `<sup>` - Superscript text

## HTML `<b>` and `<strong>` Elements

The HTML `<b>` element defines bold text, without any extra importance.

```
<b>This text is bold</b>
```
The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.

```
<strong>This text is important!</strong>
```

## HTML `<i>` and `<em>` Elements

The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.

Tip: The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

```
<i>This text is italic</i>
```

The HTML `<em>` element defines emphasized text. The content inside is typically displayed in italic.

Tip: A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.

```
<em>This text is emphasized</em>
```

## HTML `<small>` Element

The HTML `<small>` element defines smaller text:

```
<small>This is some smaller text.</small>
```

## HTML `<mark>` Element

The HTML `<mark>` element defines text that should be marked or highlighted:

```
<p>Do not forget to buy <mark>milk</mark> today.</p>
```

## HTML `<del>` Element

The HTML `<del>` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

```
<p>My favorite color is <del>blue</del> red.</p>
```

## HTML `<ins>` Element

The HTML `<ins>` element defines a text that has been inserted into a document. Browsers will usually underline inserted text:

```
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```

## HTML `<sub>` Element

The HTML `<sub>` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

```
<p>This is <sub>subscripted</sub> text.</p>
```

## HTML `<sup>` Element


The HTML `<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW`[1]`:

```
<p>This is <sup>superscripted</sup> text.</p>
```



<h1>HTML Quotation and Citation Elements</h1>

In this chapter we will go through the `<blockquote>`,`<q>`, `<abbr>`, `<address>`, `<cite>`, and `<bdo>` HTML elements.

```
Here is a quote from WWF's website:

For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
```

## HTML `<blockquote>` for Quotations

The HTML `<blockquote>` element defines a section that is quoted from another source.

Browsers usually indent `<blockquote>` elements.

### Example
```
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities, wildlife, and the places in which they live.
</blockquote>
```

## HTML `<q>` for Short Quotations

The HTML `<q>` tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

```
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```


# HTML Comments

HTML comments are not displayed in the browser, but they can help document your HTML source code.

## HTML Comment Tag


```
<!-- Write your comments here -->
```

## Add Comments

With comments you can place notifications and reminders in your HTML code:

```
<!-- This is a comment -->

<p>This is a paragraph.</p>

<!-- Remember to add more information here -->
```


# HTML Colors

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

## Color Names

In HTML, a color can be specified by using a color name:

## Background Color

You can set the background color for HTML elements:


```
<h1 style="background-color:DodgerBlue;">Hello World</h1>
```


## Text Color

You can set the color of text:

### example

```
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

## Border Color

You can set the color of borders:

```
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```


## Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

The following three <div> elements have their background color set with RGB, HEX, and HSL values:

### example

```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```


# HTML Styles - CSS

CSS stands for Cascading Style Sheets.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

## What is CSS?

Cascading Style Sheets (CSS) is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

### Using CSS

CSS can be added to HTML documents in 3 ways:

- `Inline` - by using the style attribute inside HTML elements
- `Internal` - by using a `<style>` element in the `<head>` section
- `External` - by using a `<link>` element to link to an external CSS file

The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.


## Inline CSS

An inline CSS is used to apply a unique style to a single HTML element.

An inline CSS uses the style attribute of an HTML element.

The following example sets the text color of the `<h1>` element to blue, and the text color of the `<p>` element to red:

### Example
```
<h1 style="color:blue;">A Blue Heading</h1>
<p style="color:red;">A red paragraph.</p>
```

## Internal CSS


An internal CSS is used to define a style for a single HTML page.

An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.

The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red. In addition, the page will be displayed with a "powderblue" background color: 

### Example

```
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## External CSS

An external style sheet is used to define the style for many HTML pages.

To use an external style sheet, add a link to it in the `<head>` section of each HTML page:

## Example

```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

The external style sheet can be written in any text editor. The file must not contain any HTML code, and must be saved with a .css extension.

Here is what the "styles.css" file looks like:

## "styles.css":
```
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```

## CSS Colors, Fonts and Sizes

Here, we will demonstrate some commonly used CSS properties. You will learn more about them later.

The CSS `color` property defines the text color to be used.

The CSS `font-family` property defines the font to be used.

The CSS `font-size` property defines the text size to be used.

### Example
Use of CSS color, font-family and font-size properties:
```
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
  color: blue;
  font-family: verdana;
  font-size: 300%;
}
p {
  color: red;
  font-family: courier;
  font-size: 160%;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```


## CSS Border

The CSS border property defines a border around an HTML element.

Tip: You can define a border for nearly all HTML elements.

### Example

Use of CSS border property: 
```
p {
  border: 2px solid powderblue;
}
```


## CSS Padding

The CSS padding property defines a padding (space) between the text and the border.

### Example

Use of CSS border and padding properties:
```
p {
  border: 2px solid powderblue;
  padding: 30px;
}
```

## CSS Margin

The CSS margin property defines a margin (space) outside the border.

### Example

Use of CSS border and margin properties:
```
p {
  border: 2px solid powderblue;
  margin: 50px;
}
```
## Link to External CSS

External style sheets can be referenced with a full URL or with a path relative to the current web page.
### Example

This example uses a full URL to link to a style sheet:
```
<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
```
### Example

This example links to a style sheet located in the html folder on the current web site: 
```
<link rel="stylesheet" href="/html/styles.css">
```
### Example

This example links to a style sheet located in the same folder as the current page:
```
<link rel="stylesheet" href="styles.css">
```
#### You can read more about file paths in the chapter HTML File Paths.

# Chapter Summary

- Use the HTML style attribute for inline styling
- Use the HTML `<style>` element to define internal CSS
- Use the HTML `<link>` element to refer to an external CSS file
- Use the HTML `<head>` element to store `<style>` and `<link>` elements
- Use the CSS color property for text colors
- Use the CSS font-family property for text fonts
- Use the CSS font-size property for text sizes
- Use the CSS border property for borders
- Use the CSS padding property for space inside the border
- Use the CSS margin property for space outside the border


# HTML Links

Links are found in nearly all web pages. Links allow users to click their way from page to page.

## HTML Links - Syntax

The HTML `<a>` tag defines a hyperlink. It has the following syntax:
```
<a href="url">link text</a>

```

The most important attribute of the `<a>` element is the `href` attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.

### Example

This example shows how to create a link to W3Schools.com:
```
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>`
```

## HTML Links - The target Attribute

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

- _self - Default. Opens the document in the same window/tab as it was clicked
- _blank - Opens the document in a new window or tab
- _parent - Opens the document in the parent frame
- _top - Opens the document in the full body of the window

### Example

Use target="_blank" to open the linked document in a new browser window or tab:
```
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
```

## Absolute URLs vs. Relative URLs

Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

### Example
```
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
```

## HTML Links - Use an Image as a Link

To use an image as a link, just put the `<img>` tag inside the `<a>` tag:

### Example
```
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

## Link to an Email Address

Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

## Example
```
<a href="mailto:someone@example.com">Send email</a>
```
## Button as a Link

To use an HTML button as a link, you have to add some JavaScript code.

JavaScript allows you to specify what happens at certain events, such as a click of a button:

## Example
```
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```


# HTML Images

## HTML Images Syntax

The HTML `<img>` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.

The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.

The `<img>` tag has two required attributes:

- src - Specifies the path to the image
- alt - Specifies an alternate text for the image

##Syntax
```
<img src="url" alt="alternatetext">
```

## The src Attribute

The required src attribute specifies the path (URL) to the image.

Note: When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

### Example
```
<img src="img_chania.jpg" alt="Flowers in Chania">
```

# The HTML `<picture>` Element

The HTML `<picture>` element gives web developers more flexibility in specifying image resources.

The `<picture>` element contains one or more `<source>` elements, each referring to different images through the srcset attribute. This way the browser can choose the image that best fits the current view and/or device.

Each `<source>` element has a media attribute that defines when the image is the most suitable.

### Example

Show different images for different screen sizes:
```
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg">
</picture>
```


# HTML Favicon

A favicon is a small image displayed next to the page title in the browser tab.

## How To Add a Favicon in HTML

You can use any image you like as your favicon. You can also create your own favicon on sites like https://www.favicon.cc.

A favicon image is displayed to the left of the page title in the browser tab, like this:

![Favicon](https://www.w3schools.com/html/img_favicon.png)

To add a favicon to your website, either save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. A common name for a favicon image is "favicon.ico".

Next, add a `<link>` element to your "index.html" file, after the `<title>` element, like this:

### Example
```
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
Now, save the "index.html" file and reload it in your browser. Your browser tab should now display your favicon image to the left of the page title.


# HTML Page Title

Every web page should have a page title to describe the meaning of the page.

The `<title>` element adds a title to your page:

## Example
```
<!DOCTYPE html>
<html>
<head>
  <title>HTML Tutorial</title>
</head>
<body>

The content of the document......

</body>
</html>
```
The title is shown in the browser's title bar:

![title](https://www.w3schools.com/html/pagetitle.jpg)

The title should describe the content and the meaning of the page.

The page title is very important for search engine optimization (SEO). The text is used by search engine algorithms to decide the order when listing pages in search results.

The `<title>` element:

- defines a title in the browser toolbar
- provides a title for the page when it is added to favorites
- displays a title for the page in search engine-results

So, try to make the title as accurate and meaningful as possible!


# HTML Tables

HTML tables allow web developers to arrange data into rows and columns.

## Define an HTML Table

A table in HTML consists of table cells inside rows and columns.

### Example

A simple HTML table:
```
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

## Table Cells

Each table cell is defined by a `<td>` and a `</td>` tag.

td stands for table data.

Everything between `<td>` and `</td>` are the content of the table cell.

### Example
```
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
```

## Table Rows

Each table row starts with a <tr> and ends with a </tr> tag.

tr stands for table row.

### Example
```
<table>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```
You can have as many rows as you like in a table; just make sure that the number of cells are the same in each row.


## Table Headers

Sometimes you want your cells to be table header cells. In those cases use the <th> tag instead of the <td> tag:

th stands for table header.

### Example

Let the first row be table header cells:
```
<table>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>
```
By default, the text in `<th>` elements are bold and centered, but you can change that with CSS.

# HTML Table Borders

HTML tables can have borders of different styles and shapes.

## How To Add a Border

To add a border, use the CSS border property on table, th, and td elements:

 	 	 
 	 	 
### Example
```
table, th, td {
  border: 1px solid black;
}
```


## Style Table Borders

If you set a background color of each cell, and give the border a white color (the same as the document background), you get the impression of an invisible border:

 	 	 
### Example
```
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
th, td {
  background-color: #96D4D4;
}
```

## Round Table Borders

With the border-radius property, the borders get rounded corners:
 	 	 
### Example
```
table, th, td {
  border: 1px solid black;
  border-radius: 10px;
}
```

## Dotted Table Borders

With the border-style property, you can set the appearance of the border.
 	 	 
The following values are allowed:

- dotted     
- dashed     
- solid     
- double     
- groove     
- ridge     
- inset     
- outset     
- none     
- hidden     
```
Example
 th, td {
  border-style: dotted;
}
```

## Border Color

With the border-color property, you can set the color of the border.
 	 	 
### Example
``` 
th, td {
  border-color: #96D4D4;
}
```


## HTML Table Sizes

HTML tables can have different sizes for each column, row or the entire table.
 	 	 
Use the style attribute with the width or height properties to specify the size of a table, row or column.

## HTML Table Width

To set the width of a table, add the style attribute to the <table> element:

### Example

Set the width of the table to 100%:

```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```


## HTML Table Column Width
 	 	 
To set the size of a specific column, add the style attribute on a <th> or <td> element:

### Example

Set the width of the first column to 70%:
```
<table style="width:100%">
  <tr>
    <th style="width:70%">Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

## HTML Table Headers

HTML tables can have headers for each column or row, or for many columns/rows.


## HTML Table Headers

Table headers are defined with th elements. Each th element represents a table cell.

### Example
```
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

## Vertical Table Headers

To use the first column as table headers, define the first cell in each row as a <th> element:

### Example
```
<table>
  <tr>
    <th>Firstname</th>
    <td>Jill</td>
    <td>Eve</td>
  </tr>
  <tr>
    <th>Lastname</th>
    <td>Smith</td>
    <td>Jackson</td>
  </tr>
  <tr>
    <th>Age</th>
    <td>94</td>
    <td>50</td>
  </tr>
</table>
```

## Align Table Headers

By default, table headers are bold and centered:

To left-align the table headers, use the CSS text-align property:

## Example
```
th {
  text-align: left;
}
```

# HTML Table Padding & Spacing

HTML tables can adjust the padding inside the cells, and also the space between the cells.

## HTML Table - Cell Padding

Cell padding is the space between the cell edges and the cell content.

By default the padding is set to 0.

To add padding on table cells, use the CSS padding property:

### Example
```
th, td {
  padding: 15px;
}
```

To add padding only above the content, use the padding-top property.

And the others sides with the padding-bottom, padding-left, and padding-right properties:

### xample
```
th, td {
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 30px;
  padding-right: 40px;
}
```

## HTML Table - Cell Spacing

Cell spacing is the space between each cell.

By default the space is set to 2 pixels.

To change the space between table cells, use the CSS `border-spacing` property on the table element:

## Example
```
table {
  border-spacing: 30px;
}
```



# HTML Table Colspan & Rowspan

HTML tables can have cells that span over multiple rows and/or columns.

## HTML Table - Colspan

To make a cell span over multiple columns, use the colspan attribute:

### Example
```
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>57</td>
  </tr>
</table>
```
Note: The value of the colspan attribute represents the number of columns to span.


## HTML Table - Rowspan

To make a cell span over multiple rows, use the rowspan attribute:

### Example
```
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>555-1234</td>
  </tr>
  <tr>
    <td>555-8745</td>
</tr>
</table>
```
Note: The value of the rowspan attribute represents the number of rows to span.

# HTML Table Styling

Use CSS to make your tables look better.

To style every other table row element, use the `:nth-child(even)` selector like this:

### Example
```
tr:nth-child(even) {
  background-color: #D6EEEE;
}
```
Note: If you use (odd) instead of (even), the styling will occur on row 1,3,5 etc. instead of 2,4,6 etc.

## HTML Table - Vertical Zebra Stripes

To make vertical zebra stripes, style every other column, instead of every other row.

Set the `:nth-child(even)` for table data elements like this:

## Example
```
td:nth-child(even), th:nth-child(even) {
  background-color: #D6EEEE;
}
```
Note: Put the `:nth-child()` selector on both th and td elements if you want to have the styling on both headers and regular table cells.

## Combine Vertical and Horizontal Zebra Stripes

You can combine the styling from the two examples above and you will have stripes on every other row and every other column.

If you use a transparent color you will get an overlapping effect.
	 	 	 	 	 	 	 	 
Use an `rgba()` color to specify the transparency of the color:

### Example
```
tr:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}

th:nth-child(even),td:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
```

## Hoverable Table

Use the :hover selector on tr to highlight table rows on mouse over:

### Example
```
tr:hover {background-color: #D6EEEE;}
```

# HTML Lists

HTML lists allow web developers to group a set of related items in lists.

## Unordered HTML List

An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

The list items will be marked with bullets (small black circles) by default:

### Example
```
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

## Ordered HTML List

An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

The list items will be marked with numbers by default:

### Example
```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## HTML Description Lists

HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term:

### Example
```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```


# HTML Block and Inline Elements

Every HTML element has a default display value, depending on what type of element it is.

The two most common display values are block and inline.

## Block-level Elements

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: `<p>` and `<div>`.

The `<p>` element defines a paragraph in an HTML document.

The `<div>` element defines a division or a section in an HTML document.

### Example
```
<p>Hello World</p>
<div>Hello World</div>
```
Here are the block-level elements in HTML:

```
<address><article><aside><blockquote><canvas><dd><div><dl><dt><fieldset><figcaption><figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript><ol><p><pre><section><table><tfoot><ul><video>
```
## Inline Elements

An inline element does not start on a new line.

An inline element only takes up as much width as necessary.

### Example
```
<span>Hello World</span>
```
Here are the inline elements in HTML:
```
<a><abbr><acronym><b><bdo><big><br><button><cite><code><dfn><em><i><img><input><kbd><label><map><object><output><q><samp><script><select><small><span><strong><sub><sup><textarea><time><tt><var>
```
Note: An inline element cannot contain a block-level element!



# HTML Div Element

The `<div>` element is used as a container for other HTML elements.

## The `<div>` Element

The `<div>` element is by default a block element, meaning that it takes all available width, and comes with line breaks before and after.

### Example

A `<div>` element takes up all available width:
```
Lorem Ipsum <div>I am a div</div> dolor sit amet.
```

The `<div>` element has no required attributes, but style, class and id are common.


## `<div>` as a container

The `<div>` element is often used to group sections of a web page together.

### Example

A `<div>` element with HTML elements:
```
<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>
```

## Center align a `<div>` element

If you have a `<div>` element that is not 100% wide, and you want to center-align it, set the CSS margin property to auto.

### Example
```
<style>
div {
  width:300px;
  margin:auto;
}
</style>
```

## Multiple `<div>` elements

You can have many `<div>` containers on the same page.

### Example
```
<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 13 million inhabitants.</p>
</div>

<div>
  <h2>Oslo</h2>
  <p>Oslo is the capital city of Norway.</p>
  <p>Oslo has over 600.000 inhabitants.</p>
</div>

<div>
  <h2>Rome</h2>
  <p>Rome is the capital city of Italy.</p>
  <p>Rome has almost 3 million inhabitants.</p>
</div>
```

## Aligning `<div>` elements side by side

When building web pages, you often want to have two or more `<div>` elements side by side, like this:

There are different methods for aligning elements side by side, all include some CSS styling. We will look at the most common methods:

## Float
The CSS float property was not originally meant to align `<div>` elements side-by-side, but has been used for this purpose for many years.

The CSS float property is used for positioning and formatting content and allow elements float next to each other instead of on top of each other.

### Example
How to use float to align div elements side by side:
```
<style>
.mycontainer {
  width:100%;
  overflow:auto;
}
.mycontainer div {
  width:33%;
  float:left;
}
</style>
```



## Inline-block

If you change the `<div>` element's display property from block to inline-block, the `<div>` elements will no longer add a line break before and after, and will be displayed side by side instead of on top of each other.

### Example

How to use display: inline-block to align div elements side by side:
```
<style>
div {
  width: 30%;
  display: inline-block;
}
</style>
```

# Flex

The CSS Flexbox Layout Module was introduced to make it easier to design flexible responsive layout structure without using float or positioning.

To make the CSS flex method work, surround the `<div>`elements with another `<div>` element and give it the status as a flex container.

### Example

How to use flex to align div elements side by side:
```
<style>
.mycontainer {
  display: flex;
}
.mycontainer > div {
  width:33%;
}
</style>
```


# Grid

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

Sounds almost the same as flex, but has the ability to define more than one row and position each row individually.

The CSS grid method requires that you surround the `<div>` elements with another `<div>` element and give the status as a grid container, and you must specify the width of each column.

### Example

How to use grid to align `<div>` elements side by side:
```
<style>
.grid-container {
  display: grid;
  grid-template-columns: 33% 33% 33%;
}
</style>
```

# HTML class Attribute

The HTML class attribute is used to specify a class for an HTML element.

Multiple HTML elements can share the same class.

## Using The class Attribute

The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

In the following example we have three `<div>` elements with a class attribute with the value of "city". All of the three `<div>` elements will be styled equally according to the .city style definition in the head section:

### Example
```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>
```

## The Syntax For Class

To create a class; write a period `(.)` character, followed by a class name. Then, define the CSS properties within curly braces {}:

### Example
Create a class named "city":
```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
}
</style>
</head>
<body>

<h2 class="city">London</h2>
<p>London is the capital of England.</p>

<h2 class="city">Paris</h2>
<p>Paris is the capital of France.</p>

<h2 class="city">Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>

</body>
</html>
```

## Multiple Classes

HTML elements can belong to more than one class.

To define multiple classes, separate the class names with a space, e.g. `<div class="city main">`. The element will be styled according to all the classes specified.

In the following example, the first `<h2>` element belongs to both the city class and also to the main class, and will get the CSS styles from both of the classes: 

## Example
```
<h2 class="city main">London</h2>
<h2 class="city">Paris</h2>
<h2 class="city">Tokyo</h2>
```

## Different Elements Can Share Same Class

Different HTML elements can point to the same class name.

In the following example, both `<h2>` and `<p>`  point to the "city" class and will share the same style:

### Example
```
<h2 class="city">Paris</h2>
<p class="city">Paris is the capital of France</p>
```

## Use of The class Attribute in JavaScript

The class name can also be used by JavaScript to perform certain tasks for specific elements.

JavaScript can access elements with a specific class name with the getElementsByClassName() method:

### Example
Click on a button to hide all elements with the class name "city":
```
<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script>
```

# Chapter Summary
- The HTML class attribute specifies one or more class names for an element
- Classes are used by CSS and JavaScript to select and access specific elements
- The class attribute can be used on any HTML element
- The class name is case sensitive
- Different HTML elements can point to the same class name
- JavaScript can access elements with a specific class name with the getElementsByClassName() method


# HTML id Attribute

The HTML id attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

## Using The id Attribute

The id attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML document.

The id attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

In the following example we have an `<h1>` element that points to the id name "myHeader". This `<h1>` element will be styled according to the #myHeader style definition in the head section:

### Example
```
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```

## Difference Between Class and ID

A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page:

### Example
```
<style>
/* Style the element with the id "myHeader" */
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}

/* Style all elements with the class name "city" */
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
}
</style>

<!-- An element with a unique id -->
<h1 id="myHeader">My Cities</h1>

<!-- Multiple elements with same class -->
<h2 class="city">London</h2>
<p>London is the capital of England.</p>

<h2 class="city">Paris</h2>
<p>Paris is the capital of France.</p>

<h2 class="city">Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
```

# Chapter Summary
- The id attribute is used to specify a unique id for an HTML element
- The value of the id attribute must be unique within the HTML document
- The id attribute is used by CSS and JavaScript to style/select a specific element
- The value of the id attribute is case sensitive
- The id attribute is also used to create HTML bookmarks
- JavaScript can access an element with a specific id with the getElementById() method


# HTML Layout Elements and Techniques
Websites often display content in multiple columns (like a magazine or a newspaper).

## HTML Layout Elements

HTML has several semantic elements that define the different parts of a web page:


![layout](https://www.w3schools.com/html/img_sem_elements.gif)

- `<header>` - Defines a header for a document or a section
- `<nav>` - Defines a set of navigation links
- `<section>` - Defines a section in a document
- `<article>` - Defines an independent, self-contained content
- `<aside>` - Defines content aside from the content (like a sidebar)
- `<footer>` - Defines a footer for a document or a section
- `<details>` - Defines additional details that the user can open and close on demand
- `<summary>` - Defines a heading for the `<details>` element

## HTML Layout Techniques

There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

- CSS framework
- CSS float property
- CSS flexbox
- CSS grid

## CSS Frameworks
If you want to create your layout fast, you can use a CSS framework, like  Bootstrap.

## CSS Float Layout
It is common to do entire web layouts using the CSS float property. Float is easy to learn - you just need to remember how the float and clear properties work. Disadvantages: Floating elements are tied to the document flow, which may harm the flexibility.

## CSS Flexbox Layout
Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.

## CSS Grid Layout
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.


# HTML Responsive Web Design

Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports.

![imGE](https://www.w3schools.com/css/img_temp_band.jpg)

## What is Responsive Web Design?
Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones):

## Setting The Viewport
To create a responsive website, add the following <meta> tag to all your web pages:

### Example
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

## Responsive Images
Responsive images are images that scale nicely to fit any browser size.

### Using the width Property
If the CSS width property is set to 100%, the image will be responsive and scale up and down:

![IMA](https://www.w3schools.com/html/img_girl.jpg)

### Example
```
<img src="img_girl.jpg" style="width:100%;">
```
Notice that in the example above, the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.


## Using the max-width Property
If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size:

![IMGS](https://www.w3schools.com/html/img_girl.jpg)

### Example
```
<img src="img_girl.jpg" style="max-width:100%;height:auto;">
```


#HTML Semantic Elements

Semantic elements = elements with a meaning.

What are Semantic Elements?
A semantic element clearly describes its meaning to both the browser and the developer.

#### Examples of non-semantic elements: <div> and <span> - Tells nothing about its content.

#### Examples of semantic elements: <form>, <table>, and <article> - Clearly defines its content.