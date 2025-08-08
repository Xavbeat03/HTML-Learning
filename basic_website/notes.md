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

`<sub>...</sub>` Makes a set of text within the tag a subscript.

`<sup>...</sup>` Makes a set of text within the tag a superscript.

### Single Tags
Single tags are tags that only have one tag, and are formatted a bit differently then normal tag. Sometimes the `/` at the end of the tag can be removed.

`<br/>` Creates a line break in the webpage.

`<hr/>` Creates a horizontal rule (line) across the webpage.

## Comments
Comments are useful to give other developers advice about your HTML file.

Its common to explain within the comment, why you've commented something out.

Comments should be used sparingly, and they shouldn't be excessively long. Comments aren't an excuse for messy code. Let the HTML speak for itself and focus on writing clean and readable code.

To create a comment:
`<!--text here-->`

It can also be multiline:
```HTML
<!--
Text here
-->
```

## Styling HTML
Within a body and container tags you can apply different styling to the text and containers. Specific styling on further nested components override previous styling made on the container. You can also apply the color and background-color at the same time to a tag, as long as they both stay within the same style property.

### Properties
`style="color:<color>;"` Applies a different text color to the text within the tag or to the text contained within the container.

`style="background-color:<color>;"` Applies a background color to the text within the tag or the area of the website contained within the container.

`style="color:<color1>; background-color:<color2>;"` Applies a text color and background color like the above, but on the same tag.

For finding the allowed colors you can use [this website](https://www.w3schools.com/cssref/css_colors.php) as a resource.

## Formatting
Typically 3 distinct sections of a website: the header, the body, and the footer. The header is at the top, typically has branding and some menuing. The main is in the middle, and has the main content and text of the website. The footer is at the bottom and might have some more branding and linkage.

Typically websites are formatted with one main header 1, multiple header 2's for different sections, and then a header 3 for denoting different points of your header 2's.

`<header>...</header>` Typically has the `<body>` tag as a parent. It sits at the top of the page.

`<main>...</main>` Typically has the `<body>` tag as a parent. It sits in the middle of the page.

`<footer>...</footer>` Typically has the `<body> tag as a parent. It sits at the bottom of the page.

`<nav>...</nav>` Used for building a navigation bar or list structurally. Navigational lists or items go here. Typically in the header.

`<article>...</article>` If you have an article on your website, you'd want to use the article tag to denote that. Useful for SEO.

`<section>...</section>` If you have different sections of your article or of your website then you can divide them up with the section container tag. You typically want a header for the section.

`<aside>...</aside>` Commonly used for content that's not directly related to the main content of the page. Its shown to the user but not related to the core content of the website. Common for ads.

## Linking

Linking allows you to link other websites to the webpage.

`<a href="https://google.com">This is an example link</a>` This link attribute creates a link with other text than the websites link. You can also put other html tags inside of the \<a> tag, allowing the link to be a header for example.

`<a href="https://google.com" target="_blank">This is an example link that opens to a new tag</a>` Using this tag allows you to redirect a user, while not navigating them away from your website.

`<a href="same_folder.html">Same Folder</a>` This opens a page on your website to  another page on your website, where the pages are in the same folder within the server files.

`<a href="directory/different_folder.html">Different Folder</a>` This opens a page on your website to another page on your website, where the pages are in a different folder in the server files.

`<a href="catfile.png">Cat Picture</a>` This links the user to a specific file on the website, it can be any file.

## Terminology
- Tag
- Container
