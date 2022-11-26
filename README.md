# HTML Attributes

>All HTML elements can have **attributes**

>Attributes provide **additional information** about elements

>Attributes are always specified in **the start tag**

>Attributes usually come in name/value pairs like: **name="value"**

# The `HREF` Attribute

>The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

The code like this:

```html
<!DOCTYPE html>
<html>

<head>
    <title>My first hyperlink</title>

    <head>

    <body>
        <a href="https://www.google.com">Visit Google</a>
    </body>
    <html>
```

_And the optput will be like this:_

![image](https://user-images.githubusercontent.com/119107805/204103815-8c4a184b-445b-49b2-893a-0aa15f08a2d3.png)

# The SRC Attribute

>The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

The code like this:

```html
<!DOCTYPE html>
<html>

<head>
    <title>My first hyperlink</title>

    <head>

    <body>
        <img src="./README.png">
    </body>
    <html>
```
In my case,my browser will be show the notes for week 1:

_The output will be like this:_

![image](https://user-images.githubusercontent.com/119107805/204103940-21eeffd1-6a44-4c6f-b581-1862cfec37fe.png)

There are two ways to specify the URL in the `src` attribute:

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://en.wikipedia.org/wiki/HTML#/media/File:HTML5_logo_and_wordmark.svg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

Tip: It is almost always best to use relative URLs. They will not break if you change domain.

# The width and height Attributes

>The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

The code example:

```html
<!DOCTYPE html>
<html>

<head>
    <title>My first hyperlink</title>

    <head>

    <body>
        <img src="./README.png" width="500px" height="600px">
    </body>
    <html>
```

_The output will be like this:_

![image](https://user-images.githubusercontent.com/119107805/204104162-30e6e246-73fa-44c0-87da-965d60d4002e.png)

# The alt Attribute

>The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader

Code example:

```html
<!DOCTYPE html>
<html>

<head>
    <title>My first hyperlink</title>

    <head>

    <body>
        <img src="./abcd.png" alt="This server haven't this image">
    </body>
    <html>
```

_The output will be like this:_

![image](https://user-images.githubusercontent.com/119107805/204104268-dba52ed4-e007-4c2c-ac51-9dc08da40528.png)

# The style Attribute

>The `style` attribute is used to add styles to an element, such as color, font, size, and more

Code example:

```html

```

_The output will like this:_

![image](https://user-images.githubusercontent.com/119107805/204104359-412e2b35-8254-4db5-b0c3-a66bec666df7.png)
