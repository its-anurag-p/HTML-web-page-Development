The syntax for the tag used to embed an video is as follows:
<video> src=" " </video> OR <embed> src=" " </embed>

The part of the code to refer for video embedding is:

<p>
<video width="100" controls>
   <source src="xd.mp4" type="video/mp4">
   Your browser does not support the video tag.
</video>
</p>


Here, the attributes are...

src which means source is the required attribute which specifies the source of the embedded video. Here, i've used (xd.mp4) a demo video and it is saved in the corresponding folder of the project. Make sure to save the video in the same directory that you have saved the HTML file into. 

Next to the source we have type attribute which specifies the video type.

width, height which are expressed by default in pixels but we can state them in percentage too.
100% will cover the whole screen and if mentioned in pixels you will see the video in mentioned amount of pixels regardless of the browser window size.  

The controls attribute is used to specify if the user wants to see the control menu which includes the play button, progress bar, the volume  and the fullscreen controller. If you do not want the control menu simoly remove the controls attribute and after resaving the file you will see there is no controller present for the embedded video.

Remember the autoplay attribute if you remove the controls because then the videoo will not play automatically and the user will not be able to play the video. If autoplay attribute prevails the video will be directly played at the launch of corresponding webpage. The autoplay attribute does not work with mobile devices like iPads & iPhones.


Check browser compatiability if it does not supports the video tag
