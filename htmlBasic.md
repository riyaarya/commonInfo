HTML

HTML is the standard markup language for creating Web pages.

HTML stands for Hyper Text Markup Language
HTML describes the structure of Web pages using markup
HTML elements are the building blocks of HTML pages
HTML elements are represented by tags
HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
Browsers do not display the HTML tags, but use them to render the content of the page

- Each element of the HTML is known as Tag

- To view the html coding of page do right click and select view page source or press cntrl+u

- Each tag has special meaning defined in W3C schema

- HTML and HTML 5 
 HTML 5 is the new version of HTML 5 which adds few more tags like canvas and all to support animation without flash, in the earlier systems flash was used to create games and animation which was then requiring flash play in your system. With the advancement in the HTML 5 with these tags these all can be achievd without flash player

 - To know if the page has been coded in HTML or HTML 5, so look for this line <!DOCTYPE html>, if the page has this line then its HTML 5 otherwise its not

- every tag should be start with <tag name> and ends with </tag name> e.g. <html></html>

 # Tags

 <html>
 this tag is the top most container which tells what ever is being written will be treated as HTML and ends with </html>

 -each html has two most basic part 
 head and body

 -head part start with <head> tag and ends with </head>

 -head tag containes basically javascript or all the linking files like for designing and other javascript libraray using <link> tag

 - body tag which contains the element which we see on the page and start with <body>

- Most used tags in body are head tag which are h1, h2,h3,h4,h5 which are all does the same but prints the text in different sizes
h1 is the bigger one and h5 is lowest and are in this order h1>h2>h3>h4>h5

- To write the paragraph we use <p> tag
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

- Text is formatter tags 
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

for the use of each see this https://www.w3schools.com/html/html_formatting.asp

- To create the link we use <a> Tag which has several attribute, the text between the <a></a> is always clickable
href - it is the location which if the this text is clicked where is should go like if we see forgot password in signup pages it uses this
target - if set it tells where to open the link in the current tab or new tab, it target is set as target="_blank" it will open the page in the new tab
for example
<a href="www.google.com">GO</a> if you click on GO it will open google in the same tab which you were seeing 
<a href="www.google.com" target="_blank">GO</a> if you click on GO it will open google in new tab 

- To include image in the page we use img tag, this is only tag which doesnot have closing like </img>
its also most used because we use image often 
<img src="pulpitrock.jpg">
its as src attribute which is the location of the image file  
to see how its working - https://www.w3schools.com/html/html_images.asp

- To create the table we use table tag and this works with combination of tr and td and tbody sometimes
<table></table> defines table now we have table which is empty unless we add values into it and to add values we have to add row wise 
tr= table row
td= table data or col
<table>
 <tr>
  <td>Value1</td
 <tr>
<table>
td is always used inside tr and tr is always used inside table and sometimes under tbody whicih is optional

see its working here - https://www.w3schools.com/html/html_tables.asp

- to create list like bullet points or ordered list we create in the doc we use <ul> and <li>, ul and li works togethere and li is always under ul
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

- <div> is the most used and common tag in html which define a section in the page or defines a block, div can contain any type of html elements excluding head, body and html tag
and div can have nested div in it means a section under section
<div>
  <div>
  </div>
</div>
take it as simliar to the { } in the coding 

- 


