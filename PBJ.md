# Getting started with HTML

[Overview: Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

In this article, we cover the absolute basics of HTML. To get you started, this article defines elements, attributes, and all the other important terms you may have heard. It also explains where these fit into HTML. You will learn how HTML elements are structured, how a typical HTML page is structured, and other important basic language features. Along the way, there will be an opportunity to play with HTML too!

## What is HTML?

> [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML) (HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit. It can be as complicated or as simple as the web developer wants it to be. HTML consists of a series of [elements](https://developer.mozilla.org/en-US/docs/Glossary/Element), which you use to enclose, wrap, or *mark up* different parts of content to make it appear or act in a certain way. The enclosing [tags](https://developer.mozilla.org/en-US/docs/Glossary/Tag) can make content into a hyperlink to connect to another page, italicize words, and so on. For example, consider the following line of text:

```javascript
My cat is very grumpy
```
If we wanted the text to stand by itself, we could specify that it is a paragraph by enclosing it in a paragraph [`<p>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) element:

HTML:
```javascript
<p>My cat is very grumpy</p>
```

```javascript
Note: Tags in HTML are not case-sensitive. This means they can be written in uppercase or lowercase. For example, a <title> tag could be written as <title>, <TITLE>, <Title>, <TiTlE>, etc., and it will work. However, it is best practice to write all tags in lowercase for consistency and readability.
```
## Anatomy of an HTML element

Let's further explore our paragraph element from the previous section:

![anatomyOfElement](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

The anatomy of our element is:
* **The opening tag**: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
* **The content**: This is the content of the element. In this example, it is the paragraph text.
* **The closing tag**: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

[MDN Link for reference](https://generalassembly.instructure.com/courses/298/assignments/3674)