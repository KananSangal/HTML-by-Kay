HTML - Hyper Text Markup Language.

## Basic Summary:-
Languages are popular as they have some of their popular web frameworks available on the web. For eg.:
1. For Javascript: Express, React, Angular.
2. For Java: Spring, Springboot.
3. For C++: Crow, Treefrog.

## VS Code Shortcuts:-

1. `[Cmd + Shift + P]` – To open command palette.
2. `[Cmd + P]` – To quickly search and open any file in your project folder.
3. `[Cmd + B]` – To toggle (hide/show) the left side Explorer bar to get more screen space.
4. `[Cmd + Option + I]` – To open Developer Tools / Inspect Element directly from the browser window preview.
5. `[Cmd + Option + Up/Down Arrow]` – To add multiple cursors and edit multiple lines at the same time.
6. `[Option + Up/Down Arrow]` – To move the current line of code up or down without cutting and pasting.
7. `[Shift + Option + Up/Down Arrow]` – To instantly duplicate/copy the current line of code up or down.
8. `[Cmd + F]` – To find any specific word or text inside the current file.
9. `[Cmd + Shift + F]` – To global search any word across all the files inside your opened folder.
10. `[Cmd + \]` – To split the editor screen vertically into two columns so you can see two files together.

- By default we use index.html file as the default file coz since a long time in the history, this has been the case.
- In Apache software which was used in Linux for serving webpages on a web-browser, it wa a default configuration that if no file was served, then by default it used to serve "index.html".
- In case, no index.html file is present then default.html was served. But now, everyone is on the same page and that is "index.html".

---

## Emmet Abbreviations:-

EMMET Abbreviations may not work when only a single file is opened, as in easy words, VS Code servers require space to work so a proper folder must be opened in which you should be working on a file with extension ".html".

For writing "Fast Pace Code", we need Emmet abbreviations. In some code editors, we need to add Emmet as an extension, but in VS Code it is already integrated internally. So we can use them directly. Below, we will be discussing the Emmet shortcuts efficiently: 

- `!` + `Tab` – We will get a whole boiler-plate format of our HTML file.
- `div` + `Tab` – To quickly generate a open and close `<div></div>` block.
- `Cmd` + `/` (Mac) or `Ctrl` + `/` (Windows) – To instantly comment or uncomment any selected line of code.
- `Option` + `Shift` + `F` (Mac) or `Alt` + `Shift` + `F` (Windows) – To automatically format and neatly align your messy HTML code layout.
- `div.classname` + `Tab` – To create a division with a specific class name (`<div class="classname"></div>`).
- `div#idname` + `Tab` – To create a division with a specific id name (`<div id="idname"></div>`).
- `element1>element2` + `Tab` – To nest an element inside another (e.g., `ul>li` will put a `<li>` directly inside a `<ul>`).
- `element1+element2` + `Tab` – To place elements right next to each other as siblings (e.g., `h1+p`).
- `element*N` + `Tab` – To multiply and create N number of same elements together (e.g., `li*5` will instantly give you 5 list items).
- `element{Text}` + `Tab` – To generate an element containing text directly inside it (e.g., `h1{Hello World}`).
- `p>lorem` + `Tab` – To instantly fill a paragraph with random dummy placeholder text (Lorem Ipsum) for testing designs.
- `a:link` + `Tab` – To instantly generate an anchor link tag with the default `href="http://"` attribute filled out.

---

Now, let's get back to our Basics of HTML and learning. So, YAY, let's start.
We will be discussing each topic step by step.

## 1. Headings:
1. More than markup, HTML is a syntactical and structural language. And this point matters a lot. As I guess we all know that H1 is the largest heading of all and H6 is the smallest. But, it's not where the main point lies. As we can always make H2 much larger than H1 with the help of the styling language known as "CSS".
2. So, what's the actual use of H1 to H6? It's the "Priority" that matters. Yes, you read it right. H1 is a structural language and it is used to make sure that the element inside H1 is having the highest priority of all.
3. Similarly, just to give one more example, the same happens with the footer and address tags. If we want our address to be there in the bottom-most of the screen, we can do this easily with the CSS styling but again if we use the `<address>` tags inside the `<footer>` tags, the HTML will automatically do this for us.

---

### 2. Structure:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
  </head>

  <body>
  </body>
</html> 
```

- `<!DOCTYPE html>` - Sometimes, we need to tell browser on which type of file we are working on.
- `<html>` & `</html>` - Basic structure to start and end any html file.
- `lang="en"` - We told we are writing in English.
- `<head>` 
   - This contains all the info which is important but not directly visible on the webpage except two things, i.e. the "Title" and the "Favicon", which are both visible on the tabs of the browser. The icon and the site name or a crisp description.
   - Sometimes, `<meta>` tags are placed inside the `<head>` tag to tell the browser about our webpage and make it easier to be ranked on the Browser. You can learn about `<meta>` tags in detail by having a look at its [documentary](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/meta).
- `<body>` - Here goes all the info that is visible on the webpage.

> Just a quick note: HTML can work even without closing the tags but it is not advised and not considered as a good practice at all.

---

### 3. Stand-alone tags:
Some tags do not need a closing tag with a slash `/`. But, for better practice you can write `/>` instead of `>`. The following are some of the self-closing stand-alone tags in HTML:
- `<br>` – To shift to a new line.
- `<img>` – To insert an image.
- `<hr>` – To insert a horizontal straight line (divider).
- `<input>` – To create an input field (text box, checkbox, button etc) inside forms.
- `<meta>` – To store hidden data about the webpage (like character set, page description for SEO).
- `<link>` – To connect external files (like attaching a CSS stylesheet to an HTML file).
- `<source>` – To define multiple media files inside `<audio>` or `<video>` tags.
- `<embed>` – To plug in external interactive resources or apps (like PDF viewers, flash files).
- `<param>` – To set specific parameters/settings for embedded plugins inside `<object>`.
- `<area>` – To create clickable regions inside an image map.
- `<base>` – To set a default target URL for all hyperlinks on the page.
- `<col>` – To control specific column properties inside a `<table>`.
- `<track>` – To add timed subtitles, captions, or text tracks to videos.
- `<wbr>` – To suggest a safe position where the browser can break a long word onto a new line if needed.

---

### 4. Attributes:
These are the tags which are used to determine properties of their parent tags. There are three types of attributes present which are:
1. Global Attributes - These can be applied to almost all HTML elements.
Common examples include id, class, style, title, data-*, hidden, lang, and dir.
2. Multi-Tag Attributes -
3. Single-Tag Attributes - 