# refernce-website
1. Naming convention for all filenames, paths and folders
- All files should be written in lower case with no spaces or dashes 
'index.html' 

2. Best practices for commit messages

3. What is HTML?
- HTML is the standard language used to discribe the content on a web browsers.

4. Proper syntax for HTML tags.
- The proper syntax for HTML tags are <> and </>. The starting tag is <> and the end of the tag is </>.

5. Explain or demonstrate commonly used html tags/elements:

- headings: h1-h6
   <h1>This is an example of a heading.</h1>
   - Heading tags are used to mark titles/section titles. The h1 tag is for the most impart heading and largest heading. The h6 tag is for the least import and smallest heading on the page.
 

- p
   <p>This is an example of a paragraph</p>
   - The <p></p> tags define a parapgraph within the text. The paragraph creates a margin automatically around it to define it.

- lists: ul, ol, dl
<ul>
   <li>Unordered list example. </li>
    <li>Unordered list example.</li>
</ul>

<ol>
    <li>1. Ordered list example. </li>
    <li>2.  Ordered list example.</li>
</ol>

<dl>
 <dt>Term or name</dt>
 <dd>Description of term</dd>
 <dd>Description of term</dd>
<dl>

- a
  <a href="Link Text"></a>
  The  <a href=""></a> tag is used to create a hyperlink. The <a> tag and href attribute, which shows to the link of the content.

- img
  <img src="" alt="">
  - The <img src="" alt=""> tag is used to place images within in the website. This tag links the image to the HTML document. The tag provide the image location and an alternative title for the image.
- q
   <q>Example of quote</q>
   The <q></q> is a tag used to mark quotes that are within other elements such as paragraphs.

- blockquote:
  <blockquote>Example of blockquote</blockquote>
  The blockquote tag is used for large stand alone quotes.

- Cite:
  <cite>Example of cite</cite>
  The cite tag is used to mark the source of the quote. 

- em
  <em>Empahsize example.</em>
  The em tag creates emphasis.

- strong
  <strong>Example of strong</strong>
  The strong tag is used to create empasis and importance to the content.

- b
   <b>Examlpe of keywords.</b>
   The b tag is used for keywords.

- i
  <i>Example of i tag.</i>
  The i tag is used when the content is a technical term or in a different language.

- small
  <small>Example of small.</small>
  The small tag is used to reduce the size and emphasis on content.

6. Explain block Elements and also explain the list of block elements and why they are used from below:
    - Block elements are a HTML element that starts a new line on the web page and extends to the full horizontal space of its parent element.

 - html
    HTML is the standard language used to discribe the content on a web browsers.

 - head
   
 - body
   
 - header

 - nav

 - main

 - section

 - article
   
 - div

 - aside

 - footer

 - span

 - small

7. Explain why accessibility is important and also explain the accessibility properties like:
 - landmark roles: Are to help those using screen readers to jump to spacific sections on a website.
  
 - aria labels: Are accessible rich internet applications.

 - image alternative texts: Describe images using alternative text. The alternative text is used to describe the photo if it fails to download and for those who cannot see it.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
CSS is Cascading Style Sheets. CSS is the language used to control the apperance of HTML pages. A CSS file is first created in codes editor, saving the extension .css.

9. What is the difference between CSS property and value (write explanation and an example code)
CSS property is a selector. For an example, you are able to change the font style, size and colour. CSS value is the setting for the property. For example, the colour can be any colour and the font-family can be a varity of fonts.

10. Why do we use border-box property in CSS?
    The border-box property in CSS is used to create any border and padding values specifically for an element.

11. Explain different type of ways we can add spacing to an element
    The different type of ways spacing can be added to an element includes margins and padding.

12. What is the main difference between margin and padding?
    Padding displays the amount of inner space an elememt has. A margin is the whitespace available around the element.

13. What are different types of display properties?
    The different types of a display properties are flex, grid and inline-block.

14. Write a brief explanation of flexbox property.
   A flexbox is a one-dimensional layout used to arrange items in rows or columns.

15. What are different types of flexbox properties and what is the major difference between them?
    The different types of flexbox properties are flex-wrap, flex-direction, flex-flow, justify-content, align-items and align-content. The main difference between flexbox properties is the movements being arranged horizontally and vertically.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
Flexbox parent element allowa for its child elements automatically align themselves into a column or row with the auto width and height.

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
 .box{
  display: flex;
  flex-flow: row wrap;
 }
18. What is CSS grid property?
 CSS grid property sets all of the explicit and implicit grid properties in one declaration.

19. Write the parent and two sub-properties used for CSS Grid Property.
.grid{
  display: grid;
  grid-template-columns: repeat(9,1fr);
  grid-tem  grid-template-rows: repeat(4, minmax(100px, auto));
}

.item {
  display: grid;
  grid-column: 2 / 7;
  grid-row: 2 / 4;
  grid-template-columns: subgrid;
  grid-template-rows: subgrid;
}

20. What is the difference between display: flex and display: grid?
Display: flex is used for layout in one dimension in a row or column. Display: grid is used for two-dimensional layout in rows and columns at the same time.

21. What sub-property we use to divide elements in CSS Grid properties?
The sub-property we use to divide elements in CSS Grid properties is <div>.

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
.grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-column-gap: 10px;
}
Alternatively %, px or em can be used instead of fractions.

23. What is the area property in CSS grid we use for the child elements?
The area property in CSS used for child elements referrer to specific grid lines. Thes lines include grid-column-start/grid-row-start and grid-column-end/grid-row-end. The line starts where the item begins and the line ends where the item ends.

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
