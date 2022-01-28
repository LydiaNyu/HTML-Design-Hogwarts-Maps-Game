# Introduction:
This is a small project using html and Javascript to build a website that will let users create their own maps of Hogwarts. The core of this system is based on a series of small graphics (32px by 32px), which can be "tiled" next to one another to form a seamless backdrop.

# Website Address:
It has been already uploaded to my school website: https://i6.cims.nyu.edu/~st3890/webdev/assignment04/

# Requirements: 
1. Create a graphical layout that contains a two columns - one on the left and one on the right. 
2. The left column should contain a block that is 320px by 320px to hold the user's map. Each individual image tile is 32px by 32px.  
3. The right column should contain all of the images included in the downloadable package.  

Whenever you click on an image in the right column the following should occur:  

4. That image should gain some sort of visual class to show that it is selected.  
5. Some variable should be updated to hold the 'src' property of that image so that we can use it to "draw" the map on the left side of the screen.  
6. Note that under no circumstances should more than one image on the right have the "selected" indicator attached to it.  
7. The left column should be filled with 100 divs that are 32px by 32px each. Make these divs float to line up next to one another.  
8. Set up each div so that when you hover over them they gain a temporary indicator showing that they are being selected (hint: use a hover state in CSS).  
9. Each div should listen for a mouse click. If it is clicked it should use whichever image was selected in the right column and set that as its 'backgroundImage' property.  
