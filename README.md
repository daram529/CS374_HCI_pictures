# BZDuck: Redesigning the experience of kpop fangirling/fanboying 

#### Team Name: Self-explanatory

#### Team Members:  
Jiyoun Ha  
Hyunjong Lee  
Sindy Wu  
Minkyu Yun  

### youtube url: [https://youtu.be/ROGVos1_nzo](https://youtu.be/ROGVos1_nzo)

## Iteration :

We first finalized what we should work on the iteration phase. From a list of items we wanted to tackle, we chose ones that are significant and can be implemented on time.  

* Change the ‘making jjal’ button  
* Visual Feedback for swiping left/right in weak wifi conditions
* When liked a “jjal”, page should stay where it is now
* include title in the navigation for information scent
* have a variety of videos that match to each emotional state
* have the same video when go back from Profile page
* have a title(“Starred video”) at Profile page to let users know where they are
* Include a control bar for the video
* Change the fast forward and reverse icons  

were the items we have listed to revisit during the iteration phase. Among the 9 items above, we first removed ones not related to our 3 tasks(browsing contents, view jjals and create jjals), so profile related items were removed. Also, we removed the “visual feedback issue when wifi is weak” and “have a variety of videos that match each emotional state”, because we thought it was less significant than other items **as wifi was more technical and more variety wouldn’’t affect the usage of the interface greatly.** The rest were implemented with some modifications.  


* Change the ‘making jjal’ button
	* Create a separate button for creating jjal, so that users would not be confused where to look for the button. Check out screenshot 3. at "Representative Screenshots"

* When like a “jjal”, page stays where it is now  
	* We have used an 'a' tag for the like button, so we changed the href to “javascript:void(0)” so that it won’t refresh the page to top.

* Include title in navigation  
	* We have added titles for each videos and displayed it right below the category navigation for give more sense of what video they are currently watching.

* Include a control bar for the video
	* We have concluded that there would be no need for a control bar as we provide fast forward and rewind. Instead, we have made a progress bar so that users can know where in the video they are watching. 

* Change the fast forward and reverse icons
	* Our fast forward and reverse features were for skip forward(5 sec), but as our icons did not represent what it does correctly, we changed the icons so that the user had more affordance to what it does.  

Through the iteration process, we have learned how we should communicate to select the items to iterate and cater the objectives of each items according to our design goals. We had a lot of items to work on, but managed to reduce them to a reasonable number and modified each items to make it fit with our service. 



## Final Interface :

### Representative screenshots:  

![1](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/a85d980d/DP8/1.jpeg)  
1. Sign up page. Choose favorite kpop idols.  


![2](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/a85d980d/DP8/2-1.jpeg)  
2. Onboarding guidelines for each button/function (swipes, characteristics filter, star, making jjal, reading jjals made by others).  


![3](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/a85d980d/DP8/3.jpeg)  
3. Task 1. Characteristics filter for contents (videos and GIFs) Filters based on user study.  


![4](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/a85d980d/DP8/5.jpeg)  
4. Task 2. JJals (from each video/gif) made by others. Users can like/download JJals from here.  


![5](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/a85d980d/DP8/6.jpeg)  
5. Task 3. Making/Sharing JJal. Users can make their own JJals and share with share with others.  


### Quality Arguments:

BZDuck boasts several features that make its interface “great”.   

First, the interface provides good usability. For **learnability**, BZDuck provides onboarding guidelines for each function. Even without the guidelines, our user studies proved that users have no problem figuring out how to perform each task. Swiping left/right to go to the next/previous contents is externally consistent with other apps (from user interview) such as ‘Tinder’, and is very clearly shown on the onboarding. The affordances, sizes, color, grouping, feedbacks and layout for buttons were improved throughout iterations to fulfil users’ standards. For example, at Hi-fi Prototyping stage, “making JJal” button was visible only when a video is paused because it’s natural to get a captured image from paused video. However, despite the onboarding, users had some problems finding the “making JJal” button, so we modified the interface so that “making JJal” and “starring” buttons are located together side by side. Also, icons for fast-forward and fast-backward of 5 seconds are modified so that they are more intuitive in how much seconds will be fast-forwarded/backwarded.  
<img src="https://cdn.rawgit.com/daram529/CS374_HCI_pictures/6bade156/DP8/star_button.png" alt="drawing" width="90px"/> <img src="https://cdn.rawgit.com/daram529/CS374_HCI_pictures/6bade156/DP8/create_jjal_button.png" alt="drawing" width="100px"/>
→ <img src="https://cdn.rawgit.com/daram529/CS374_HCI_pictures/6bade156/DP8/star_create_buttons.png" alt="drawing" width="200px"/>. For **efficiency**, the interface saves our target users’ time to search for kpop idol contents, the main need that out team tries to fulfill. From the interviews, we could confirm that our interface saves time to search for contents for both users actively and passively searching for kpop contents. For **safety**, the interface provides ‘undo’s for some of the important tasks including selecting favorite idols, starring contents, and sharing JJal.  


<img src="https://cdn.rawgit.com/daram529/CS374_HCI_pictures/6bade156/DP8/filters.png" alt="drawing" width="200px"/>  
The characteristics filter, one of the main features of our interface, was designed to be very user centered. The four categories 귀여워, 꿀잼, 감동, 섹시도발 (cute, funny, touching, sexy) don’t seem to be evenly distributed or MECE (mutually exclusive and collectively exhaustive) at all. They are not. However, they are focused more on the users’ needs and therefore more relevant than any other meaningless categories. Our team’s initial hypothesis was that as users are emotionally attached to the kpop idols, they have different wants at each emotional state. However, according to our interviews, the only emotional states found to be needed were sad and bored. We also found out that users tend to search videos not by their own emotional states, but by the videos’ characteristics and that all kpop idol has a concept of sexy vs. cute. Therefore, we revised the characteristics filter to include sexy, cute, touching and funny (touching and funny derived from sad and bored, respectively).   

Also, the interface has a unique, minimalistic visual design. We took out any unnecessary features so that the interface is very simple, organized and intuitive to the users. All the icons used are self-made or adjusted to make better affordances and consistency within the interface.   

Lastly, we have implemented all features via pure HTML and JS. To provide the best user experience, we had to carefully manipulate all UI components starting from the video, overlay and jjal creating part. We could have used video control provided by other libraries, or pre-built layouts, but based on our paper prototype and low-fi prototype, we figured out that we needed different layouts and had to build our own video control(skip forward and progress bar). We managed to implement all features by ourselves, or at least use only minor libraries. Moreover, to have completeness within our app, we also implemented features that are not included in out major tasks, such as profiles and starred video section. It was to give users the feel that they are not using a prototype but an actual service. It worked out well, as it provided richer experience for our user testing participants about our web app, which we think helped users give feedback with in depth understanding of what we are trying to do.



	

## Individual Reflection :  

### Jiyoun Ha

**Contribution :**  

I contributed mostly in creating and implementing the designs, while testing mobile compatibility of the interface. I implemented the designs for login, profile, emotional filter, home, and some of the comments. For the design assets, I created the onboarding, logo, and most icons (edited from open svg’s). I tested on mobile for consistency of designs and functions, and edited video view algorithm in accordance to our framed perspective. Lastly, I made the phrases for emotional filter and logo catchphrase.I also created the “top navigation filter”. 
Other than the actual implementations, I recruited various users for interview, who were mostly extreme users. The impressions they gave stuck throughout the design phases. Further, I was also the main actress for the video introducing our application. 

**Teamwork :**   

We had a good balance of different individuals, balanced as follows : 1) 3 CS-majoring students and 1 ID-majoring student, 2) 3 Koreans, 1 international 3) 2 individuals contributing mostly UI/UX, 2 individuals contributing mostly coding, 4) 2 males, 2 females. Such diversity allowed us to speak freely on various ideas without reservation and brainstorm. Though this chemistry allowed us to banter from time to time, we made sure to utilize our time together as much as possible and still said “Though we like each other, let’s not meet for more than x hours”, etc. Also, we had some time constraints and pressure. If we had more time, It would have been an easier progress.

**Lessons from experience :**   

I learned that though we always say “make a crappy prototype so that people can easily comment”, a good design does not only limit to core functions but also its implementation. We learned that even miniscule parts of the entire interface, such as tones in phrases for navigation bar resulted in a big UX difference. I learned that a UI’s theme is not only decided from the core functionalities itself, but the design of the UI actually offers  a lot of information scent and thus impacts the users heavily. Next time, I’d like to either 1)Have a user in the team or 2) constantly talk to the user in each iteration, or 3)create and implement, then make users like it. 


### Hyunjong Lee

I have contributed mostly on how comments(jjal) section works. How it retrieves data from firebase, renders the photos and buttons for each comments(jjals), reacts to like/unlike buttons and how it interacts with the main page, so that it will keep the main page still when browsing through the comments(jjals). Also worked on initial design of how our firebase should store user data and comments, which later Minkyu took charge of.  
Other than implementation, I have recruited our user testing subjects according to our PoVs, including KAIST students, high school students and also people with different age groups.
We had a wonderful teamwork, as we have tried to keep a psychologically safe environment. We could speak out even the dumbest ideas to initiate new solutions. However, it was quite hard to make a quick decision. Since we didn’t stop spitting out solutions, we sometimes took too much time just listing up ideas and couldn’t proceed to the next phase. If there was a more of a strict time constraint or coordinating role within our team, it would have been easier to move on. 
I learned that I have to actively escape from my perspective and more actively empathize with our target users. So having an environment to continuously communicate with the users and to understand them is preferred in the user centered design. 


### Sindy Wu

**Contribution:**  
I contributed in creating the CSS layout and design in general and the HTML/CSS template for sign in/sign up and for when the users create their own jjals. I also contributed to the textbox implementation in creating a jjal when we first split the pages between us. Afterwards, I worked on providing feedback for sharing and text editing, having the navigation go away when the user clicks outside, and implementing the buttons for comments and creating a jjal. After the user testing, I helped change the making a jjal button so that it pauses the video and shows the screenshot and laying out the title on the overlay.  
 
**Teamwork:**  
The team was well-balanced and had good chemistry. For example, when coding the guys mainly did the implementation while the girls did the CSS portion, but also when discussing and giving input, the girls generally had similar opinions but the guys could provide a different aspect. Everybody contributed quite equally and was productive. It was really nice because we were all willing to talk and actively participate. The team was also good in the sense that during team meetings we had good “banter” but it didn’t hold back on our productivity, which helped contribute to a good atmosphere. There were two hurdles, which were mainly both in the beginning. One, the girls tend to hold strong opinions and are very persuasive, which multiplied since the girls agreed most of the times. However, it’s a good thing the guys are not easy to persuade. Nevertheless, we realized this. We tried to be more mindful and ask for the guys’ opinion more often to give them a chance to speak. Two, when we disagree, we do a democratic vote of “Save” (thumbs up for us) or “Kill” (thumbs down for us). This was used a lot in the beginning DPs. From being in this team, I learned that there doesn’t need to be a leader for a team to work well. Although a leader provides focus and organization, it can also make the other members into minions. In our team, nobody particularly led the team. We were more united with a similar purpose, but I think this made our teamwork better generally. For my next team project, I would like to try to align everybody goals rather than the team be led by the leader’s standards.  
 
**Lessons from Project Experience:**  
Throughout the project experience, I learned for web-based GUI implementation that CSS was a lot of trial and error especially with positioning elements inline or on top of each other and centering elements vertically. I also learned that mobile web-based GUI implementation is more constricting as there is less affordance and a fingertip is not as precise as a mouse. With trying to make a draggable, editable, and resizable text box, it was hard trying to balance the clicking area especially on such a small surface. As for the user-centered design process, I’ve realized that it is a very iterative process and designers are not users. Things needed to be very obvious so we needed the onboarding. Then with the onboarding, we realized that users forget things especially since they aren’t being super attentive. There were always problems for every iteration, and because of that, I also learned that it’s extremely important to communicate with the users at every step. However, at the same time, users don’t always agree with each other. Through the user testings and interviews, although there was a general consensus, one person may not be in that consensus. For example, one user encountered no problems using the web app but all the other users did.  



### Minkyu Yun

**Contribution:**  

At first, we divided the UIs into 1) main video and navigation(overlay) 2) creating jjals and sharing 3) consuming(viewing) jjals and 4) profile and watching starred videos. As we decided on the most of the design choices together before starting implementing, each member just implemented the design into code. **I took the first one: full screen main video and overlay navigation that controls video as well as links to another functions. Also, while refactoring creating jjal UI, I had to make most of the modifications: canvas, text input, etc.** However, later on we didn’t stick to the only part that we were assigned. Rather, every member implemented any functionalities that are important at the moment. I mainly dealt with javascript: navigating through videos, starring & unstaring, sign in & sign up, sending/receiving data(user authentication, videos, jjals, starred videos, favorite idols, etc.) to/from firebase.

**What worked well and not:**  

**Good :**  
	Role distribution was perfect and every member was very passionate. I can recall the moment in the beginning of the semester when the professor suggested forming a team with members as diverse as possible. I believe our team was the perfect example of the ‘diverse team’. Each member had differences in interests and skills so that we could supplement each other’s weak points and smoothly led to role distribution. I was writing reports in markdown format when everyone else was working on the contents. Jen would always write down the feedbacks in the studio. In implementation-wise, Jen and Sindy were more interest and skilled in designing. I and Hyunjong contributed more on logics and JavaScript. I think teamwork is pretty much decided from the formation of the team. Members should have diverse backgrounds and every member should be expecting something similar from the course. If a team is formed by members with very smilar backgrounds, they will likely face problems on some area where none of the members is familiar with. If members expect different amount of work and output, it’s likely that they will fight at some point.  

**Bad :**  
	I think we spent too much time on the team project in the beginning, especially on very trivial things. We interviewed extra users, prepared for the presentation, paid a lot of attention to each word. Sometimes we had endless debates on ideas when we followed the majority rule and moved on. I still have some doubts on whether it will select the optimal solution or just average ones. The problem is very naturally resolved by two factors. The professor and the TAs gave us instructions not to spend too much time on some areas, like presentation. Also, as everyone was busy, we had to make team meeting short and as efficient as possible. 

**Lesson learned :**  

I learned that in order to make a team meeting efficient, every member should be prepared for the meeting. The meeting should be only for discussion. Therefore, everyone should read all the instructions and have thoughts before coming to the meeting. However, I found it more efficient to be in a same room when working on reports or implementation so that you can resolve any issue right away. Also, before start discussing, it’s very important to set a maximum time limit of how long we will discuss the issue, just like we did in the class, so that we can move on at some point.  
Also, I learned that it is very important to keep in mind that there is a deadline. There are endless wants from the users and from myself. Users always want something more and I always try to make the project better. It’s important to realize we can’t and shouldn’t satisfy all the needs to make it simple and complete.
