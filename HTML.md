# [[HTML]]

# HTML Cheatsheet
## Tags
Div Section
```html
<div>Block Element</div>
```
Headings
```html
<h1>Page Title</h1>
<h2>Subheading</h2>
<h3>Tertiary Heading</h3>
<h4>Quaternary Heading</h4>
<h5></h5>
<h6></h6>
```
Paragraph
```html
<p style="text-align: center;">text</p>
```
Image
```html
<img src="/demo.jpg" alt="description" height="48" width="100" />
```
Outbound Links
```html
<a href="https://google.com/" target="_blank" rel="nofollow">Click here</a>
```
Mailto Link
```html
<a href="mailto:me@ruwix.com?Subject=Hi%20mate" target="_top">Send Mail</a>
```
Inner Anchor (jump to section on page)
```html
<a href="#footer">Jump to footnote</a>
<br />
<a name="footer"></a>Footnote content
```
Bold Text
```html
<strong>Bold text</strong>
```
Italic Text
```html
<em>Italic text</em>
```
Underlined Text
```html
<span style="text-decoration: underline;">Underlined text</span>
```
Iframe
```html
<iframe src="link.html" width="200" height="200">
</iframe>
```
Abbreviation
```html
<abbr title="Hypertext Markup Language">HTML</abbr>
```
Comment
```html
<!-- HTML
Comment -->
```
Horizontal Line
```html
<hr />
```
Line Break
```html
<br />
```
Quotation
```html
<q>Success is a journey not a destination.</q>
<blockquote cite="https://ruwix.com/">
The Rubik's Cube is the World’s best selling puzzle toy.
</blockquote>
```
Video
```html
<video width="200" height="150" controls>
<source src="vid.mp4" type="video/mp4">
<source src="vid.ogg" type="video/ogg">
No video support.
</video>
```
Audio
```html
<audio controls>
<source src="sound.ogg" type="audio/ogg">
<source src="sound.mp3" type="audio/mpeg">
No audio support.
</audio>
```
## Structures
Table
```html
<table><caption>Phone numbers</caption>
<thead>
<tr>
	<th>Name</th>
	<th colspan="2">Phone</th>
</tr>
</thead>
<tbody>
<tr>
	<td>John</td>
	<td>577854</td>
	<td>577855</td>
</tr>
<tr>
	<td>Jack</td>
	<td>577856</td>
	<td>577857</td>
</tr>
</tbody>
<tfoot>
<tr>
	<td>&nbsp;</td>
	<td>Personal</td>
	<td>Office</td>
</tr>
</tfoot>
</table>
```
Unordered List
```html
<ul>
<li>First</li>
<li>Second</li>
<li>Third</li>
</ul>
```
Definition List
```html
<dl>
<dt>HTML</dt>
<dd>Hypertext Markup Language</dd>
<dt>CSS</dt>
<dd>Cascading Style Sheets </dd>
</dl>
```
Form
```html
<form action="/action.php" method="post">
Name: <input name="name" type="text" /> <br /> 
Age: <input max="99" min="1" name="age" step="1" type="number" value="18" /> <br />
<select name="gender">
<option selected="selected" value="male">Male</option>
<option value="female">Female</option>
</select><br /> 
<input checked="checked" name="newsletter" type="radio" value="daily" /> Daily <input name="newsletter" type="radio" value="weekly" /> Weekly<br />
<textarea cols="20" name="comments" rows="5">Comment</textarea><br />
<label><input name="terms" type="checkbox" value="tandc" />Accept terms</label> <br />
<input type="submit" value="Submit" />
</form>
```
## Attributes
Syntax
```html
<tag attributename="value" />
<!-- lowercase attributes, quote values -->
```
Global Attributes
```html
<!-- accesskey, class, contenteditable, data-*, dir, draggable, hidden, id, lang, spellcheck, style, tabindex, title -->
<div id="demo" class="big" dir="ltr" lang="en" 
style="color: red;" tabindex="0" title="Tooltip" 
contenteditable="true" spellcheck="true" 
data-htmlcheat="99">Hello World!</div>
```
Internalization: dir, lang, xml:lang
```html
<html lang="en-US">
...
<p dir="rtl">Right to left (Arabic)</p> 
...
</html>
```
Link: download, href, hreflang, media, rel, target, type
```html
<a href="https://htmlg.com/" target="_blank" rel="external" hreflang="en" type="text/html">Link</a>
```
Image: src, alt, height, ismap, longdesc, srcset, usemap, width
```html
<img src="/demo.jpg" alt="description" height="48" width="100" longdesc="desc.txt" />
```
All Attributes
```html
accept <!-- form, input -->
accept-charset <!-- form -->
accesskey <!-- Global attribute -->
action <!-- form -->
align <!-- applet, caption, col, colgroup, hr, iframe, img, table, tbody, td, tfoot , th, thead, tr -->
alt <!-- applet, area, img, input -->
async <!-- script -->
autocomplete <!-- form, input -->
autofocus <!-- button, input, keygen, select, textarea -->
autoplay <!-- audio, video -->
autosave <!-- input -->
bgcolor <!-- body, col, colgroup, marquee, table, tbody, tfoot, td, th, tr -->
buffered <!-- audio, video -->
challenge <!-- keygen -->
charset <!-- meta, script -->
checked <!-- command, input -->
cite <!-- blockquote, del, ins, q -->
class <!-- Global attribute -->
code <!-- applet -->
codebase <!-- applet -->
color <!-- basefont, font, hr -->
cols <!-- textarea -->
colspan <!-- td, th -->
content <!-- meta -->
contenteditable <!-- Global attribute -->
contextmenu <!-- Global attribute -->
controls <!-- audio, video -->
coords <!-- area -->
data <!-- object -->
data-* <!-- Global attribute -->
datetime <!-- del, ins, time -->
default <!-- track -->
defer <!-- script -->
dir <!-- Global attribute -->
dirname <!-- input, textarea -->
disabled <!-- button, command, fieldset, input, keygen, optgroup, option, select, textarea -->
download <!-- a, area -->
draggable <!-- Global attribute -->
dropzone <!-- Global attribute -->
enctype <!-- form -->
for <!-- label, output -->
form <!-- button, fieldset, input, keygen, label, meter, object, output, progress, select, textarea -->
formaction <!-- input, button -->
headers <!-- td, th -->
height <!-- canvas, embed, iframe, img, input, object, video -->
hidden <!-- Global attribute -->
high <!-- meter -->
href <!-- a, area, base, link -->
hreflang <!-- a, area, link -->
http-equiv <!-- meta -->
icon <!-- command -->
id <!-- Global attribute -->
integrity <!-- link, script -->
ismap <!-- img -->
itemprop <!-- Global attribute -->
keytype <!-- keygen -->
kind <!-- track -->
label <!-- track -->
lang <!-- Global attribute -->
language <!-- script -->
list <!-- input -->
loop <!-- audio, bgsound, marquee, video -->
low <!-- meter -->
manifest <!-- html -->
max <!-- input, meter, progress -->
maxlength <!-- input, textarea -->
media <!-- a, area, link, source, style -->
method <!-- form -->
min <!-- input, meter -->
multiple <!-- input, select -->
muted <!-- video -->
name <!-- button, form, fieldset, iframe, input, keygen, object, output, select, textarea, map, meta, param -->
novalidate <!-- form -->
open <!-- details -->
optimum <!-- meter -->
pattern <!-- input -->
ping <!-- a, area -->
placeholder <!-- input, textarea -->
poster <!-- video -->
preload <!-- audio, video -->
radiogroup <!-- command -->
readonly <!-- input, textarea -->
rel <!-- a, area, link -->
required <!-- input, select, textarea -->
reversed <!-- ol -->
rows <!-- textarea -->
rowspan <!-- td, th -->
sandbox <!-- iframe -->
selected <!-- option -->
size <!-- input, select -->
slot <!-- Global attribute -->
span <!-- col, colgroup -->
spellcheck <!-- Global attribute -->
src <!-- audio, embed, iframe, img, input, script, source, track, video -->
start <!-- ol -->
step <!-- input -->
style <!-- Global attribute -->
tabindex <!-- Global attribute -->
target <!-- a, area, base, form -->
title <!-- Global attribute -->
type <!-- button, input, command, embed, object, script, source, style, menu -->
usemap <!-- img, input, object -->
value <!-- button, option, input, li, meter, progress, param -->
width <!-- canvas, embed, iframe, img, input, object, video -->
wrap <!-- textarea -->
```
## Blank Page
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Page Title</title>
<meta name="description" content="Roughly 155 characters">
<link rel="stylesheet" type="text/css" href="mystyle.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
<script src="script.js"></script>
</head>
<body>
<!-- Content -->
</body>
</html>
```
## .htaccess
Force HTTPS
```
html
RewriteEngine on
RewriteCond %{HTTPS} !on
RewriteRule (.*) https://%{HTTP_HOST}%{REQUEST_URI}
```
Force www
```html
RewriteEngine on
RewriteCond %{HTTP_HOST} ^htmlg\.com [NC]
RewriteRule ^(.*)$ http://www.htmlg.com/$1 [L,R=301,NC]
```
Force non-www
```html
RewriteEngine on
RewriteCond %{HTTP_HOST} ^www\.htmlg\.com [NC]
RewriteRule ^(.*)$ http://htmlg.com/$1 [L,R=301]
```
Custom Error Pages
```html
ErrorDocument 500 "Sorry, something went wrong!"
ErrorDocument 401 https://htmlg.com/404/
ErrorDocument 404 404error.html
```
Redirect Entire Site
```html
Redirect 301 / https://htmlg.com/
```
Permanent Page Redirect
```html
Redirect 301 /oldlink.html https://htmlg.com/help/
Redirect 301 /oldlink https://htmlg.com/about/
```
Alias Directory
```html
RewriteEngine On
RewriteRule ^source_directory/(.*) target_directory/$1
```
Remove .php Extension
```html
RewriteEngine On
RewriteCond %{SCRIPT_FILENAME} !-d
RewriteRule ^([^.]+)$ $1.php [NC,L]
```
Block IP Address
```html
Order deny,allow
Allow from all
Deny from 123.123.123.123
Deny from 123.123.123.123
```
Allow Access From Only One IP
```html
Require all denied
Require ip 123.123.123.123
```
## Robots.txt
Example
```html
User-agent: *
Disallow: /don't-index-this-folder/
Sitemap: https://htmlcheatsheet.com/sitemap.xml
```
Ban All Robots
```html
User-agent: *
Disallow: /
```
## Head Tags
```html
<!doctype html>
<html lang="en" class="no-js">
<head>
<meta charset="utf-8">
<meta http-equiv="x-ua-compatible" content="ie=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="canonical" href="https://htmlcheatsheet.com/" />
<title>HTML CheatSheet</title>
<meta name="description" content="A brief page description">
<meta name="keywords" content="html,cheatsheet" />
<meta property="fb:admins" content="YourFacebookUsername" />
<meta property="og:title" content="HTML CheatSheet" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://htmlcheatsheet.com/" />
<meta property="og:image" content="https://htmlcheatsheet.com/images/html-cheatsheet.jpg" />
<meta property="og:description" content="A brief page description" />
<link rel="apple-touch-icon" href="apple-touch-icon.png">
<link rel="alternate" hreflang="es" href="https://htmlcheatsheet.com/spanish/" />
<link rel="stylesheet" href="/styles.css">
<script src="/script.js"></script>
</head>```
##  HTML5 Page Structure
header, nav, main, article, section, aside, footer, address
```html
<header>
<div id="logo">HTML</div>
<nav>  
<ul>
	<li><a href="/">Home</a>
	<li><a href="/link">Page</a>
</ul>
</nav>
</header>
<main role="main">
<article>
<h2>Title 1</h2>
<p>Content 1</p>
</article>
<article>
<h2>Title 2</h2>
<p>Content 2</p>
</article>
</main>
<section>
A group of related content
</section>
<aside>
Sidebar
</aside>
<footer>
<p>&copy; HTML CheatSheet</p>
<address>
Contact <a href="mailto:me@htmlg.com">me</a>
</address>
</footer>
```
## Open Graph
Open Graph
```html
<!doctype html>
<html xmlns:og="http://ogp.me/ns#">
<head>
<title>The Rock (1996)</title>
<meta property="og:title" content="Cheat Sheet" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://htmlcheatsheet.com/" />
<meta property="og:image" content="https://htmlcheatsheet.com/demo.jpg" />
```
Optional
```html
<meta property="og:audio" content="https://htmlcheatsheet.com/track.mp3" />
<meta property="og:description" content="A brief description" />
<meta property="og:determiner" content="the" />
<meta property="og:locale" content="en_US" />
<meta property="og:locale:alternate" content="es_ES" />
<meta property="og:site_name" content="HTML CheatSheet" />
<meta property="og:video" content="https://htmlcheatsheet.com/video.swf" />
```