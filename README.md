# Welcome to Wholesale Project

## Software Installs

MAMP is a free, local server environment that can be installed under macOS and Windows.
[Download](https://www.mamp.info/en/)

Sublime Text editor for PC/Mac
[Download](https://www.sublimetext.com/)

Sublime Merge for Git Client
[Download](https://www.sublimemerge.com/)

### README: Git

[Git](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

### The Keyboard

![](https://cdn.glitch.com/a813cfc9-cd0e-4e81-9725-c22074e7a34a%2Fkeyboard.svg?v=1591896216657)

The 104-key US QWERTY layout

### Keyboard Symbols

#### HTML

- `<!-- my comment statement in HTML -->` HTML Comment
- `!` exclamation mark
- `<` less than
- `>` greater than
- `/` backslash
- `=` equal
- `' '` single quote
- `" "` double quote
- `-` dash / hyphen
- `_` underscore
- `;` semicolon

#### CSS

- `/* my comment statement in CSS */` CSS Comment
- `@` the at sign used for `@import 'normalize.css';`
- `(` open parenthesis
- `)` close parenthesis
- `.` period
- `#` **pound / number sign** or hashtag
- `{ }` curly brace / bracket
- `{` open curly brace / open bracket
- `}` close curly brace / close bracket
- `-` dash / hyphen
- `_` underscore
- `' '` single quote
- `" "` double quote
- `:` colon
- `;` semicolon

### Keyboard shortcuts for Windows

Applies to: [Windows 10 Windows 8.1 Windows 7](https://support.microsoft.com/en-us/help/12445/windows-keyboard-shortcuts)

### Keyboard shortcuts for Mac

By pressing certain key combinations, you can do things that normally need a mouse, trackpad, or other input device. [Learn more](https://support.apple.com/en-us/HT201236)

## Your Project Folder

### ← README.md

That's this file, where you will find class notes and homework assignments

### Create a README.md: Basic writing and formatting syntax

Create sophisticated formatting for your prose and code on GitHub with simple syntax.
[Learn more](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

### ← index.html

Your introduction for the content of your website.

## HTML: Sample Code

_HTML stands for Hypertext Markup Language_ and that it is the standard markup language for the creation of web pages.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Web Development 101</title>
</head>
<body>
  <h1>Week One: HTML Sample Code</h1>
  <p>This class is awesome!</p>
</body>
</html>
```

### Placeholder text and images

- [Lorem Ipsum](https://www.lipsum.com/) Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on meaningful content.
- [Lorem Picsum](https://picsum.photos/) Lorem Ipsum for photos.

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Simple HTML and Inline CSS</title>
</head>
<body>
  <h1 style="background-color: yellow; color: black; text-align:center;">My First HTML with Inline CSS</h1>
  <img src="https://picsum.photos/300" alt="Lorem Picsum" style="display: block; margin: 5% auto;">
  <div class="container" style="border: 3px solid red;">
    <p style="background-color: green; color: yellow; padding: 10px 5px 20px 5px; margin: 20px 20px 20px 20px;">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
  </div>
</body>
</html>
```

### Sample Code using HTML5 tags

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Web Development 101</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
  </head>
  <body>
    <header>
      <nav>
        <menu>
          <ul>
            <li>About</li>
            <li>Portfolio</li>
            <li>Resume</li>
            <li>Contact</li>
          </ul>
        </menu>
      </nav>
    </header>
    <aside>
      <div class="sidebar">
        <h2>Sidebar Header</h2>
        <p>This is the sidebar content.</p>
      </div>
    </aside>
    <main>
      <div class="site-content">
        <h1>Week One: HTML Sample Code</h1>
        <p>This class is awesome!</p>
      </div>
    </main>
    <footer>
      <p>&copy 2020 <br/> Author: First and Last Name</p>
    </footer>
  </body>
</html>
```

### ← style.css

CSS files add styling rules to your content.

## CSS: Three Types

### Inline CSS

```
<p style="color: red;">Add color to text</p>
```

### Internal CSS

```
<head>
  <style type="text/css">
    p {
      color: red;
    }
  </style>
</head>
```

### External CSS

```
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

## CSS: Sample Code

![](https://cdn.glitch.com/a813cfc9-cd0e-4e81-9725-c22074e7a34a%2Fcss-selector.gif?v=1590804079831)

_CSS stands for Cascading Style Sheets_ and it represents the design conventions that are applied to the display of HTML elements on screen, paper and other media

```
body {
    background-color: powderblue;
}
h1 {
    color: white;
    text-align: center;
}
p {
    font-family: Verdana;
    font-size: 20px;
}
```

### ← script.js

If you're feeling fancy you can add interactivity to your site with JavaScript.

### ← assets

Drag in `assets`, like images or music, to add them to your project

## Class Resources

- [The Essential Meta Tags for Social Media | CSS-Tricks](https://css-tricks.com/essential-meta-tags-social-media/)

- What is a [Favicon](https://en.wikipedia.org/wiki/Favicon)

  - [How to Add a Favicon to your Site](https://www.w3.org/2005/10/howto-favicon)

- [Normalize.css](https://necolas.github.io/normalize.css/) makes browsers render all elements more consistently and in line with modern standards.

- Learn how to create [tabs](https://www.w3schools.com/howto/howto_js_tabs.asp) with CSS and JavaScript.

- The [World Wide Web Consortium (W3C)](https://www.w3.org/) is an international community that develops open standards to ensure the long-term growth of the Web.

- [Font Awesome](https://fontawesome.com/) vector icons and social logos on your website.

- Creating wireframs with [Adobe XD](https://www.adobe.com/au/creativecloud/business/enterprise/how-to-wireframe-xd.html)

## Homework Assignments

### Assignment 2

- Find the HTML and CSS symbols on your keyboard
  - Create a file called `code_example.txt`
  - Provide examples on how the symbols are used in code.
- Code 3 website pages using HTML5 and CSS and use `nav` to connect the pages.
- Use **external font** to heading `<h1> to <h6>` tags and add social media icons
  - https://www.w3schools.com/cssref/css_websafe_fonts.asp
  - https://fonts.google.com/
  - https://fonts.adobe.com/
  - https://www.fontsquirrel.com/
  - https://fontawesome.com/start
- BONUS
  - Review the use of **CSS Flexbox** `display: flex;`. [Learn More](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - Create a **one wireframe page** using Adobe XD [watch tutorial video](https://www.youtube.com/watch?v=jUqbd0em1js)
    - [Learn how](https://helpx.adobe.com/xd/help/share-designs-prototypes.html) to share your design

### Assignment 3

- Review the use of **CSS Flexbox** `display: flex;`. [Learn More](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

  - [HTML <div> Tag](https://www.w3schools.com/tags/tag_div.asp)
  - [CSS Flexbox Layout Module](https://www.w3schools.com/css/css3_flexbox.asp)
  - [What Happens When You Create A Flexbox Flex Container?](https://www.smashingmagazine.com/2018/08/flexbox-display-flex-container/)

- Create HTML and CSS markup for the below design
  ![](https://cdn.glitch.com/a813cfc9-cd0e-4e81-9725-c22074e7a34a%2FWeb%201920%20%E2%80%93%202%20Column%20Grid%20%E2%80%93%20Text.jpg?v=1591997299184)
