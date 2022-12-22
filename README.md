# [HTML Tutorial](https://www.youtube.com/@codingcollege)

HTML stands for Hyper Text Markup Language, which is the most widely used language on the Web to develop web pages.

## Why Learn HTML?

Originally, HTML was developed with the intent of defining the structure of documents like headings, paragraphs, lists, and so forth. HTML is widely used to format web pages with the help of different tags available in HTML language.

I will list down some of the key advantages of learning HTML:

- Create a Web site
- Become a web designer
- What is the Web?
- Learn other languages

### HTML Document Structure

Following is an example of an basic HTML document.

```html
<!DOCTYPE html>
<html>

   <head>
      <!-- Title of page -->
      <title>Html Tutorial</title>
   </head>

   <body>
      <!-- 1st heading -->
      <h1>Basic HTML Document</h1>
      <!-- Paragraph and content goes here -->
      <p>Hello World!</p>
   </body>

</html>
```

## HTML Tags

HTML is a markup language that uses tags to format the content. These tags are enclosed within angle braces `<Tag Name>`. Most of the tags have their corresponding closing tags. For example, `<html>` has its closing tag `</html>` etc.

The above example of an HTML document uses the following tags:

| Sr.No | Tag | Description |
| ----- | ----| ----------- |
| 1 | `<!DOCTYPE...>` | This tag defines the document type and HTML version. |
| 2 | `<html>` | This tag encloses the complete HTML document |
| 3 | `<head>` | This tag represents the document's header which can keep other HTML tags. |
| 4 | `<title>` | The `<title>` tag is used inside the `<head>` tag to mention the document title. |
| 5 | `<body>` | This tag represents the document's body which keeps all other HTML tags. |
| 6 | `<h1>` | This tag represents the heading. |
| 7 | `<p>` | This tag represents a paragraph. |

### HTML Basic Tags

To learn HTML, you will need to study various tags and understand how they behave while formatting a document.

#### Heading Tags

Any document starts with a heading tag. You can use different sizes for your headings. HTML has `6` levels of headings, which is `<h1>`, `<h2>` and upto `<h6>`. While displaying any heading, browser adds one line before and one line after that heading.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Heading Example</title>
   </head>

   <body>
      <h1>This is heading 1</h1>
      <h2>This is heading 2</h2>
      <h3>This is heading 3</h3>
      <h4>This is heading 4</h4>
      <h5>This is heading 5</h5>
      <h6>This is heading 6</h6>
   </body>

</html>
```

#### Paragraph Tag

The `<p>` tag offers a way to structure your text into different paragraphs. Each paragraph has an opening `<p>` and a closing `</p>` tag.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Paragraph Example</title>
   </head>

   <body>
      <p>Here is a first paragraph of text.</p>
      <p>Here is a second paragraph of text.</p>
      <p>Here is a third paragraph of text.</p>
   </body>

</html>
```

#### Line Break Tag

Whenever you use the `<br />` element, it will break line and starts a new line. This tag do not need opening and closing tags, as there is nothing to go in between them.

> The `<br />` tag has a space between the characters `br` and the forward slash. If you omit this space, older browsers will have trouble rendering the line break.

## HTML - Elements

An HTML element is defined by a starting tag, the element contains other content and ends with a closing tag.

| Start Tag | Content | End Tag |
| --------- | ------- | ------- |
| `<p>` | This is paragraph content. | `</p>` |
| `<h1>` | This is heading content. | `</h1>` |

Here `<p>....</p>` is an HTML element, `<h1>...</h1>` is another HTML element.

## HTML - Attributes

An attribute is used to define the characteristics of an HTML element and is placed inside the opening tag. All attributes are made up of two parts − a `name` and a `value`.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Network Automation</title>
    </head>
    <body>
        <h1 align="center">Python for Network Engineer</h1>
    </body>
</html>
```

### The Id Attribute

The `id` attribute can be used to uniquely identify any element within an HTML page. There are two primary reasons that you might want to use an `id` attribute on an element.

- If an element carries an `id` attribute, it is possible to refrence that element and its content.
- If you have two elements of the same name within a Web page and want to distinguish between elements that have the same name.

### The class Attribute

The `class` attribute is used to associate an element with a style sheet, and specifies the class of element. Multiple HTML elements can share the same `class`.

## HTML - Links

A webpage can contain various links that take you directly to other pages and even specific parts of a given page.

### Linking Documents

A link is specified using HTML tag `<a>`. This tag is called `anchor` tag and anything between becomes part of the link and a user can click that part to reach to the linked document.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>About</title>
    </head>
    <body>
        <h1>Syed Asif</h1>
        <a href="https://tech-net.hashnode.dev/">Blog</a> <br/>
        <a href="https://twitter.com/SydAsif78">Twitter</a> <br/>
        <a href="https://github.com/sydasif">GitHub</a> <br/>
    </body>
</html>
```

### The target Attribute

This attribute is used to specify the location where linked document is opened.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>About</title>
    </head>
    <body>
        <h1>Syed Asif</h1>
        <a href="https://tech-net.hashnode.dev/" target="_blank">Blog</a> <br/>
        <a href="https://twitter.com/SydAsif78" target="_blank">Twitter</a> <br/>
        <a href="https://github.com/sydasif" target="_blank">GitHub</a> <br/>
    </body>
</html>
```

Following are the possible options:

1. `_blank` - Opens the linked document in a new window or tab.
2. `_self` - Opens the linked document in the same frame.
3. `_parent` - Opens the linked document in the parent frame.
4. `_top` - Opens the linked document in the full body of the window.

You can link HTML documents related to the same website, it is not required to give a complete URL for every link.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Network Automation</title>
    </head>
    <body>
        <h1>Python for Network Engineer</h1>
        <a href="book/">Read the Book</a> <br/>
        <a href="about.html">About the Author</a>
    </body>
</html>
```

### Linking to a Page Section

You can create a link to a particular section of a webpage by using `id` attribute. This is a two-step process.

- First create a link to the place where you want to reach with in a webpage and name it using  `id` as follows:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>automation?</title>
    </head>
    <body>
        <p id="why-programming">
            Network engineering is changing, as a network engineer, there has never been a better time for you to learn programming to automate networks and write code. In the late 90’s – 2010, a network engineer typed in the same CLI commands hundreds/thousands, of times to configure and troubleshoot network devices.
        </p>
    </body>
</html>
```

- Second step is to create a hyperlink to link the document and place the fregment `#why-programing` where you want to reach.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Network Automation</title>
    </head>
    <body>
        <a href="book/ch01/01_automation.html#why-programming">Why learn Programming?</a> <br />
    </body>
</html>
```
