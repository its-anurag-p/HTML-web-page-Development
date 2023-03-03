Two types of image insertions are:
 
1) Relative File Referencing: The image path is defined relative to its directory so the image should be located in the same folder of the HTML document.
 
2) Absolute File Referencing: The image is from an external source like from another website so we need to copy the image link and paste here.
 
 Here, we are inserting 3 images names mentioned inside the double inverted commas " " 

 1) "RTH.jpg" &
 
 2) "EA.jpg" through Relative File Referencing which are saved in my local desktop folder named HTMLproject. 
 
 3) "https://th.bing.com/th/id/OIP.PNkjnBlLtONPJExZLvpLggHaFj?w=247&h=185&c=7&r=0&o=5&dpr=1.5&pid=1.7.jpg" through Absolute File Referencing hence the source/ image link is copied from a website and pasted in the code.
  


For Image Insertion the part of the code to refer is mentioned below:
 
<h1> Earth pictures </h1>

<p>

<img src="HTMLproject/RTH.jpg" width="330" height="250">

<embed src="HTMLproject/EA.jpg">
</embed>

<img src="https://th.bing.com/th/id/OIP.PNkjnBlLtONPJExZLvpLggHaFj?w=247&h=185&c=7&r=0&o=5&dpr=1.5&pid=1.7.jpg" width="330" height="250">

</p>

You can insert image on the webpage through the <embed>...</embed> tag or through <img> tag which is a self closing tag and its attributes are 
src= source of the image 
width & height.
 
  
  
