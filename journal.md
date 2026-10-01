# JOURNAL
DEAR READER,this is my journal for my rover, its a bit imformal but i tried my best to organize my thoughts...
## 29 SEPTEMBER
designing a rover is one of the plans that i always had, but im not a professional so i will research->model->get frustrated->research for another design->model->accept the mediocrity->repeat.  
first day i started my research about how a rcoker bogie even works? like i know it has 6 wheels can traverse rough terrain , can climb twice the diametre of its wheels, keeps all six wheels on the ground even on assymetric terrain  
but how does it do that? idk...  
after some hour of googling and watching the "science behind rocker bogie" i had a rough idea of wht it is  
THIS VIDEO HELPED IN UNDERSTANDING DIFFERENTIAL USE IN ROCKER BOGIE-  
[![DIFFERENTIAL ON ROVER](https://img.youtube.com/vi/fs5-uF0McYk/maxresdefault.jpg)](https://www.youtube.com/watch?v=fs5-uF0McYk)

Now that i had a rough idea of wht im dealing with i wanted to start making the whole 6 wheel system , but its not the same as a
4 wheeler where u can just draw a rectangle add some extension on corner for motor and wheel and ur done with the skid steering design,
here i would have to pre calculate every dimension that im going to use bcz that will determine how the rover's gonna act,  
with 6 wheels the design is a bit complicated as now there are two separate parts on each side of rover -  
on each side a pair of wheels are attached to a common pivot which goes on to connect to the 3rd wheel on the main pivot-
<img width="434" height="184" alt="image" src="https://github.com/user-attachments/assets/cfda477a-24e7-43c8-8a2a-e0173bc02b26" />
kind of wht we can see on this image  
so with this information i headed straight to learning how actually u deicide how long each arm's gonna be?(they call these their "arms" 
idk shouldn't these be legs?) the two wheels connected on the front are part of bogie arm(small 'V') while the rear wheel is part of the rocker arm(big one)  
hence the name -ROCKER BOGIE.  

THIS VIDEO TAUGHT ME THAT THERE'S A METHOD TO FIND OUT THE EXACT DIMENSION AND ANGLES IN THE ARM-
[![Watch the Video](https://img.youtube.com/vi/X_NhGME49gQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=X_NhGME49gQ)  
so i made my own blueprint-<img width="1311" height="696" alt="image" src="https://github.com/user-attachments/assets/0ac5aa87-31e8-427d-a344-b24a7f8a97b8" />
the dimensions are just the size i preferred to have , the length of this decides wht the main chassis's dimension can be so it is just that i can fit my sensors and stuff 
next i extruded the parts separately and joined them here's the first prototype lol-
<img width="905" height="659" alt="image" src="https://github.com/user-attachments/assets/e7eb06fb-27d4-4e6a-a891-cecada91a529" />
look at that rocker bogie ! finally some progress , atleast i have a path now , though the main chassis is too big and goofy , its just a place holder , it won't cause any trouble...so i thought.  
now if u observe my rover have a handle thingy on the front, well wht happened is i was confused how to make a differential bar , so i googled some differential bar ,
the first thing i saw was nasa's rover which had this nose differential bar, so i thought if nasa's using it then its the best!, well now i know...  
after i added the differential bar , which u can see in that picture, next step was adding the tie rod,  
TIE ROD: is used to connect the diff bar with the main arm.   
how it works: when a side's main arm goes up it pushes on the tie rod , which rotates the diff bar which affects the other tie rod and pushes it, causing the other arm to go down,
this  ensures that all 6 wheels stay in contact with the ground at any moment.
but i failed , i couldnt get the tie rod to connect without colliding with the bogie arm , so i got frustrated and decided to switch to some different type of differential bar.

## 30 SEPTEMBER











