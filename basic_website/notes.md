# Notes
use `index.html` for root file in an HTML website.

`<!DOCTYPE html>` dictates the document type to the webbrowser

Nested tags are indented to help visually show the relationship between the tags. Outer tags are referred to as parent tags, inner tags are referred to as child tags.
```HTML
<parent>
    <child>
        <grand-child></grand-child>
    </child>
</parent>

```

Within tags are things referred to as attributes (or properties), that define more information about a tag. Within the example below, information about the charset of the webpage is carried within a tag attribute.
```HTML
<meta charset="UTF-8">
```

Information within the document is placed by the order that tags are placed from top to bottom.
```HTML
<p>This text would appear first</p>
<p>This text would appear second</p>
<p>This text would appear third</p>
```

HTML doesn't care about additional whitespace or returns in the document.
```HTML
<p>Text</p>
<p>Text</p>
```
The above is the same as the below in terms of the viewable content on the page.

```HTML
<p>Text</p>



<p>Text</p>
```
## Container Tags
`<html>...</html>` dictates the html container for the website. All HTML tags and code go in this tag.

`<head>...</head>` dictates the title of the document, the description of the document and overall data of the document. Can be used to define other attributes like images in the document.

`<body>...</body>` dictates the actual webpage content.

## Head Tags
Used to define metadata about the website.

`<meta>` is a basic empty meta tag.

`<meta charset="UTF-8">` sets the character set of the webpage to UTF-8, a common character set for websites.

`<meta name="description" content="A basic description of my website">` Sets the description of the website and makes it easier for search engines to find information about the website.

## Body Tags
`<title>Text Here</title>` Sets the title of the website that appears at the top of the browser.

`<h1>...</h1>` is a large header tag. Numbered 1-6, they decrease in size and overall scale as the header # increases.

`<p>...</p>` dictates basic paragraph content.

`<b>...</b>` Makes a set of text within the tag bold. 

`<i>...</i>` Makes a set of text within the tag italicized.

`<big>...</big>` Makes a set of text within the tag a bit bigger in font.

`<small>...</small>` Makes a set of text within the tag a bit smaller in font.

### Single Tags
Single tags are tags that only have one tag, and are formatted a bit differently then normal tag. Sometimes the `/` at the end of the tag can be removed.

`<br/>` Creates a line break in the webpage.

`<hr/>` Creates a horizontal rule (line) across the webpage.


## Terminology
