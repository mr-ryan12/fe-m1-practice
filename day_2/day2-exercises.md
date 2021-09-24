  1.  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?  
   Ordered lists will add a list of numbers in numerical order to the content. Unordered lists include bullet points and do not represent an ordered structure of elements. Definition lists include a definition title and the actual definition displayed underneath it. 
  ```html
  <ul>
    <li>These are elements in an <strong>UN</strong>ordered list</li>
    <li>So are these</li>
    <li>More things</li>
  </ul>
  <ol>
    <li>These are elements in an ordered list</li>
    <li>So are these</li>
    <li>Even more things</li>
  </ol>
  <dl>
    <dt>Some term that needs defining</dt>
    <dd>This is the definition</dd>
  </dl>
  ```
  2.  What is the basic structure of an element used to link to another website?  
      `<a href="http://www.example.com" target="_blank">Example</a>`
  3.  What attribute should you include in a link to open a new tab when the link is clicked?  
      `target="_blank"`
  4.  How do you link to a specific part of the same page?  
      An id must be assigned to the element you want to reference. Then set an anchor tag with its value the same same as the id of the element preceded by a hash symbol.  
      `<a href="#id-name">Link to Section</a>`  
  
CSS Questions  
  1.  What is the purpose of CSS?  
      Allows the developer to add styling to the elements of a webpage.
  2.  What does CSS stand for? What does cascading mean in this case?  
      Cascading Style Sheets. Instructions are executed in the order they are placed in the file from top to bottom unless certain rules are applied.
  3.  What is the basic structure of a CSS rule?  
      ```css
      h1 {
        display: flex;
        justify-content: center;
        background-color: red;
        color: blue;
      }
      ```
  4.  How do you link a CSS stylesheet to your HTML document?  
      `<link href="css/stylesheet.css" type="text/css" rel="stylesheet">`  
      Make sure this is placed between the `<head>` tags
  5.  When is it useful to use external stylesheets as opposed to using interal CSS?  
      It's best to use external stylesheets if there is a significant amount of styling applied to the webpage. This keeps the HTML file relatively uncluttered with CSS code and makes it easier to read. It's also beneficial to use an external stylesheet when a website has multiple pages. Rules can be applied to all of the pages from one stylesheet. This helps with making adjustments to one file as opposed to many.
  6.  Describe what a color hex code is.  
      It is a six-digit code that represents the amount of red, green and blue are in a color preceded by a hash symbol.
  7.  What are the three parts of an HSL color property?  
      Hue, saturation, lightness
  8.  In the world of typeface, what are the three main categories of fonts? What are the differences between them?  
      Serif, sans-serif, monospace. Serif fonts have additional details or strokes within the letters. Sans-serif is an identical typeface without the additional strokes. Monospace consists of uniform spacing between the letters.
  9.  When specifiying font-size, what are the main three units used?  
      px, %, em
