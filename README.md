This is a small project relate to my CV and may or may not be used for future job application

## 1. Command

```
<!DOCTYPE html>
```

basically this is the first thing you must write dowm on every main script as a declaration. It's to tell the web browser which version of HTML pages is written in.

<hr>

```
<html lang="en">
```

IT just to tell the web browser which langage this website is based on it can be spanish chinese etc.

<hr>

```
<head> </head>
```

The \<head> provides crucial information to browsers and search engines without appearing on the actual page. It contains essential data, including the page title, character set, styles, links to scripts, and SEO information. IN short is the Brain of the whole html.

<hr>

```
<meta> and <title>
```

This part is quite confusing but im trying to be a blunt as possible meta is a data that relate to how can the website be search by the engine or in short something call SEO **( search engine optomization )** and this will help google or bing or any other engine's bot or search algorithm find the website relate to what the User is searching for. It is like a library managment and if the user is searching for CV and the title name is also CV the bot might hand out your website to the user first according to the user searching prompt.

<hr>

```
<meta charset="UTF-8">
```

**UTF-8** is the universal standard because it supports virtually every character, including symbols and emojis.

**Placement**: It should be the very first tag inside your <head>. This ensures the browser knows how to decode the text before it starts reading the title or CSS.

<hr>

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

<meta name="viewport" content="...">This is your most powerful tool for mobile responsiveness. Beyond the standard setup, you can use these specific attributes for different purposes :

| Attribute          | Purpose           | Why use it?                                                                                                 |
| :----------------- | :---------------- | :---------------------------------------------------------------------------------------------------------- |
| width=device-width | Responsive Design | Matches the webpage width to the physical screen width.                                                     |
| initial-scale=1.0  | Standardization   | Sets the default zoom to 100% on load.                                                                      |
| viewport-fit=cover | Modern Display    | Expands your site to fill the entire screen on phones with "notches" (like modern iPhones).                 |
| user-scalable=no   | Locking Zoom      | Prevents users from pinching to zoom; use this only if you want the site to feel exactly like a mobile app. |

<Hr>
there may be more that is still missing. 
<hr>
**NOTE** : This is for my own basic understanding with my own research with google and AI to assist while writing down this documentation.

```
<body> </body>
```

It is used to contain all of the content that will be shown on the user screen.

There can only be one \<Body> on each HTML file.

It contains headings, paragraphs, images, hyperlinks, tables, lists, and any other visible elements

    <main>

The `<main>` tag is a Semantic HTML element used inside the `<body>`. It tells the browser and search engines exactly where are all the info on your page.

It specifies the unique, primary content of the document.

Exclusions: It should not contain content that is repeated across multiple pages, such as site logos, navigation bars, search bars, or footer information.

Quantity: There should be only one non-hidden `<main>` element per page.

CS/SEO Benefit: Screen readers (for accessibility) use the `<main>` tag as a "shortcut." Users can press a key to skip the navigation and jump directly to the important content.

<!-- didnt know i could just select the text and click tap to pull out the code block and i just dicover it accidentally man i have so much more to learn and i am sure i cannot rememeber all of these>
