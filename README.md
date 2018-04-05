# Sung Duck: Redesigning the experience of kpop fangirling

#### Team Name: Self-explanatory

#### Team Members:  
Jiyoun Ha  
Hyunjong Lee  
Sindy Wu  
Minkyu Yun  

## Prototype
![0_login](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/0_login.jpg)  

![0_signup](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/0_sign_up.jpg)  
Sign up with favorite group and year.

![1_consume_contents](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/1_consum_contents_.jpg)  
**[Task 1]** The main page where users can consume contents. Content is displayed on the middle of the page. On the top-right, user's profile and album is shown. On the bottom-right, there's a floating '+' button for creating contents. The flag is to report inappropriate content, and the bookmark is to save the content.

![1_consume_contents_dislike](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/1_consum_contents_dislike.jpg)  
**[Task 1]** A user can swipe left to dislike the current content. Disliked contents are not likely to appear on the feed again.  

![1_consume_contents_like](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/1_consum_contents_like.jpg)  
**[Task 1]** A user can swipe right to like the current content. Liked contents are likely to appear on the feed again.

![1_consume_contents_filter](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/1_consum_contents_filter_by_emotion.jpg)  
**[Task 1]** As contents are classified into emotions, when click a different emotion, different types of contents are shown.  

![2_create_contents_photo](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/2_create_contents_photo.jpg)  
**[Task 2]** Users can choose default photo or search for photos from Google.

![2_create_contents_text](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/2_create_contents_text.jpg)  
**[Task 2]** The text that the user writes should be related to giving encouragement regarding the June Mock Test.

![2_create_contents_share](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/2_create_contents_share.jpg)  
**[Task 2]** Users can tag emotion, artist, and source.

![3_saved_contents_albums](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/3_saved_contents_albums.jpg)  
**[Task 3]** The user clicks album to go into saved content. If the user clicks the image, it enlarges.


![3_saved_contents_clicked](https://cdn.rawgit.com/daram529/CS374_HCI_pictures/47d5a0ff/DP3/3_saved_contents_clicked.jpg)  
**[Task 3]**  


## Participants

**How we recruited them:**  
Posted prototype testing interviewee advertisement on ‘Ara’, looking for high school students or college students younger than 20 years old who have been fans of kpop stars in high school.  

The reason we included college students although our target users are high school students is because it was very difficult to find high school fan girls in such a short period of time.  

**We interviewed 3 students in total:**  

* P1: 20 / Female / Korean / Fan of Bigbang since 13 yrs old
* P2: 19 / Female / Korean / Fan of Highlight and Beast since 12 yrs old
* P3: 20 / Male / Korean / Fan of Girls Day in high school, Twice in College


## Briefing

“Among Korean high school students who are going through stress due to tight academic schedules and pressure, some K-pop fans get motivated and relieved from stories of past struggle of their favorite stars. We want to design a website from which high school kpop fans can get academic motivation through contents with their favorite stars’ “picture quotes”. 

Interact with this paper prototype as if it were a web -- if you're not a high school student now, we want you to imagine yourself back in high school, in a highly stressful environment and relieving your stress via photos, videos, stories, and music of your favorite kpop star.”  


## Tasks

1. Browsing contents (motivational quotes with stars’ photos) and get motivated
	* Like/Dislike
	* Report
	* Save
	* Filter by emotion
2. Creating contents
3. Saving contents and browsing saved contents  

## Observations

* **Consuming content (Task 1):**
	1. Assumed emotion navigation was like Facebook emoticons  - P1, P2 (HIGH)  
	**Solution:** We will make it less confusing by differentiating with Facebook reactions and explain our emotion filter through an onboarding.
	2. Didn't know of swiping usage to like and dislike, and tried other actions (double click, scroll down, etc.) - P1, P2, P3 (HIGH)  
	**Solution:** Give instructions or have external consistency commonly used by our target user
	3. Question on flag(report), didn't know what it was - P3 (LOW)  
	**Solution:** Our report system is already externally consistent with other platforms, but we will allow users to figure out the function by giving high safety report button. When clicked, the modal page asks the user whether they want to report it.

* **Creating content (Task 2):**
	1. Doesn't use search query (not sure what it's for) - P1, P2, P3 (MEDIUM)  
		**Solution:** We added a placeholder 'google search' to show that they can use images other than default ones.
	2. Text being written by user when creating contents doesn't match purpose of platform - P3 (HIGH)  
		**Solution:** Give a better integrated nudge to remind the users the purpose of this platform, or clarify the purpose of the platform by aborting the concept that seems to distant (academic motivation). 
	3. Unsure of purpose of emotional tag - P1, P2, P3 (MEDIUM)  
		**Solution:** Once we fix the problem in Task 1 Problem 1, the concept of 'emotional filtering' will be clarified, thus also solving this problem.
	4. Sources misleading/not specific - P3 (MEDIUM)  
		**Solution:** Give a placeholder with an appropriate example to clarify instruction.

* **Saving contents and consuming saved contents (Task 3):**
	1. Unsure what ‘album’ button is - P3 (LOW)  
		**Solution:** We will reword the album or make profile image replace the task like Instagram (external consistency)  
	2. Unable to see things they've made - P1 (HIGH)  
		**Solution:** We will add a page where users can see the created contents of their own.
	3. Unsure how to go back to ‘consuming content’ - P1, P2 (HIGH)  
		**Solution:** We will make a (home) button to go back to 'consuming content' from any phase.

* **Overall:**
	1. Was in English while all the users are Korean - P1, P2, P3 (LOW)  
		**Solution:** We will build our prototype in Korean from the next stage.  


## Individual Reflections

### Jiyoun Ha  

**What role did you play in each round?**  
I played the observer once, and facilitator twice. 

**What were some of the difficulties you faced playing the role(s)?**  
	As an observer, I found it difficult to skip through some parts I wanted to question the users at that very moment. Instead, I had to write down some questions and notes, and ask the user to replay the act after all the tasks were done. This probably made the users difficult to answer their intentions than when asked right on spot. When I did try once asking the user what his/her intention was at a certain act, I felt like I might have disturbed the facilitator and felt guilty.  
	As a facilitator, I found it difficult to determine to what extend I should give users their clues. The user went back and forth through different tasks, sometimes unknowingly changing the option for the next task, and later wondering why he/she wasn’t able to complete the task as instructed. As we were to test end-to-end, this was an expected situation. I did give his/her some clues, guiding his/her back to his/her intended task; however, it was difficult to determine to which extent I should consider my hints no more “facilitating between the tasks” but giving excessive hints.  

**In what way was paper prototyping useful in your project?**  
	Our paper prototype was useful in that it gave us 1) a gesture/interaction user would take given the minimal clues for hotspots 2) an opportunity to ask their intentions in actions, on spot, and 3) the freedom for users to interact with the prototype freely without constraints of a prototype tool (ex: one user gestured as if she were trying to through the content box out of the prototype). All these opportunities for insights gave us a chance to fix our prototype at a very early stage. However, we saw that when tackling emotional properties (ex : fangirling), low-fidelity may not be a suitable option in some parts of the prototype. Further, users were often shy, not taking free actions or asking vocabularies within the interface he/she did not understand (ex : “June Mock-up Test” meant 6월 모의고사, but no user bothered to ask what it meant) especially as our prototype was written in English. This choice of language not only posed some inconsistent accessibility barrier (we’d just designed the prototype in English as the course is in English), but may have cast some emotional barrier as well, as our prototypes intended on integrating emotional properties of ‘enthusiasm from fangirling’ and ‘stress from academic pressure’. 
	
**What did your paper prototype not cover or test?**  
	The main issue, as also pointed by our TA’s, is that we have yet to test our paper prototypes with real high school fangirls. Instead, we tested our prototypes on “recent” graduates by 1~3 years (which, as pointed, could cast bias in their reflections.) As we had substituted our real users given the short amount of time we had for DP1, we plan on covering our real targets in later user studies.  
	Further, our paper prototype deals with an emotional experience of fangirling, but our mock contents weren’t designed with enough fidelity (ex : actual photo of the stars, their names, their sayings) to engage the users. They were told to play along with pre-made contents of stars they weren’t particular interested in. As suggested by our TA, this could be covered by designing the mock contents of our later prototypes with higher fidelity than the rest of the system.

### Hyunjong Lee  

**What role did you play in each round?**  
	I was a computer for the first testing and one of the observer for next two testings.  

**What were some of the difficulties you faced playing the role(s)?**  
	Working as a computer, I had to expect what the user can do as the next interaction. Since there were tens of papers flying around, I had hard time managing them physically and mentally. If not prepared for a feature, I lagged, and when I not well practiced to show a certain interaction of swiping, I got really confused.  
	As an observer, it was really hard to focus on what to observe. I could only focus on their action, or follow where they are looking at, or even if they are hesitating or not. I thought this was because I don’t have much experience with doing paper prototype and didn’t know what parts are the most important to observe. I’m actually curious if watching their implicit behaviors can be useful.  
		
**In what way was paper prototyping useful in your project?**  
	It was really helpful in the way that we could test our users and find out what parts should be redone and what were acceptable. Specifically, I think it was really good to know how the user went through the flow we had expected, so we could focus on where the users did not act as intended.
	
**What did your paper prototype not cover or test?**  
	The main weakness of our prototype is we did not have much examples. We had to show how our filter would work, but did not have enough contents to show for each choices, which made our user be confused of what the component works like. Also, because it was difficult to recruit high school students, we had to test our prototype with college students, which made us not test how “고3” schedule acts as a nudge.

### Sindy Wu  

**What role did you play in each round?**  
For the first user, I was the observer. For the other 2 users, I was the computer.  

**What were some of the difficulties you faced playing the role(s)?**  
It was hard being the observer because of the language barrier. I didn't understand what was going on or what she was expecting or her reasons for doing something. She thought aloud while doing the tasks, but I could only focus on the behavior and intonation of her voice. However, at the same time, because I didn't understand what was going on, I was a good observer because I was more mindful of small gestures and could only observe. For the other 2 users, I changed to computer because I didn't think my observations were that insightful because of the language barrier. Being the computer was a little stressful because there were so many components to keep in mind. It's hard not to forget something and have a quick enough change or feedback. Also sometimes there were parts of the interface that we didn't really think through so I wasn't sure how to react. In addition, there was this one situation where the user had saved a picture, so I remembered it. However, when I went back to the picture, he said he didn't save it. As the computer I should've just been mechanical, but it was hard to not argue back.  

**In what way was paper prototyping useful in your project?**  
The paper prototype was useful because it not only helped us catch interactions we missed but also we saw the user's conceptual model of the interface, which we did find to be very off. Also one thing that was very important was that the paper prototype revealed that our content was off and not exactly what the user wanted. Also with the paper prototype we could tell if the users understood the symbols and labeling. However, the users were more deliberate and less willing to try stuff out with the paper prototype, so it was hard to actually see if the users wouldn't have figured out the swipe left/right concept we had implemented.  

**What did your paper prototype not cover or test?**  
The paper prototype didn't cover the different pictures for each emotion. We only had three because the feel was still there like having feedback for changing emotions. However, the content was sketched, and the users couldn't really connect with the content. In this sense, it probably would've been better if we used actual picture photos from online. We didn't test going back or going out of a certain process like creating their own content, and we only figured that out in the testing when the users were a little confused when trying to go back. Also through the testing, we found out that we missed how users can see content they've created. The paper prototype didn't test for safety as well. There was no interface for let's say when the user exits the creating content page if the content was saved.

### Minkyu Yun 

**What role did you play in each round?**  
	I was a facilitator for the first testing and an observer for next two testings.  

**What were some of the difficulties you faced playing the role(s)?**  
	When I was a facilitator, as it was the first testing, we didn't have our confirmed briefing ready. Therefore, we missed some of the details (such as that our contents are classified by emotions) and may have given a user some confusions. From this difficulty, I realized how important it is to let users figure out our project through interface. Also, I had to suppress my urge to 'correct' the user everytime she does unexpected behaviors.
	As a observer, it was difficult to figure out what and why the users think/do that way. After users' testing, we interviewed them for a while and asked several questions inlcuding what they thought of certain interfaces and why they did certain actions.
		
**In what way was paper prototyping useful in your project?**  
	Paper prototype was useful in our project in that it allowed us to find major problems in very early stage. One of the problems, although not very difficult to fix, was that we made our prototype in English while our targeted users are all Koreans. This probably affected users not being able to understand our prototype thoroughly. Also, we found out that we were missing some of the actions that should be included to perform the tasks smoothly, such as going back to 'Task 1, consuming contents' from 'Task 3, seeing saved contents'. Also, we could confirm the difference of needs between female and male, therefore confidently targeting female only.
	
**What did your paper prototype not cover or test?**  
	The main problem with our prototpye was that we couldn't test our real users: high school fan girls. Instead, we had recruited those who close to high school in their ages and had experience of fangirling/fanboying in their high school. In later stage, we will try to let high school fan girls test our prototype. Also, our paper prototype did not cover designs, some of the basic or unnecessary functions, such as uploading profile photo. 


## Studio Reflections


#### Feedback from the studio session includes:

 
**Students' comments**

* We targeted user well
* She liked it because she didn't know how to create "picture quotes" before
* She wished that scope was bigger than mere academic motivation  
**(reflection) →** We think the scope is big enough, but as we have a problem with subtle integration between academic motivation and fangirling, we may consider aborting 'academic motivation' for better integration and consistent scope.
* She thought "Sung Duck" meant something to do with emotional connection with stars  
**(reflection) →** We looked up the definition of "Sung Duck", which means a fangirl/fanboy who succeeded in their fields and earned social respect. Therefore, we believe we used the terminology correctly.

**TA’s comments**

* Liked that we tested 3 users
* Liked that we got many UI insights via detailed paper prototyping
* If time allows, interview real high school students
**(reflection) →** We will try to recruit high school students in the later DP's.
* Because this solution tackles emotional aspects, it may be helpful to use real photos of the stars when making mock picture quotes.
**(reflection) →** For the user testing, we will use mock contents that are more realistic and therefore reflect users' emotional aspects better.