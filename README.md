# cheat-sheet
First project creating a cheat sheet for HTML and CSS
<!DOCTYPE html>
<html>
    <head>
        <title>HTML and CSS cheatsheet</title>
        <link rel="stylesheet" type="text/css" href="styles.css">
    </head>
    <body>
        <h1>
            HTML and CSS cheatsheet
        </h1>
        <p class="trial">
            On this page we're going to go through some of the basic
             things that you need to make a webpage work and look good!
        </p>
        <h2>
            Here's a list of the basic thing's you need at the start of a HTML doc.
        </h2>
        <ol>
            <li>&lt;!DOCTYPE html&gt;</li>
            <li>&lt;html&gt;</li>
            <li>&lt;head&gt;</li>
            <li>&lt;title&gt;&lt;/title&gt;</li>
            <li>&lt;/head&gt;</li>
            <li>&lt;body&gt;</li>
            <li>&lt;/body&gt;</li>
        </ol>
        <h2>
            Within the body section you can have the following...
     </h2>
     <table>
       <tr>
       <th>Tag</th>
       <th>Description</th>
        </tr>
        <tr>
         <td>&lt;h1&gt; to &lt;/h6&gt;</td>
         <td>This will apply a different size heading.</td>
         </tr>
         <tr>
         <td>&lt;p&gt;</td>
         <td>This will start a new paragraph</td>
         </tr>
         <tr>
           <td>&lt;br&gt;</td>
           <td>This will apply a one line break used within the paragraph tag.</td>
           </tr>
           <tr>
         <td>&lt;div&gt;</td>
         <td>Will provide a divide in your text, esentially the same as section</td>
           </tr>
           <tr>
         <td>&lt;section&gt;</td>
         <td>Will provide a section in your text</td>
         </tr>
     </table>
     <p> These guys can put you on the right <a href="https://www.w3schools.com/html/html_basic.asp" target="_blank">
          tracks</a>
          </p>
        <section>
            <h2>
                Some basic CSS rules....
            </h2>
            <p>
                You need to link the two sheets together so you
                 will need to enter something similar to this in the head section....</p>
                 <p>
&lt;link rel="stylesheet" type="text/css" href="style.css"&gt;
                 </p>
                 <ul>
                     <li><b>rel</b> describes the relationship between the HTML document and a linked document.</li>
                     <li><b>type</b> determines what type of data should be taken by an input element.</li>
                     <li><b>href</b> points to a specific file that you're uploading.</li>
                 </ul>
                 <p><em>
                     If you don't apply the above link then CSS will not work.</em>
                 </p>
            <p>
                There are a few different types of CSS selectors that you can use which is basically how you target areas of HTML....
            </p>
            <img src="https://i.imgur.com/lxfBa5f.jpg" alt="CSS Selectors">
            <p>
            When all else fails and you find yourself stuck then Google will be your friend along with <a href="www.w3schools.com" target="_blank">W3 schools</a>    
            </p>
            </section>
            <br>
            <footer>
              Created By: Phil Johnson
              </footer>
    </body>
</html>
