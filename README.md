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

## HTML <sub> Element

The HTML `<sub>` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O:

```
<p>This is <sub>subscripted</sub> text.</p>
```

## HTML `<sup>` Element


The HTML `<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW`[1]`:

```
<p>This is <sup>superscripted</sup> text.</p>
```









