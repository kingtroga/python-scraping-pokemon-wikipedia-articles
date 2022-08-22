# Scraping Pokemon Articles
<center><img src="images/gameplay.gif"></center>

 <ul>
   <li>
     <p>Being a big fan of the Pokemon Franchise. I was curious about the details on every pokemon there is. I want to be read up on any pokemon in my free time.<p>
   </li>
   <li>
     <p>So I found a list of all the Pokemon from wikipedia and copied the table into a Spreadsheet</p>
   </li>
 </ul>
 
<center>
  <img src="images/masterList.gif">
</center>

 <ul>
   <li>
     <p>Then I split that spreadsheet into various spreadsheets each containing each generation of pokemon</p>
   </li>
 </ul>
 
<center>
  <img src="images/genList.gif">
</center>

<h2>Coding</h2>

 <ul>
   <li>
     <p>First, I imported the necessary libraries. That is 'pandas', 'requests', 'os', 're'</p>
   </li>
 </ul>
 
<center>
  <img src="images/code1.png">
</center>

 <ul>
   <li>
     <p>Second, I created a directory (using python) to store the articles</p>
   </li>
 </ul>
 
<center>
 <img src="images/directory.gif">
</center>

<ul>
  <li>
    <p>Then, I loaded up "generation1.xls" to run logic tests on</p>
  </li>
</ul>

<center>
  <img src="images/code2.png">
</center>

 <ul>
   <li>
     <p>I didn't want the special characters in the file to mess up my program so I used Regex to take care of them</p>
   </li>
 </ul>
 
 <center>
  <img src="images/code3.png">
 </center>


## Algorithm and test
What I want to do is simple but how do I do it programatically.
1. Okay, I can make an article request to the Wikipedia API and check if everything went okay
2. Then write the article in binary form to file on my disk
Let's do that in code.
<center>
<img src="images/logicPic.gif">
</center>



