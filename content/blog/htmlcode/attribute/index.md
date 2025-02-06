---
title: HTML Attributes
summary: Hyper Text Markup Language
date: 2025-02-05
authors:
  - admin
tags:
  - HTML
  - Website
  - Markdown
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---


## HTML Attribute

  -  All HTML elements can have **attributes**
  -  Attributes provide **additional information** about elements
  -  Attributes are always specified in **the start tag**
  -  Attributes usually come in name/value pairs like: **name="value"**

### The href Attribute
The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:
```html
   <a href="https://www.siischool.jp">SIS</a> 
```

### The src Attribute

The `<img>` tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

```html
 <img src="img.jpg"> 
```

There are two ways to specify the URL in the ==src== attribute:
1. **Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.example.com/images/img.jpg".
2. **Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img.jpg".

Another attribute for `<img>` :
- width and height : specify the width and height of the image 
```html
  <img src="img.jpg" width="500" height="600">  
```
- alt : specifies an alternate text for an image, if the image for some reason cannot be displayed. 
```html
  <img src="img.jpg" alt="A Boy with a jacket">  
```
 
### The style Attribute
The `style` attribute is used to add styles to an element, such as color, font, size, and more.
 
```html
   <p style="color:red;">This is a red paragraph.</p>  
```

### The lang Attribute
to declare the language of the Web page
```html

<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>

```

## Excersice


