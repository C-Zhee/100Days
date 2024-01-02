.md = Mardown file

adding id to divs
id="introduction"      id = name 
                    intro = value

<p> are used to make paragraphs
<span> are used inside <p> tags so the text can be shown on the next line

<em> to italicize
<strong> to bold

<br> Makes text move to next line.
Can add another to skip a space

<ul> unordered list
<ol> ordered list

<img src="lemon.jpeg"  alt="img description"/>  self closing tag

<video src="lemon.mp4" width="320" height="400" controls> controls is for play,pause, ff, rew
Add text inbetween opening and close tags incase video isn't supported

<a href="" target="blank">Learn More</a> anchor element

** Wrapping img inside an <a> tag so it can link to a site.
 <a href="https://en.wikipedia.org/wiki/Brown_bear" target="_blank"><img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" /></a>

** # must match the id clicks to work
     <ul>
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#habitat">Habitat</a></li>
      <li><a href="#media">Media</a></li>
    </ul>

<!-- Tables -->

Table
Thead
tbody
tfoot

tr table row
th table head   (must use tr before)
td table data   (must use tr before)

scope="row"     data is for a row
scope="col"     data is for a col

colspan="value"     (must used for td/th)
used if a certain cell is long

rowspan="value"     (must used for td/th)

<!-- Forms -->

<form action="/example.html" method="POST">
</form>
action = where the information is sent
method = what kind of HTTP request

<input type="text" name="username" value="Davie" id="">
type = what kind of data you want text/num
name = could be username or password
value = value shown on the form bar

<label for=""></label>
Will show up in front of the input bar. **Needs to be same value as input id
** Labels should go on top of the input

