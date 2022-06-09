# RPG - Dungeon Master Help. 



![Capa](https://user-images.githubusercontent.com/101576831/169187274-ddec5c5d-df39-4657-9ee3-a35876ea2f49.jpg)


I have been playing RPG for more than 20 year, and being a Dungeon Master demands a lot of time and commitment. 

With that in mind I tried to make one of the most time demanding things for a Dungeon master easier. Monster selection! 

Pathfinder has a lot of PDF books full of monsters, but unfortunately there is no fast way to check the most important information of a monster and see his image.

With that problem in mind, I decided to create an interactive Dashboard that displays the most important information regarding the monsters and their images.   




<img width="474" alt="Best 1 capa" src="https://user-images.githubusercontent.com/101576831/169187944-43a97675-a57d-4ef6-a1e1-c18482c5dfb6.PNG">


How to do it?
	After analyzing the task, I decided that the best way to accomplish it, is to extract the image and the name of the monster from the PDF book and get the information regarding the monster in an online site www.d20pfsrd.com.


About the Code: 
	PDF Scrap is no easy task, PDF files usually have a lot of images that are hidden under the ones that we can see, PDF files also are different between them.
Considering those 2 points above,  I was forced to do a specific code for each of the PDF files so I could extract only the images I wanted and the name of the monster. 
	After that I stated the Web Scrap, unfortunately the search of the www.d20pfsrd.com site wave captcha. To evade that, I searched directly on google using selenium. 
Some monsters had different names from the book,  so I needed to adjust their names individually for it to work.
After extracting all the information i made some adjustments in Python soo i was very easy to work with the information in Tableau and create a dynamic Dashboard. 
Conclusion: 
I hope this project can help a lot of Dungeon Masters, making their job easier so they can spend time doing what is most important, playing with your friends and having a good time! 

 

