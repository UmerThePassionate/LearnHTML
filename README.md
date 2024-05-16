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

<h6>Absolute URL</h6>

Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

<h7>Notes:</h7>External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

<h6>Relative URL</h6>

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