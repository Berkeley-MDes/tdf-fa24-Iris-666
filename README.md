# Hello!
This is Tian Qin. Welcome to my TDF repository :)

# Menu
[week 4](#week-4-my-interaction-ecosystems) \
[week 3](#week-3-building-lampshade-with-grasshopper) \
[week 2](#week-2-experiment-with-rhino-and-grasshopper) \
[week 1](#week-1-laser-cutting)


---
# Week 4 My Interaction Ecosystems
<p align="center">
  <img height="500" src="assets/week4/map.png">
</p>

I created a network map of my entertainment & media ecosystem, which visualize the devices, applications, and platforms I used in my daily life for entertaining purposes. <br />

I started my map with listing out all the devices or objects I used daily for entertainment. The ones that I used most often are definitely mobile phone, laptop, and ipad. These are my primary devices that serve multiple purposes beyond just entertainment. The overlapping of applications between these devices (e.g., Netflix, WeChat) offer cross-device functionality, allowing for seamless transitions between devices depending on the environment (e.g., using Instagram on mobile phone outside or watching YouTube on the iPad when relaxing at home). <br />

There are some other devices that have specialized roles in the entertainment ecosystem. Switch is primarily for gaming with games like Super Mario Odyssey and Animal Crossing, while Oculus supports VR experiences like Beat Saber. These two devices are highly immersive, focusing specifically on gaming and virtual reality, respectively.<br />

Between devices and platforms, content flows smoothly. Photos captured on the camera may end up edited on Photoshop and then shared via Instagram. Similarly, media consumption across Netflix, YouTube, and podcasts happens seamlessly across my devices, showing a well-connected media ecosystem. <br />

<p align="center">
  <img height="400" src="assets/week4/print.gif">
</p>

This week, I also continued exploring 3D printing in Studio Foundation class. I tried the bambu lab 3D printer at the Citris Invention Lab, and the result turned out really delicate. We also learned how to use metal threaded inserts to assemble the 3D printed part and the ccrylic board. 

<p align="center">
  <img height="300" src="assets/week4/print1.jpg">
  <img height="300" src="assets/week4/print2.jpg">
</p>

# Week 3 Building Lampshade with Grasshopper

After exploring Rhino and Grasshopper last week, I started trying to build my own model with grasshopper. I chose to create a lampshade cause the small ikea lamp on my desk is very dazzling, as the light bulb is directly facing the eyes. 

I firstly sketched out the shape of my lamp and the lampshade. 
<p align="center">
  <img height="250" src="assets/week3/sketch2.PNG">
  <img height="250" src="assets/week3/sketch1.PNG">
</p>

Based on a grasshopper tutorial of a [parametric vase](https://www.youtube.com/watch?v=jGIqvAQRXEc), I also sketched out the rough process in grasshopper to make it easier. 
<p align="center">
  <img height="300" src="assets/week3/sketch3.PNG">
</p>

I learned many new components during the process. For example, the Revolution component is used to create a surface by rotating the curve around an axis, so I can create an annular surface as the basic shape of the lampshade. Weave takes two input lists and combines them into one single output list, so it combines the two sets of curves together to make a wavy pattern. Then I use loft to create a surface by connecting those curves. 

To make the shade perfectly fit my lamp, I imported a side photo of my lamp into rhino to check. I also measured the perimeter of each part of my lamp carefully to make sure the size of the model matches the lamp. 

<p align="center">
  <img height="250" src="assets/week3/lampshade1.gif">
  <img height="250" src="assets/week3/lampshade2.gif">
</p>

<p align="center">
  <img height="250" src="assets/week3/lampshade4.png">
  <img height="250" src="assets/week3/lampshade5.png">
</p>
I encountered many challenges during the process, for example trying to understand what each component is doing and a lot of debugs. However, it turns out the biggest challenge is printing this model out. It failed several times because the shape of the bottom is very wavy and tortuous. And finally, it succeeded on the third try! Although the printing temperature was set too high, makes it very difficult to take off the support. 

<p align="center">
  <img height="250" src="assets/week3/lampshade3.gif">
  <img height="250" src="assets/week3/lampshade3.jpg">
</p>

From this project, I noticed that I should learn about the constrains of the tools and medium that I’m using, and design the project based on that. For example with 3d printer, it would be much easier to print something with a flat bottom instead of a curly bottom.

<p align="center">
  <img height="250" src="assets/week3/lampshade6.gif">
  <img height="250" src="assets/week3/lampshade7.gif">
</p>

# Week 2 Experiment with Rhino and Grasshopper  #

This week I started with going through a rhino 8 beginner [tutorial](https://www.youtube.com/watch?v=mAXknDTPULE&list=PLWIvZT_UEpWXs6niI0BiWz2xMg0bHbEfs&index=4) to get familiar with the interface and functions of rhino. The tutorial was only 1 hour, but it took me more than one afternoon to follow the tutorial to finally build a chair. I managed to understand some basic but seems to be important rhino concepts during the process, like c plane, planar curves, osnap, pushpull, mirror, inset, scale1D.

<p align="center">
  <img height="400" src="assets/week2/chair1.png">
  <img height="400" src="assets/week2/chair4.png">
</p>
<p align="center">
  <img height="250" src="assets/week2/chair2.png">
  <img height="250" src="assets/week2/chair3.png">
</p>

I also learned grosshopper with this [tutorial](https://www.youtube.com/watch?v=CzmZjo2_3-M) and successfully built a box with a lid. It was interesting to learn and really helpful for understanding the grasshopper graph we got in class. 

<p align="center">
  <img height="400" src="assets/week2/gh2.png">
</p>

One very useful concept from grasshopper is brep. It appears a lot in the example file and I was so confused at first. Later I noticed that brep can be anything and in many cases it’s used for make the diagram clearer and more organized. 

Another useful trick that I learned from Chuhua is that by clicking this little green button in the upper right corner, I can easily preview what I selected in grasshopper. This really helps me to understand what each part of the grasshopper file is doing.

<p align="center">
  <img height="400" src="assets/week2/gh1.png">
</p>

So with help of that, I drew out the diagram of the steps building the shape of the phone stand. 
<p align="center">
  <img height="400" src="assets/week2/diagram1.jpg">
</p>

And then I started to modify the example file to replace some nodes and change the shape of the phone stand.
<p align="center">
  <img height="400" src="assets/week2/gh3.png">
</p>
---

# Week 1 Laser Cutting #

This week, I went through the laser cutting and 3d printing tutorials and quiz. I design and laser cut a coaster with the photo of my dog. It was an interesting experience to custom make something useful by myself. 

I used 3mm plywood to make the cut and the result was really satisfying. This was also a very helpful refresh for using those machines. 

<p align="center">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster1.jpg">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster2.jpg">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster3.jpg">
<img width="200" alt="a Cool Coaster" src="assets/week1/coaster_cutting.gif">
</p>
<p align = "center">
  <img width="500" alt="a Cool Coaster" src="assets/week1/coaster4.png">
</p>

---
## Quick Links: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
