<h1>Learn HTML by building a cat photo app </h1>

HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage.

In this course, you'll learn the most common HTML tags by building your own cat photo app.

________________________________________________________________________________________

<h3>Step 1 </h3>

<html>
  <body>
<p> </p>HTML elements have opening tags like < h1 > and closing tags like < /h1 >.</p>
The text for an element goes between its opening and closing tags.
Find the h1 element and change its text to:

CatPhotoApp

 < h1 >Hello World< /h1 >

  </body>
</html>

<html>
  <body>
<h3>Step 2</h3>
The h1 through h6 heading elements are used to signify the importance of content below them. 
The lower the number, the higher the importance, so h2 elements have less importance than h1 elements. 
Only use one h1 element per page and place lower importance headings below higher importance headings.

Below the h1 element, add an h2 element with this text:

Cat Photos

</html>
  </body>

<h3>Step 3</h3> 
The p element is used to create a paragraph of text on websites. 
Create a p element below your h2 element and give it the following text:

See more cat photos in our gallery.

<h3>Step 4</h3>
Commenting allows you to leave messages without affecting the browser display. 
It also allows you to make code inactive. A comment in HTML starts with 
< !--, contains any number of lines of text, and ends with -- >. For example, 
the comment < !-- TODO: Remove h1 -- > contains the text TODO: Remove h1.

Add a comment above the p element with this text:

TODO: Add link to cat photos
Your comment should be above the p element. You have them in the wrong order.

< !-- TODO: Add link to cat photos -- >

< p >See more cat photos in our gallery.< /p >

<h3>Step 5</h3>
HTML5 has some elements that identify different content areas. 
These elements make your HTML easier to read and help with Search Engine Optimization
(SEO) and accessibility.
Identify the main section of this page by adding a <main> opening tag before the h1
element, and a </main> closing tag after the p element.

< main >  

    < h1 >CatPhotoApp< /h1 >
    < h2 >Cat Photos< /h2 >
    < !-- TODO: Add link to cat photos -- >
    < p >See more cat photos in our gallery.< /p >
    
< /main >

<h3>Step 6</h3>
In the previous step, you put the h1, h2, comment, and p elements inside the main element. 
This is called nesting. Nested elements should be placed two spaces further to the right of
the element they are nested in. This spacing is called indentation and it is used to make HTML 
easier to read.

The h1 element, h2 element and the comment are indented two spaces more than the main element
in the code below. Use the space bar on your keyboard to add two more spaces in front of the 
p element so that it is indented properly as well.

<h3>Step 7</h3>
<p>You can add images to your website by using the img element. img elements have an opening tag without
a closing tag. A tag for an element without a closing tag is known as a self-closing tag.
Add an img element below the p element. At this point, no image will show up in the browser. </p>


<p>< p >See more cat photos in our gallery.< /p > </p>

< img/ >

<h3>Step 8</h3>
HTML attributes are special words used inside the opening tag of an element to control 
the element's behavior. The src attribute in an img element specifies the image's URL 
(where the image is located).

Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

< img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg" >
Inside the existing img element, add an src attribute with this URL: https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg: 

< img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg"/ >

<h3>Step 9</h3>
All img elements should have an alt attribute. The alt attribute's text is used for screen
readers to improve accessibility and is displayed if the image fails to load. 
or example, < img src="cat.jpg" alt="A cat" > has an alt attribute with the text A cat.

Inside the img element, add an alt attribute with this text:

A cute orange cat lying on its back

< img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute 
  orange cat lying on its back"/ >

<h3>Step 10</h3>
You can link to another page with the anchor (a) element. For example, < a href='https://freecodecamp.org'></a > 
would link to freecodecamp.org.
Add an anchor element after the paragraph that links to https://freecatphotoapp.com. 
At this point, the link won’t show up in the preview.

< p >See more cat photos in our gallery.< /p > 
< a href='https://freecatphotoapp.com'>< /a >




  
