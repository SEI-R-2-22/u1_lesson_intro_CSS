# Introduction To CSS

![css-image](https://www.tutorialrepublic.com/lib/images/css-illustration.png)

## Overview

So far we've learned how to set up and structure a HTML file. Now we'll make it look pretty! This an introductory lesson to CSS. We'll touch on very basic topics ranging from positioning to coloring!

## Objectives

- Learn how to link stylesheets
- Learn how to position elements
- Learn parent child relationships
- Learn css specificity

## What You'll Be Building

![final](Capture.png)

## Getting Started

- Fork and Clone this repository
- Open this lesson in your code editor
- Open the `index.html` file in your browser (Refer to the prior lesson on how to do so)

## What Is CSS

CSS stands for `cascading style sheets`. This means that when the file is read, it is being read from top to bottom. (We'll see how this works in just a bit)

> CSS describes how HTML elements are to be displayed on screen, paper, or in other media
>
> CSS saves a lot of work. It can control the layout of multiple web pages all at once

### Why CSS

From W3Schools:

> HTML was NEVER intended to contain tags for formatting a web page!
>
> HTML was created to describe the content of a web page, like:
>
> - `<h1>This is a heading</h1>`
>
> - `<p>This is a paragraph.</p>`
>
> When tags like `<font>`, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.
>
> To solve this problem, the World Wide Web Consortium (W3C) created CSS.
>
> The style definitions are normally saved in external .css files.
>
> With an external stylesheet file, you can change the look of an entire website by changing just one file!

## Applying Some Flair To Our HTML

You've been provided an `index.html` file, the contents may be familiar to you, we built it in the previous lesson!

First things first, let's create a `styles.css` file in this lesson folder.
You can do this by either using the `touch` command:

`touch styles.css`

Or by using the new file button in VSCode.

### Linking Our Stylesheet

In order for our `styles.css` file to be used by our html file, we need to link the two of them together. We can accomplish this by using a `link` tag in our `index.html`.

Open your `index.html`, add the following to the head section in the html file:

```html
<link rel="stylesheet" href="./styles.css" />
```

**NOTE**: Place this tag before the `title` in the html file.

Your `head` section should look like the following:

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="./styles.css" />
  <title>Document</title>
</head>
```
