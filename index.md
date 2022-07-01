# Object Detection With Deep Learning On Raspberry Pi
 
Using object detection I created a program that correctly identifies a certain subject/object from an image. In this case I can upload an image of an airplane into a folder and then run the code that was created, and it will subsequently tell us what airline the plane belongs to. A Long with this information it will let us know how certain the program is of it's findings. In the future, the code can be changed to detect any other object you could think of!

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sohith Movva | California Highschool | Engineering | Incoming Sophmore

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2021/12/BlueStamp-Logo.svg)
[Documentation](BSEdocumentation.pdf)
  

# First Milestone
  
So far I was able to get tensorflow working on my raspberry pi, which is a platform/tool that is made for machine learning. After getting tensorflow installed, I was able to test it out twice and it worked perfectly both times. First, I tested it with a given set of code found online and for the second test I uploaded an image and then tweaked the code in order to run this new image. The test results were completely as expected and basically gave an output of how certain the program is on what objects are in the given image. One challange I faced so far was when the code from the github didn't work completely, so to fix this issue I had to change a few lines and files which ended up working how I wanted it to. Since this first crucial step is now completed, the next step is to gather research and test materials for the main project of identifying airlines from images of planes!

<iframe width="650" height="365.625" src="https://www.youtube.com/embed/1lDAeFAYNfI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 <br> <br>

# Second Milestone
 
For the second milestone I was able to get an api working that would correctly utilize the labeled images that were fead to it in order to train the program to identify an airline based of an image of a plane. However this would only work with the specific link to the link after I used imgur to get said link. It was a bit of a hassle to upload the images and then get their link, then finally input it to the code for it to work it's magic. On the bright side, the output of the code was exactly as desired and it worked each time it was tested. The next steps are to clean up the code and output so it would be more clear to the user. As well as making the process less tedious from getting the image link each time manually. 
 
<iframe width="650" height="365.625" src="https://www.youtube.com/embed/qT83YkiYU4A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 <br> <br>

# Third Milestone
 
To wrap up the project I created a web server to host the images I wanted to run the code with. Using this web server I could put any image into a specific folder and run the program, which would give me the data I was looking for without the hassle of getting an image link and then inputting it each time. This makes the object detection program way more user friendly, efficient, and successful due the reduced percentage of human error during the link gathering process. Overall I am very happy with the finished product and it works just as well as expected, if not better. It is also great to know that I can alter the code slightly to work with any other object, not just planes, which will come in handy throughout my future! 
 
<iframe width="650" height="365.625" src="https://www.youtube.com/embed/XNyUs3A4QAA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
