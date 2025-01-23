# Introduction To HTML

HTML is a standard markup language for creating web pages.

- HTML stands for Hyper Text Markup Language
- It is being used for creating web pages
- It describes only the structure of web page
- It consist of multiple elements
- It tells the browser how to display the content
- It runs on web browser

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Welcome to HSR Hi-Tech Solutions.</h1>
</body>
</html>
```

1. ``` <!DOCTYPE html> ``` :  This defines that this document is an HTML5 document.
2. ``` <html> ``` : It is the root element of an HTML document.
3. ``` lang= "en" ``` :  It represent that language used in content of this HTML document.
4. ``` <head> ``` :  It contains meta information of the HTML document.
5. ``` <title> ``` :  It specifies the title of the HTML page.
6. ``` <body> ``` : It defines the HTML document's body and is also a container for all the visible contents on a web page.
7. ``` <h1> ``` : It helps to create level 1 heading.


## HTML Elements

A HTML element is defined by a start tag, some content and an end tag.

Syntax:
```
<tagname> Content goes here... </tagname>
```

Example:
```
<h1>Welcome to HSR Hi-Tech Solutions.</h1>
```
### Nested HTML Elements

HTML elements can be nested.

All HTML documents consist of nested HTML elements.

```
<!Doctype html>
<html>
    <head>
        <title>Document</title>
    </head>
    <body>
        <h1>Heading 1</h1>
    </body>
</html>
```

**Note:** Never skip the end tag, If you do so then it will display content incorrectly.

### Empty HTML Elements

HTML elements with no content are called empty elements

So it do not have any end tag.

```
<img src="" alt="">
```

**Note:** HTML tags are not case sensitive.

e.g, You can use ```<P>``` or ```<p>```

My recommendation is always use lowercase characters for your HTML elements.


## HTML Attributes

HTML attributes provide additional information about HTML elements.

- All HTML elements can have attributes
- Attributes provide additional information about elements
- It is always specified in the start tag
- It come in name/value pair like name="value"
- For providing value to name you can use either single quote or double quote