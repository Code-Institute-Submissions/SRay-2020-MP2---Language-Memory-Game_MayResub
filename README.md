# MILESTONE PROJECT 2 - Language Acquisition Memory Game - Interactive Front End

## Project Summary:
### The goal of this project will be to design and create a simple pattern matching memory game using JavaScript, HTML and CSS. The main goal for both the user and the site owner will be to have a game that is enjoyable to play. I will also include a 'language acquisition' component to this memory game which will highlight the versatility of this type of project and how it can be utilised for educational purposes while still being enjoyable which should expand the appeal of this website to a wider audience. 

### Link to Live Site - (https://sray-2020.github.io/MP2---Language-Memory-Game/)


### **MOCKUPS**

<img src="assets/images/mediamockup1.png">

A digital render of how the site would look on different devices and screen sizes 


### Contents - 

* [**STRATEGY**](#strategy)

* [**USER STORIES**](#user-stories)

* [**SCOPE**](#scope)

* [**STRUCTURE**](#structure)

* [**SKELETON**](#skeleton)

* [**SURFACE**](surface)

* [**FEATURES**](#features)

* [**FUTURE FEATURES**](#future-features)

* [**TECHNOLOGIES USED**](#technologies-used)

* [**TESTING**](#testing)

* [**BUG FIXES**](#bug-fixes)

* [**IMPLEMENTATION ISSUES**](#implementation-issues)

* [**DEPLOYMENT**](#deployment)

* [**CREDITS**](#credits)

* [**CONTENT**](#content)

* [**MEDIA**](#media)

* [**ACKNOWLEDGEMENTS**](#acknowledgements)


### **STRATEGY**

#### SITE OWNER GOALS:
The main goal of this project is to create an interactive website which hosts a single player, pattern matching game with a language acquisition component. This game should be fun for any user and should make the user want to return to the website to play again. This will hopefully be achieved by using fun and unique images throughout this project. The language acquisition component will hopefully broaden the appeal of this game to users, educators and parents which should will mean a higher base of users and more people who could potential enjoy playing the game and have fun!  

Target audience 
- People who like games 
- Early language learners
- Parents of young game users
- Educators

### **User stories**

Website user -

1. As a user I want a fun experience 
2. As a user I want to be able to play the game by being given the instructions needed but with as minimal instructions as possible
3. As a website user I want to be able to navigate the website easily and intuitively
4. As a user I want a consistent playing experience, that is the same every time I come back to the website and on any device

Early Language Users - 

5. As a language learner I want the words I am trying to learn to be displayed clearly
6. As a language learner I want to be challenged to remember words
7. As a language learner I want to play in multiple languages

Parents of Young Game Users - 

8. As the parent of a young game user I want my child to learn while playing a game
9. As the parent of a young game user I want the game to be safe and the content appropriate
10. As the parent of a young game user I want my child to have fun learning

Educators - 

11. As an educator I want a learning resource that will engage my students
12. As an educator I want a learning resource that will encourage my students to learn while having fun
13. As an educator I want a learning resource that is free and easy to access 

Website Owner - 

14. As the website owner I want the users to have fun playing the game
15. As the website owner I want the users to be engaged by the content of my website
16. As the website owner I want the users to return to my website
17. As the website owner I want users to be able to contact me to share their feedback

### **SCOPE**

This project will be a minimal viable product containing the aspects that are vital to functionality and an acceptable standard of aesthetic value, but with lots of opportunity to develop further in the future.

Functional specifications: 
- Navigation
- Card Flip mechanism
- Card Match mechanism
- Email contact form

Content specifications:
- Tutorial overlay
- Custom artwork
- Win/Lose overlays

### **STRUCTURE**

The website is laid out over three pages. 
These pages are 
1.Landing Game Page (Game in English/Irish) 
2.Secondary Game Page (Game in English/French)
3.Contact Page 

The two game pages (1 + 2)contain three overlays, these will instruct the player: 
- How to play
- Tell users if they have won the game
- tell users if they have lost the game
When a player clicks on this first overlay (after being prompted on screen to click) the game will begin. When this happens a timer will start, which will begin at 100 seconds and will countdown to zero. When the timer reaches zero the game will end. 

Pages 1 & 2 will contain 12 cards which will resemble playing cards. These cards will each contain a different image of an animal (repeating twice) to create six pairs of cards. Each pair will have the name of the animal that it contains written on it, one will have the English and the other will have the Irish (or French on Page 2) on it. On the reverse side all cards will be identical, containing a farmyard fence and a question mark. When a player clicks on a card it will flip over and they must select a second card to find it's match. If the player finds all 6 matches before the 100 seconds is over then they will win the game and the 'Victory' overlay will appear on screen. If they cannot find both matches before the 100 seconds elapses then they will lose and the 'Lose' overlay will appear on screen. A 'click to restart' prompt will appear on both of these screens. 

The contact page (pg3) will contain a very simple feedback form that will send an email to the author of the website. When all fields are correctly filled out and the feedback has been successfully sent, a thank you message will appear in the feedback box. 


### **SKELETON**

Differences between final design and wireframes:

There were no major differences between the final design or the website and the original wireframes. One slight adjustment was made to the wireframes for the first two pages of the site (Landing Game Page and Secondary Game Page) and mobile display adjustments needed to be made to the number of columns that were displayed and this changed from an original plan of 3 columns to the final layout of 2 columns at that media size. The contact page was kept in a very simple style which was scalable across all media sizes. As can be seen from the wireframe model below, the layout remained consistent. 

<img src="assets/images/MP2 - Wireframe.png">

##### Created at the outset of the project to direct the stylistic development. 

### **SURFACE**

Typography -
Two fonts were chosen for this project - 

The first of which is ???RocknRoll One???  - This font was chosen for it???s fun and playful style which maintained it???s visual form while using colour within. 

The second font used is ???VT32??? ??? This pixelated font was chosen because it is reminiscent of a retro game style and evokes an old-school aesthetic.

Colour scheme -

The author used Coolers.com to create a consistent and visually appealing colour palette for this project. Accessibility was also a concern so the author ensured that all colours of text used were done in a highly contrasting and visually pleasing manner .

<img src="assets/images/coolorspalette1.png">

Images -

A fun and interactive aesthetic was utilised for this project.  The desired effect would aim to make the user more comfortable and create an accessible space for any user to learn some new words for farm-yard animals in different languages, but more importantly have fun. All images were custom created by the author specifically for this project. 


### **FEATURES**

- Media responsiveness on all device sizes
- Navigation buttons that link to all pages
- Navigation buttons includes user feedback for click
- Game is available in two languages (Irish and French)
- Game includes a tutorial screen at startup
- Card Game includes 6 custom designed cards with names of animals in 3 languages
- Game includes a countdown timer
- Game includes a ???flip counter???
- Contact page form has form with ???value needed??? function
- Contact page has full functionality 
- Contact page button submits user feedback

### **FUTURE FEATURES**

- Game to include a play music function with audio (including background music and audio cues) when appropriate license free music can be obtained
- User name prompt and input to be used and stored
- User scores (number of flips) to be stored and displayed in a highscore field
- Learned words feature which displays which cards have been matched and the corresponding words for those animals
- Game made available in different languages
- Game made available with new 'decks' containing different words/images



### **TECHNOLOGIES USED**

HTML ??? For creating website

Css ??? For styling website

Bootstrap ??? Used Bootstrap grid system and called classes

JavaScript ??? For creating functions and interactive elements on project


Adobe XD ??? For creating wireframes

Adobe Photoshop ??? For editing images to consistent sizes and adjusting
 styles


Email.js ??? For email functionality on contact page

Git ??? Used for Version control

Gitpod ??? For code editing and testing

GitHub ??? For storing repository

Chrome Dev Tools ??? For editing changes in real time and checking styles in different media sizes

Chrome Lighthouse ??? For checking page performance

W3C CSS - For validating CSS code

W3C HTML ??? For validating and ensuring HTML code was correct/valid.

Coolers (website) - For creating a custom colour palette for project

FreeFormatter (website) - For validating HTML code

AutoPrefixer Online ??? For CSS parsing and adding vendor prefixes

AmIResponsive (website) - To ensure site is responsive and create mockup

### **TESTING**

#### **Code tests -**

The CSS code was passed through W3C CSS Validator and final version contained no errors. It was also passed through AutoPrefixer Online to parse CSS and add vendor prefixes.

The HTML code was passed through W3C HTML Validator and FreeFormatter.com to ensure final version contained no errors.

The JavaScript was tested using JSHint to ensure no errors included in final version. 

#### **Dev tests -**

(i)Chrome Developer Tools -

Chrome Developer Tools were used throughout this project and were greatly relied on to make all manner of adjustments and changes to project.

(ii)Chrome Lighthouse -

Chrome Lighthouse was used to ensure that the website has been deployed in the most efficient way possible ??? the screen shots below reflect the score of this project under four headings 
    ??? Performance
    ??? Accessibility
    ??? Best Practices
    ??? SEO
To bring this project to score this high some changes were made in all four categories to raise the score to be all registering at the highest bracket (90% +). 

These changes included - 
1. Performance: 
    ??? Added ???defer??? to the font styles to allow a faster load of base site 
    ??? Removing ???unnecessary CSS??? 
These two changes increased score in Performance from 76% to 97%. 
2. Accessibility:
    ??? Added new colours to increase contrast to improve visibility. 
This change increased score in Accessibility from 86% to 100%. 
3. Best Practices:
    ??? Images were changed to correct aspect ratio
    ??? Images that had been displayed at low resolution were replaced
These two changes increased score in Performance from 86% to 93%. 
4. SEO:
    ??? Added meta description to document 
This change increased score from 92% to 100%. 

<img src="assets/images/lighthouse.png">

#### **Function tests -**

This site was tested many times manually throughout the development process by the author and friends and family to ensure that it's functions behave exactly as they are intended to. This process was again repeated when hosted to ensure that there were no changes to functionality. 

Below are a list of the 
- Test cases
- Expected behaviour
- Observed Results
- Summary of expected behaviour and results 
These tests will be applied to the three pages included in the project (Landing Page, Second Page, Contact Page).

**Test Case 1:** Initial Load

Landing Page - 
- Expected Behaviour: Page will load correctly and promptly, with all elements in place where they should be.
- Observed Results: When loaded this page loaded without any issue and in a time that was satisfactory.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: Page will load correctly and promptly, with all elements in place where they should be.
- Observed Results: When loaded this page loaded without any issue and in a time that was satisfactory.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Contact Page - 
- Expected Behaviour: Page will load correctly and promptly, with all elements in place where they should be.
- Observed Results: When loaded this page loaded without any issue and in a time that was satisfactory.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 2:** Welcome overlay is visible and clickable

Landing Page - 
- Expected Behaviour: Overlay page will load and will initialise game on mouse click event.
- Observed Results: When loaded the welcome overlay was visible and when clicked it initialised the game.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: Overlay page will load and will initialise game on mouse click event.
- Observed Results: When loaded the welcome overlay was visible and when clicked it initialised the game.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 3:** Countdown timer begins

Landing Page - 
- Expected Behaviour: If game page is initialised the countdown timer will begin counting down from 100 seconds to 0 seconds
- Observed Results: When the overlay was clicked and the game begun, the timer began counting down from 100 seconds until zero.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: When game page is initialised the countdown timer will begin counting down from 100 seconds to 0 seconds
- Observed Results: When the overlay was clicked and the game begun, the timer began counting down from 100 seconds until zero.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 4:** 'Number of flips' counter measures only card flips

Landing Page - 
- Expected Behaviour: If the user clicks a card and it sucessfully flips over the 'Number of Flips' counter will increase by 1.
- Observed Results: When a card was clicked and it flipped sucessfully the counter incremented by one. When the screen was clicked anywhere else or if a card was clicked but did   not flip the counter did not increase. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user clicks a card and it sucessfully flips over the 'Number of Flips' counter will increase by 1.
- Observed Results: When a card was clicked and it flipped sucessfully the counter incremented by one. When the screen was clicked anywhere else or if a card was clicked but did   not flip the counter did not increase. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 5:** Card hover feedback

Landing Page - 
- Expected Behaviour: If the user hovers mouse over card the question mark should decrease in size with a transform, if the user takes mouse pointer off card it will return to     initial size.
- Observed Results: When the card was hovered on, the question mark shrunk in size and when the mouse was removed from the card it returned to it's original size. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user hovers mouse over card the question mark should decrease in size with a transform, if the user takes mouse pointer off card it will return to     initial size.
- Observed Results: When the card was hovered on, the question mark shrunk in size and when the mouse was removed from the card it returned to it's original size. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 6:** Card flip on click event

Landing Page - 
- Expected Behaviour: If the user clicks on a card it should flip over and display an image of an animal and the name of the animal underneath and stay face up until a second     card is clicked. 
- Observed Results: When the card was clicked it flipped over on the y axis and displayed the face side which showed an image of an animal and it's name underneath. This was done   for all cards and there was six different pairs of animals and each pair had the name of the animal in English on one and Irish on the other. The card remained face up until a   second card was clicked.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user clicks on a card it should flip over and display an image of an animal and the name of the animal underneath and stay face up until a second     card is clicked. . 
- Observed Results: When the card was clicked it fliped over on the y axis and displayed the face side which showed an image of an animal and it's name underneath. This was done   for all cards and there was six different pairs of animals and each pair had the name of the animal in English on one and French on the other. The card remained face up until   a second card was clicked.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 



**Test Case 7:** Card not matched event

Landing Page - 
- Expected Behaviour: If the user clicks a second card that is different to the first card then both cards will flip back over to display the side with the question mark- (no match will be found)
- Observed Results: When the second card was clicked and was different both cards flipped back over.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user clicks a second card that is different to the first card then both cards will flip back over to display the side with the question mark- (no     match will be found)
- Observed Results: When the second card was clicked and was different both cards flipped back over.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 8:** Card matched event

Landing Page - 
- Expected Behaviour: If the user clicks a second card that contains the same animal image to the first card then both cards will remain face up and a 'match' will be found
- Observed Results: When the second card was clicked and was the same as the first card then both cards remained face up (displaying the animal image).
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user clicks a second card that contains the same animal image to the first card then both cards will remain face up and a 'match' will be found
- Observed Results: When the second card was clicked and was the same as the first card then both cards remained face up (displaying the animal image).
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 9:** Victory Conditions met

Landing Page - 
- Expected Behaviour: If all card pairs have been successfully matched the game should end, the 'Victory' overlay should be displayed and all cards should be flipped back to be     face down again.
- Observed Results: When user successfully matched all the pairs the game ended and an overlay appeared on the screen saying "Victory, you win - Click to restart".The cards in     the background (behind the overlay) flipped back over to be face down.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If all card pairs have been successfully matched the game should end, the 'Victory' overlay should be displayed and all cards should be flipped back to be     face down again.
- Observed Results: When user successfully matched all the pairs the game ended and an overlay appeared on the screen saying "Victory, you win - Click to restart".The cards in     the background (behind the overlay) flipped back over to be face down.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 10:** Game Over Conditions met

Landing Page - 
- Expected Behaviour: If all card pairs have not been successfully matched within the 100 seconds the game should end, the 'Game Over' overlay should be displayed and all cards     should be flipped back to be face down again.
- Observed Results: When user did not match all the pairs within the 100 seconds on the timer the game ended. An overlay appeared on the screen saying "GAME OVER! - Click to       restart". The cards in the background (behind the overlay) flipped back over to be face down.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If all card pairs have not been successfully matched within the 100 seconds the game should end, the 'Game Over' overlay should be displayed and all cards     should be flipped back to be face down again.
- Observed Results: When user did not match all the pairs within the 100 seconds on the timer the game ended. An overlay appeared on the screen saying "GAME OVER! - Click to       restart". The cards in the background (behind the overlay) flipped back over to be facedown.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 11:** Click to restart function works on 'Victory' condition

Landing Page - 
- Expected Behaviour: If the 'Victory' overlay is clicked the game should reset itself, reshuffle the cards and be initialised again from the start (including resetting the       timer to 100 seconds,the flip counter to zero).
- Observed Results: When the 'Victory' overlay was clicked the game began again from the very beginning. The timer was reset to 100 seconds, the flip counter was reset to 0 and   all the cards were face down again and set in new places.  
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the 'Victory' overlay is clicked the game should reset itself, reshuffle the cards and be initialised again from the start (including resetting the       timer to 100 seconds,the flip counter to zero).
- Observed Results: When the 'Victory' overlay was clicked the game began again from the very beginning. The timer was reset to 100 seconds, the flip counter was reset to 0 and   all the cards were face down again and set in new places.  
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 12:** Click to restart function works on 'Game Over' condition

Landing Page - 
- Expected Behaviour: If the 'Game Over' overlay is clicked the game should reset itself, reshuffle the cards and be initialised again from the start (including resetting the     timer to 100 seconds,the flip counter to zero).
- Observed Results: When the 'Game Over' overlay was clicked the game began again from the very beginning. The timer was reset to 100 seconds, the flip counter was reset to 0     and all the cards were face down again and set in new places.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the 'Game Over' overlay is clicked the game should reset itself, reshuffle the cards and be initialised again from the start (including resetting the     timer to 100 seconds, the flip counter to zero).
- Observed Results: When the 'Game Over' overlay was clicked the game began again from the very beginning. The timer was reset to 100 seconds, the flip counter was reset to 0     and all the cards were face down again and set in new places. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 13:** Click on navigation buttons

Landing Page - 
- Expected Behaviour: If the user clicks on the 'French' button they should be brought to the 'Second' page of the website where the game is available in French. If they click     on the 'Contact' button they will be brought to the Contact page.
- Observed Results: When the 'French' button was pressed the user was brought to the correct page where game was available in French. When the user clicked on the 'Contact'       button they were directed to the 'Contact' page. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: If the user clicks on the 'Irish' button they should be brought to the 'Landing' page of the website where the game is available in Irish. If they click on   the 'Contact' button they will be brought to the Contact page.
- Observed Results: When the 'Irish' button was pressed the user was brought to the correct page where game was available in Irish. When the user clicked on the 'Contact' button   they were directed to the 'Contact' page. 
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Contact Page - 
- Expected Behaviour: If the user clicks on the 'Irish' button they should be brought to the 'Landing' page of the website where the game is available in Irish. If the user       clicks on the 'French' button they should be brought to the 'Second' page of the website where the game is available in French.
- Observed Results: When the 'Irish' button was pressed the user was brought to the correct page where game was available in Irish. When the 'French' button was pressed the user   was brought to the correct page where game was available in French.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 14:** Feedback on navigation buttons

Landing Page - 
- Expected Behaviour: The current page the user is on should be indicated to the user through colour feedback on the buttons on the top of the page. The current page they are     on should have a golden font to indicate this (whereas the other pages should have white font in the text on the buttons).
- Observed Results: When the user is on the 'Landing' page the button at the top saying 'Irish' is coloured in gold while the two other button texts remain white in colour.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Second Page - 
- Expected Behaviour: The current page the user is on should be indicated to the user through colour feedback on the buttons on the top of the page. The current page they are     on should have a golden font to indicate this (whereas the other pages should have white font in the text on the buttons).
- Observed Results: When the user is on the 'Second' page the button at the top saying 'French' is coloured in gold while the two other button texts remain white in colour.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

Contact Page - 
- Expected Behaviour: The current page the user is on should be indicated to the user through colour feedback on the buttons on the top of the page. The current page they are     on should have a golden font to indicate this (whereas the other pages should have white font in the text on the buttons).
- Observed Results: When the user is on the 'Contact' page the button at the top saying 'Contact' is coloured in gold while the two other button texts remain white in colour.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 

**Test Case 15:** Contact Page functionality

Contact Page - 
- Expected Behaviour: The page should display three input boxes with 'Name','Email' and 'Feedback' placeholders. They should all have the 'required text' function and the submit button should not be able to be pressed until all fields have been filled. When the 'Send Feedback' button is pressed an email which contains all the fields should be sent to the authors email address and formatted in the preset format. When an email is sent the fields should return to empty, except the bottom field which should be replaced with 'We have received your email. Thank you for your feedback :) '.
- Observed Results: When the user tried to click the 'Send Feedback' button on the form without filling in any of the three fields the website would not allow user to click button. When all fields were filled the button could be clicked and the form went blank in the 'Name' and 'Email' fields and in the bottom text field a message saying 'We have received your email. Thank you for your feedback :)' appeared. When this happned an email was sent and was received in the inbox of the author. This email was formatted in the correct way that it had been set up on JQuery.
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


**Test Case 16:** Error 404 Page

Error 404 Page - 
- Expected Behaviour: If a user inputs an incorrect HTML the custom 'Error 404' HTML page should be displayed, including navigation back to other pages of website. 
- Observed Results: When an incorrect HTML was entered the user was redirected to custom Error 404 page, which had buttons on top to re-direct back to all other pages of website.  
- Test Summary: There was no outstanding differences between the expected behaviour of this test and the observed results. 


#### **Response tests -**

The site was tested across all media query sizes and at all possible breaking points to ensure that a consistent and responsive experience was ensured for the user on any device. 

The author also used AmIResponsive.com to ensure that this was confirmed through an outside, objective source.


#### **Browser tests -**

Though the sote was developed through Google Chrome, after it had been deployed online it was tested across all other major browsers to make sure that it was fully operational. These browsers included 
- Chrome
- Safari
- Firefox
- Opera


#### **User story tests:**

**Website user -**

1. As a user I want a fun experience 
- Game is fun to play, it includes unique and cute images of farmyard animals on every card.
2. As a user I want to be able to play the game by being given the instructions needed but with as minimal instructions as possible
- Game includes instructions in the startup overlay but doesn't overwhelm user with information
3. As a website user I want to be able to navigate the website easily and intuitively
- Website has clearly labelled buttons that can be used to navigate website
4. As a user I want a consistent playing experience, that is the same every time I come back to the website and on any device
- Website has been tested at all different media sized and is fully responsive to changes while keeping consistent experience for user

**Early Language Users -**

5. As a language learner I want the words I am trying to learn to be displayed clearly
- Words on cards are displayed clearly with good contrast
6. As a language learner I want to be challenged to remember words
- Game shuffles location of cards after every game making for a more challenging user experience
7. As a language learner I want to play in multiple languages
- Game is available to play in English/Irish & English/French

**Parents of Young Game Users -**

8. As the parent of a young game user I want my child to learn while playing a game
- This game includes a simple language acquisition component which helps teach words to user
9. As the parent of a young game user I want the game to be safe and the content appropriate
- This game is safe and the content included is appropriate for younger users
11. As the parent of a young game user I want my child to have fun learning

**Educators -**

10. As an educator I want a learning resource that will engage my students
- Through the use of custom graphics this website is engaging for users
11. As an educator I want a learning resource that will encourage my students to learn while having fun
- This game encourages the user to remember where animals/words are which engages learning while also being fun to play
12. As an educator I want a learning resource that is free and easy to access 
- This game is free and easy to access and start playing across any platform

**Website Owner -**

13. As the website owner I want the users to have fun playing the game 
- This game is fun for users
14. As the website owner I want the users to be engaged by the content of my website 
- This website is engaging to users
15. As the website owner I want the users to return to my website 
- This game has multiple languages and is fun and engaging so users would return to it
16. As the website owner I want users to be able to contact me to share their feedback 
- This game features a contact page which includes an email feedback form so users can offer feedback to the website owner

### **BUG FIXES**

The project contained four major bugs, these were - 

BUG 1: Could not use 'a' element within the button tags due to an error on W3C markup validator. This bux was fixed by using a from instead of a an anchor tag and placing the button inside.

BUG 2: Attribute 'defer' could not be used in link element (because there was no src link) to slow down when the Google fonts were loaded. No good fix was available for this so 'defer' was removed from this link and the performance of load was slightly reduced. 

BUG 3: In CSS file a wrong media query width was included - this was deleted and there was no change to project (due to media size not being applicable). 

BUG 4: On deployment there was a problem with the contact form on the Contact page, which continually gave errors and was not properly connected to host site. This bug was fixed by author through testing and rewriting code. 


### **IMPLEMENTATION ISSUES**

There were no outstanding implementation issues with this project.

### **DEPLOYMENT**

**Git Hub Pages**

This project was developed in the Gitpod development environment. I initialised the project by creating a new repository for the project in GitHub and used this as a storing point to push the project to at various points through out the development process. Using the git add function I staged my code at many times and used the Git Commit command to save all changes. Finally, I used the Git Push command to send all the changes back to my repository on GitHub.
Git Hub Pages -
After site was completed I deployed the website to GitHub Pages using the settings feature on my project repository, scrolling to GitHub pages, choosing master as source and then saving the new pages link.

**Creating clone of project -**

To create a clone of this project you can access it through the link onf Git Hub Repository, click the clipboard to copy the url, this can then be brought to the terminal when a new working directory can be set up and the clone saved. Once this is done you can type ???git clone??? and paste the url and press enter and a new clone will be created.

**Running Clone on local machine -**

If you want to run this clone on a local machine you would go to the 'Clone' section on GitHub and click the url link in the HTTPS section. When you download and unzip these files to your desktop you can then open them in your own IDE shell and save them as a new directory. 

### **CREDITS**

#### **General Elements -** 

- Code Institute (Course content & Slack Community)
- The Complete JavaScript Course 2021: From Zero to Expert - Jonas Schmedtmann (Udemy)

#### **Specific Elements -** 

**Buttons** 
- FDossena: (https://fdossena.com/?p=html5cool/buttons/i.frag)
- W3Schools: (https://www.w3schools.com/css/css3_buttons.asp)
- Bootsrap Docs: (https://getbootstrap.com/docs/4.0/components/buttons/)

**Card Creation**
??? W3Schools: (https://www.w3schools.com/howto/howto_css_cards.asp)
- Web Dev Simplified: (https://www.youtube.com/watch?v=28VfzEiJgy4&t=8s)
- Tutorial Republic: (https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-cards.php)

**CSS Animations/Transformation**
-Web Dev Simplified: (https://www.youtube.com/watch?v=YszONjKpgg4)

**CSS Flexbox** 
- Web Dev Simplified: (https://www.youtube.com/watch?v=fYq5PXgSsbE)
- Free Code Camp: (https://www.freecodecamp.org/news/learn-css-flexbox-in-5-minutes-b941f0affc34/)
- CSS Tricks: (https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

**Card Game JavaScript Functionality** 
- Medium: (https://medium.com/free-code-camp/vanilla-javascript-tutorial-build-a-memory-game-in-30-minutes-e542c4447eae)
- Web Dev Simplified: (https://www.youtube.com/watch?v=28VfzEiJgy4&t=8s)
- PorEXE: (https://www.youtube.com/watch?v=3uuQ3g92oPQ&t=1385s)

**Loading Javascript**
- Flaviocopes.com: (https://flaviocopes.com/javascript-async-defer/)

**Lighthouse Issues**
- Web.dev: (https://web.dev/image-aspect-ratio/?utm_source=lighthouse&utm_medium=devtools)

**Managing Overlays**
- StackOverflow: (https://stackoverflow.com/questions/40311152/how-do-i-manage-multiple-overlays-on-different-buttons-clicks)

**Form Submissions**
- StackOverflow: (https://stackoverflow.com/questions/20416803/how-do-i-clear-the-previous-text-field-value-after-submitting-the-form-with-out)

**Media Queries**
??? CSS Tricks: (https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)
- W3Schools: (https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
- Code Grepper: (https://www.codegrepper.com/code-examples/delphi/bootstrap+hide+image+on+mobile)

**Adding Favicons to Website**
- Dani Krossing: (https://www.youtube.com/watch?v=kEf1xSwX5D8)

**README Editing**
- Adam Pritchard: (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Github Support: (https://github.community/t/link-to-a-section-in-another-readme-md-file/1130)
- Next Day Video: (https://www.youtube.com/watch?v=2dAK42B7qtw/)

#### **Other Elements -**

- Cooler.com - Colour scheme generator: (https://www.coolors.co/)
- EmailJS - Email service for form input: (https://www.emailjs.com)

### **CONTENT**

All text content was written by author 

### **MEDIA**

All images were custom designed and created specifically for this project.

### **ACKNOWLEDGEMENTS**

- Code institute
- Mentor (Spencer Shelton)
- Slack Community
- Friends and Family (for testing)
    

