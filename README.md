# BZDuck: Redesigning the experience of kpop fangirling/fanboying 

#### Team Name: Self-explanatory

#### Team Members:  
Jiyoun Ha  
Hyunjong Lee  
Sindy Wu  
Minkyu Yun  

## POV  

**User :** Korean Kpop newbie and intermediate fans who don’t have enough time or information about where to find idol contents
**User’s need :** Need refreshing contents of their favorite stars at the right time without spending too much time searching  
**User’s insight :** Because watching contents complementing their emotions make them feel better and energized.  

**Updates :**  As we looked back upon our interviews and had many discussions, we realized that the rapid shift into “Ko3 high school students” in DP3 to avoid common characteristics between our target user and ourselves was detrimental. Not only was the change of perspective forced, but it diverted us from the initial point we wanted to make : changing the experience of fangirling/fanboying, and focused excessively on combining these two specific groups. Looking back at the interviews and with more discussion, we found out that the pain points of Ko3 fans we elicited were not limited to Ko3’s only, but a core need of fans who are busy and don’t have enough time for scavenging contents. In fan culture, we saw that there was an evident,  gap between newbie fans (who don’t have enough time or information to scavenge for contents) and extreme fans (who would spend hours on scavenging for star contents). We want to target the newbie and intermediary fan who don’t have enough time or information about where to find new idol content, but nonetheless gain emotional benefit from consuming these contents.  


## Target users  

Korean Kpop newbie and intermediate fans who don’t have enough time or information about where to find idol contents  

## Tasks  

1. Find and interact with content that pertains to your emotional state as "너무 좋아! 지구뿌셔!!" without specific queries (save, filter by emotion, swipe through)

2. Go to "jjal" at your favorite video and look through all the comments. Find the best comment and show it by either liking or downloading it

3. Create a jjal comment for a video that best complemented your emotion that you want to share


## Implementation Notes  

[https://bzduck.github.io](https://bzduck.github.io)  
Please test on mobile device : Galaxy 7, 8 and 9 (excluding iPhone). Make sure that your wifi bandwidth is sufficient, as the platform handles video. Please use chrome when testing the web application.  

**URL of your Git repository :** [https://github.com/bzduck/bzduck.github.io](https://github.com/bzduck/bzduck.github.io)  
  
**Libraries and frameworks :**  

	* fontawesome 
	* bootstrap
	* jquery 
	* easytimer.min.js
	* firebase database & storage
	* github version control
	* github pages


**Representative screenshots :** 

**Sign up:** 

![1_1](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/signup.png)
![1_2](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/login.png)
**Task 1 (View and filter the videos via the emotional filter):**  
Default screen with overlay  

![4](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/emotionfilter.png)
![5](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/onboarding.png )

Emotional filter and onboarding


**Task 2 (View and upvote comment jjals on the video):**  

![6](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/jjal.png)
Jjal  

**Task 3 (Create your own jjal):**  

![7](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/1b70c115/DP6/create_2.png)
Add text  

Additional screenshots    


![profile](https://cdn.rawgit.com/bzduck/CS374_HCI_pictures/6a0bfff1/DP6/profile.png)
Starred videos gallary


## Individual Reflections 

### Jiyoun Ha  

**Contribution**  

At the beginning, I made the profile html template. Then I made the design guidelines for all screens of our interface, including the fine details of margin, alignment, and padding. Later, I made the top navigation bar throughout all the pages and the emotional filter bar, and respective functions. I also made the designs for login, profile, emotional filter, home, and some of the comments. For the design assets, I created the onboarding, logo, and most icons. I tested on mobile for consistency of designs and functions, and edited video view algorithm in accordance to our framed perspective. Lastly, I made the phrase for emotional filter and logo catchphrase.

**The difficulties**  
Mobile compatibility : I found it difficult to maintain the intended design when viewed from a mobile device, though the device view tool from developer mode of chrome had no problems. It seemed that it was a more difficult feat to maintain the expected design in mobile devices than in desktop, due to variability of the devices. Consequently, to maintain intended designs throughout different devices we had to disregard some of the fine-tuned design guidelines and constantly check from the device by pushing to the repository and editing on the go. Additionally, most of the margins and icon/text sizes were replaced in screen-size adjustable units, such as “em”’s and %’s.  
Iframe : There were some difficulties when implementing the top navigation and emotional filter bars due to iframe characteristics. I had to work with it a lot to get my intended div in tact while performing the intended function. 
Importing libraries without collision : As some of the UI components (buttons, icons, etc) were exported from external libraries, there had to be some fine tuning to use these without collisions.


**Useful Implementation skill**  
HTML / CSS : I learned to maintain an expectable design in mobile frames of different sizes. It also made me realize that it is more difficult to make a functional yet aesthetic design in mobile, due to limitation in size and lack of possible effects and information scavenging (ex : hovering is not possible on mobile). I also realized that keeping the design consistent on mobile is a difficult feat than it looks, as told by many obscure answers in stackoverflow. Throughout this process, I learned more ways in keeping internal consistency in design to make a mobile platform look presentable and trustable. 
I learned that though core functions and skeleton are the pillars of our platform, how they are phrased, presented, and instructed (ex: onboarding) can greatly change our perspective. Experimenting with many versions made me learn more on tying our platform more to the intended perspective. 


### Hyunjong Lee  

**Contribution**  
* At the start, I made the comments.html template, worked on how to connect the main page and the iframe comments page and designed how firebase saved comments so that we can pick up the data easily. Later, after we implemented basic functionalities, I got to work on anything that comes into our TODO queue. Still, I mostly worked on parts that needed communications between components, such as passing values so that iframes could display the right content. 

**The difficulties**  
1. I had hard time implementing how iframe should be closed with a button. As I had less experience with JS, it was not a very intuitive task. Inside the iframe, I couldn’t reach out to remove the whole iframe, so I had to make a button that has a larger z-index than the iframe and integrated like a nav inside the iframe.  
2. I had hard time connecting the github pages with a file server we planned to have. We later found out that firebase storage works well with https and decided to move our files to firebase.


**Useful Implementation skill**  
I picked up lots of html and JS implementation skills. I had to handle js code that manipulates the DOM and it really helped me understand how JS syntax, callbacks and DOMs work. Especially from adding event listeners to buttons and designing interactions was where I learned the most.  
Also I learned how to deploy a simple service through github pages with firebase so that you can actually store and authenticate user information. It is easy to create and deploy.


### Sindy Wu  

**Contribution**  

* I contributed in creating the css layout and design in general and the html/css template for sign in/sign up and for when the users create their own jjals. I also contributed to the textbox implementation in creating a jjal when we first split the pages between us. Afterwards, I worked on providing feedback for sharing and text editing, having the nav go away when the user clicks outside, and implementing the buttons for comments and creating a jjal.

**The difficulties**  

1. **Android keyboard pop up :**
	* One of the difficulties I faced was trying to figure out how to get the Android keyboard from pushing all the elements up. It was hard to test because it had to be done by phone since there was no keyboard pop up on the computer. Also I didn't know if the changes were actually being reflected even after I pushed to Github. 
			
2. **css positioning/layout (center vertical align) :**  
	* It was also sometimes somewhat difficult to position elements inline or on top of each other and center elements vertically. Mainly after trial and error, it was doable. To vertically align in the center was more difficult and harder to figure out since it had to be displayed in table form with a parent div.
	
3. **drag and text edit**  
	* Another difficulty was implementing a draggable, editable, and resizable text box in mobile, which ended up not being implemented in the end. However, when I was working on it, the plugins I tried didn't work and figuring how to code the difference between dragging and click was difficult. At first, whenever somebody pressed down on the textbox, the text box was only draggable and not editable. It was hard doing the balance of the two, particularly the clicking areas, without even attempting resize.

**Useful Implementation skill**  

* One useful implementation skill was definitely learning how to implement drag and text editing at the same time in mobile. Even though it wasn't implemented, it was good experience. The equivalent touch event listeners were connected to the mouse ones. I realized how to do the drag by using duration and movement as key factors and then using a handle since it was still finicky with touch on mobile. After touchstart, if touchend was called without any movement, it would be a click to edit text. However, if touchmove was called before touch end, it would be a drag. This helped me understand input, output, and structure a lot better. 

### Minkyu Yun  

**Contribution**  
    
* At first, we divided the UIs into 1) main video and navigation(overlay) 2) creating jjals and sharing 3) consuming(viewing) jjals and 4) profile and watching starred videos. As we decided on the most of the design choices together before starting implementing, each member just implemented the design into web app. **I took the first one: full screen main video and overlay navigation that controls video as well as links to another functions. Also, while refactoring creating jjal UI, I had to make most of the modifications: canvas, text input, etc.** However, later on we didn’t stick to the only part that we were assigned. Rather, every member implemented any functionalities that are important at the moment. I mainly dealt with javascript: navigating through videos, starring & unstaring, sign in & sign up, sending/receiving data(user authentication, videos, jjals, starred videos, favorite idols, etc.) to/from firebase.
    
**The difficulties**  

1. **requesting videos with server :**
	* At first, because firebase has small amount of bandwidth, we decided to use server to request video from. However, the problems we faced were https. Since github io pages were in https, they could only request from https servers, so we had to make ours as https as well. We could eventually make our server into https, but only in self signed, alerting users than our GitHub io page is insecure. We could simply host our web as well as videos on our server, but since instruction was to limit the usage of server as much as possible, we gave up everything we’ve done and moved all the data to firebase database and storage.
			
2. **creating a jjal from video: taking screenshot from a video and writing text on it**  
	* We had to make a canvas, input current frame of the video, and embed whatever a user types into the canvas, then encode the canvas into base64. There are settings needed to be done at server side in order to make a image from a screenshot of video, and embedding text into the image at the right size and right place were challenging.
	
3. **mobile web keyboard problem**  
	* Because we are implementing mobile web, it was very difficult to debug and test it on our device. Since we are using GitHub io, every time we want to test our code, we have to merge, push, and wait until the GitHub io is updated (it is updated very slowly due to the caches). However, bigger problem was with the keyboard. Unlike on the computer, when user inputs text/numbers on mobile, keyboard pops up and sometimes hides the input or resizes the screen.

**Useful Implementation skill**  
	
* For the difficulty 3, mobile web keyboard problem, I solved it by keeping track of device size. For our sign in / sign up page, when user clicks input box, keyboard popped up and user couldn’t see what they’re writing. Therefore, I monitored the summation of window height and window width. Since when keyboard pops up, window height changes while width stays the same, I added a class to elements that need to move up so that users can see the input boxes.
		
		
## Studio Reflections  


#### Feedback from the studio session includes:

 
**Students' comments**

*  "Would a first time user get to select their favorite star?"  
**(answer) →** Yes, you can do it in the signup. But for today's demo we aimed to show 3 tasks we had defined


**TA’s comments**

* Previously, I didn’t understand what you were trying to make, but now I understand what you‘re saying
* This prototype is for sharing content, but it should need more affordance for the functions it provide.  
**(reflection) →** We would provide visual guides, onboarding, top navigation (to state where in the application we are), and visual change of state with feedback (ex : before/after sharing or liking has different icon and/or feedback) to let them know what kind of functions we provide.  

* Would a normal teenager who like the prototype fully understand the affordances? For example, the swipe gesture might be hard to figure out.  
**(reflection) →** In addition to providing a visual onboarding for first time users, we also have made sure that none of our feature is too different from external consistencies of what our users would use. (ex : swiping is no longer for like / dislike, but for “new” / “undo”). Additionally, we would test it later next week
