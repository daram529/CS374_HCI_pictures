# Sung Duck: Redesigning the experience of kpop fangirling

#### Team Name: Self-explanatory

#### Team Members:  
Jiyoun Ha  
Hyunjong Lee  
Sindy Wu  
Minkyu Yun  

## POV  

**User :** Korean 고3 kpop fans in high-school  
**User’s need :** need to see encouraging and empathizing contents of their stars easily  
**Surprising insight :** Because of their pressuring situation, it’s easier for them to feel stressed and uncertain.

**Updates :** Target user is changed from high school fangirls to 고3 kpop fans including both fangirls and fanboys because we thought there's not much difference of needs between the groups as we thought in earlier stages. However, we thought 고3 differed from other high schoolers due to the pressure they receive that year, so we decided to focus on them. We also omitted “emotionally empathize”, as user’s need, as users don’t necessarily want to consume videos with their exact emotional status, but complementing their emotional status.  
 

## Tasks  

Sensitize - As a high school student you must study a lot. Have you ever had those times where you broke down or the stress and pressure was too much? You wished you had somebody to comfort you. 

1. You just were in that situation. You have been studying for hours. It’s starting to make you tired, but you need to go into college. That thought just permeates your brain. You just want somebody to tell you it’s ok, to comfort you. You remember that listening to your favorite kpop stars’ songs always cheered you up because of the various lyrics and behind stories of the stars. You first **choose your emotional state as “위로받고 싶어요".** Then you want to **look for content (video)** so that your kpop star can comfort and make you feel better. You find the first tzuyu video to be the best.

2.  After seeing the video, you feel better, and you are curious about what other 고3 are feeling and what they think about the video. So you decide to **look through the comments/posts.** One of them really sparks you, **and you would like others to see it as well. (upvote)**

3. After looking through the comments/posts, **you are inspired to make your own** and begin to go through the video again. You want to capture the moment at the 1:49 mark because you think tzuyu looks the most beautiful at that moment.  You think that writing “힘내요” with tzuyu screenshot would help other 고3 in the same situation. 


## Prototype 

* **Prototype Link :** [Invision Link](https://invis.io/GFHMVSIATDZ)
* **Prototyping tool :**  
	* **Invision :**  
		* Pros
			* We could easily link different pages from designated hotspots.
			* We could generalize a layer over the whole category span.
			* We could save the screens in separate categories so to prevent clustering layers of different categories
		* Cons
			* On mobile, “swipe” means go to the next invision screen. There was no “test mode” in mobile, so it was not intuitive for the users to test the Invision prototype on mobile. 
Also no typing was allowed for our contents generation.
	* **Sketch :**  
		* Pros
			* It was lighter than Illustrator, and was designated for fast creation of digital interfaces
		* Cons
			* Organizing layers was difficult, as is the natural problem of Sketch.
			* Handling SVG files sometimes was tricky, as is the critical flaw of Sketch.

* **Design choices :**  
	* **Video format is not supported by Invision, the prototype we are specifically required to use. <span style=”color:red”>So we replaced videos by external youtube videos on the laptop via Wizard of Oz.</span>.**
	* **Video navigation :** we chose not to implement this function because video is not supported by Invision and it is not the essential feature for completing the tasks.
	* **Profile - selecting favorite stars and browsing through saved collection :** we chose not to implement this function/interface because it is not required function to complete any of our tasks.
	* **Video loading page :** we chose not to implement this interface because video is not supported by Invision and there's no need at this stage where there's no video loading time.
	* **Emotional Navigation :** we chose to only implement the emotional navigation on the very first slide because only the first task required it and we only had content for one specific phrase.
	* **Sign Up/Sign In :** we chose not to implement signing up and signing in as it was not necessary to complete tasks
	* **Overlay :** we chose minimalistic icons with descriptions, so to minimize the system’s interruption in user’s viewing activity. We thought that a choice of empty icons with white border clearly stood against most videos (dark stage), and yet was empty enough to minimize interference.
	* **Emotional filter via color bar :** we chose a navigation via color bar, because color is one of the categories most intuitively associated with emotions. We mostly referenced the Color theory for emotion.  

* **Representative screenshots :**

**Task 1 (View and filter the videos via the emotional filter):**  
![1_1](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/f2982de7/DP4/Task_1_default_screen.png)  
Default screen with overlay  


![1_2](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/f2982de7/DP4/Task_1_Emotional_Filter.png)  
Emotional filter


**Task 2 (View and upvote comment jjals on the video):**  

![2](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/0ce3fca7/DP4/Task_2_jjal.png)  
Jjal  

**Task 3 (Create your own jjal):**  

![3](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/f2982de7/DP4/Task_3_add_text.png)  
Add text  

Additional screenshots    
![4](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/f2982de7/DP4/Task_others_starred_videos.png)  
Starred videos gallary  

	
* * **Instructions :**  
	* As our project is intended to work on smartphones, we implemented on the smartphone interface. Therefore, you are supposed to go to the prototype link, send it to SMS ("SMS to Mobile" on the top right corner) and **access the prototype on your smartphone**.  
	* Because Invision doesn’t support videos, we conducted the user testing with the Wizard of Oz method. The user had both a phone and laptop in front of them. The wizard stood diagonally behind the user, and reenacted the playing and pausing of the videos that the user had in our prototype in phone using the laptop to show the videos. Therefore, the ‘play’ and ‘stop’ doesn’t actually do anything to the picture.  
	* Although we intended users could browse through videos using swipe, swipe will lead to the next screen (Invisionnative problem ), not the screen we intended. Therefore, we told users not to use swipe at all. The first screen should be 12, and the emotional should first be changed to “누군가에게 위로 받고 싶어요” before browsing through content. 


## Observations  
  
* **Task 1: Change the emotion and consume according videos**  

	1. They easily found where the emotion filter is and tapped it to change to another emotion - P1, P2, P3 / [Learnability]  
	
	2. They understood what the colors of emotion filters were easily navigated to the target feelings.  (ex : When asked to search for an “anger” emotion, they immediately navigated to the red color bar. ) - **P1, P2, P3. / [Learnability]**. There was only one emotion they thought it didn’t match the color. (“boastful” and green) - **P2 / [Learnability, Efficiency] / Low** 
	**Solution :** we will reference the “color theory” for emotions chart, which is most in line with user’s intuitions.
	
	3. They could use the tapping left/right to browse after tapping several places. They could easily go back to previous video by tapping the opposite direction. - **P1, P2, P3 / [Learnability, Safety]**  
	
	4. Users could easily browse through different videos as they tried tapping the screen several times. - **P1, P2, P3 /  [Learnability]**  
 
	5. Users couldn’t match the icons with their functionalities (They thought the stop button was for exiting the application, as was with some galaxy devices without buttons. ) - **P2, P3 / [Learnability] / Medium**  
	**Solution:** we will change the icons to their matching functionalities.(pause and memes)
 

* **Task 2: Consume jjals(memes) made by others**  

	1. Users easily browsed through the jjals (memes) by swiping up or down, just like what they would do in Facebook. - **P1, P2, P3 / [Learnability]**  

	2. Users easily found the functional buttons (After finding upvote buttons, they saw the feedback (the total upvotes were increased.) They also download with ease). - **P1, P2, P3 / [Learnability]**

	3. Comments(jjals) icon didn’t match with its functionality. Most thought that it was an icon for “chatting” . - **P1, P2, P3 / [Learnability] / High**  
	**Solution:** Change the icon into relevant icon that better indicates “comments”, and not “chatting”. 

	4. Jjals didn’t match currently selected emotional filter, because they’re one depth deeper than the videos that were filtered. - P2 / [Learnability] / Low  
	**Solution:** Because comments on post results from search results are not always necessarily to related to search query, this problem does not need critical system-related addressing. Instead, we will make ‘comments’ more evident so that users understand user-created comments on posts are able to have more aried voices. 

* **Task 3: Make your own jjal**  

	1. It took time to understand that the keyboard is not a real keyboard. After that, they quickly followed the steps. - P1, P2, P3 /  [Learnability] / Low  
	**Solution:** It would automatically solved when moving on to next prototype out of invision
	 
	2. Couldn’t easily realize that jjal can be only made at paused mode - P1, P2, P3 / [Efficiency] /  Low  
	**Solution:** Implement an overlay that says “Capture this to make a jjal” or some similar action keyword to indicate that more action for creating content can be completed from ‘capturing’ the video, or show instructions for creating a content only when the video is paused. 

	3. Regarded ‘공유하기' at the final stage as sharing on different platforms, rather than positing. - P2 / [Learnability] / Low  
	**Solution:** Rephrase ‘공유하기’ or give a good context to let them understand that it is not yet posted.



## Paper vs Digital  

* **Usability issues :**
	1. It is more native to try a prototype in a smartphone than in a paper prototype.
		* Participants are less timid to try various actions in a digital prototype. They swipe, tap, and do many actions that they typically engage in.
		* Hotspots are visible (in the Invision Prototype) when participants click once, and therefore next actions are better directed.
		* As expected, users have higher expectations for digital prototypes (as they compare the app with their other apps, testing external consistency more rigorously) as opposed to paper prototypes (a medium/method they’re not familiar with)

	2. It is much easier to control the paper prototype, as we suffered many constraints from the Invision prototype (ex : no swiping, no keyboard typing, specific rules in overlays, etc)

* **Participants' reaction and expectation to prototype :**
	1. Participants were more active on digital prototype as expected. For paper prototype, participants were more delicate and unwilling to click any button before they know its functionality. However, for digital prototype, all of the participants explored the prototype more actively to complete the tasks. For example, they clicked every button / section of the screen to see what happens.
	
	2. However, on invision, as participants could figure out the working functionality displayed as blue area. Therefore, after they explored the prototype for a while, they could easily figure out what to click.

	3. Participants had generally higher expectation on a the digital prototype, as they had the same standards as the actual apps, and gave us feedbacks more harshly. For examples, participant 3 gave us a comment that video navigation bar should be placed above the navigation buttons (fast forward/backward, pause) while no one gave us feedbacks about each icon/button’s positions. Participants were also more sensitive to each wording. For example, some participants pointed out that ‘Collection’ doesn’t match with starred videos on a full screen view, whereas gallery-like view does suffice the nomer.

* **Changes we made to digital prototype :**
	
	1. We changed the contents of our prototype from ‘quotes with static photos’ to videos with ‘jjals from the videos with texts’ as comments. The change was made due to the fact that fangirls consume videos more often and relieve stress from watching the videos. As we changed the contents, there were less differences between fangirls and fanboys, so we decided to include fanboys as our target users.

	2. We implemented paper prototype in web, but realized that high school students use their (no-SIM) smartphones more often at home than desktops when surfing the web. Therefore, we changed the entire interface to fit into smartphone.
		
		
## Studio Reflections  


#### Feedback from the studio session includes:

 
**Students' comments**

* Liked the idea of using tinder, didn’t think that emotion part was good but seems good now on
mobile app.
* Liked the emotion part. How does the user know which swipe is like/pass?  
**(reflection) →** We have changed our concept and not using swipe to like/pass anymore. The swipe is to go forward/backward, which is external consistent with other apps.

**TA’s comments**

* Liked how you selected the lessons from prototype
* Text(both when creating/reading) should be readable while not covering the stars’ face.  
**(reflection) →** Text will be in reasonable size



## Class Heuristic Evaluation Reflection

* User was confused about the lack of introduction at the main page / some feedback to introduce he service  - **Heuristic / [Aesthetic & minimalist design] / Major**  
**Solution:** We will have more clear and intuitive buttons, and feedback overlays (ex: “fast forwarded 3 seconds” in addition to the clear execution of action)

* User was confused about the state of the service (ex: where they were page-wise) - **Heuristic / [Aesthetic & minimalist design] / Major**  
**Solution:** we will change the icons to their matching functionalities.(pause and memes)

* User was confused about the meaning of each buttons. - **Heuristic / [Help & Documentation] / Major**  
**Solution:** This is a similar comment as from our actual tested users. We will minimize user confusion with buttons by refining buttons that were addressed in our user interview observations. 
