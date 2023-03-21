In the anchor-tag.html file i've only included the code necessary for the section 14. HTML Anchor Tags excluding all the previous sections'
 
Don't forget to add the following standard elements to the anchor-tag.html file if you are considering testing just the anchor tags (section 14) on a separate webpage! I've initiated the code from <p> ... </p> as as am considering continuing this section's code with other sections to have the result of all sections on a single webpage.

<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Working with Anchor Tags</title>
</head>

<body>
...
</body>
</html>



The ... part represents the code for the anchor tags which is explained as follows: 

<p><h1>Table of Contents</h1></p>
<ul>
  <li><a href="#article1">Article 1</a><br>
    </li>
    </ul>

Here, the anchor tag is implemented for list contents under heading <h1> which can be initiated through a paragraph <p> tag 
An unordered list <ul> is used as it uses bullets by default as the marker but an ordered list uses numbers by default.
Then list <list> tag is used to list the contents

<p><h1><a id="article1">Article 1</a></h1></p>


