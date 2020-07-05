# Milestone Project 1 - Soul Gym
View live project <a href="https://">here
***
## Table of Contents:
* [What does it do and what does it need to fulfill?](#what-does-it-do-and-what-does-it-need-to-fulfill)
* [User Experience](#user-experience)
   * [User Stories](#user-stories)
   * [Design](#design)
       * [1. Colour Scheme](#1-color-scheme)
       * [2. Font](#2-font)
       * [3. Logo](#3-logo)
       * [4. Geometry](#4-geometry)
       * [5. Wireframes](#5-wireframes)
* [Technology Used](#technology-used)
* [Features](#features)
   * [Future Features](#future-features)
   * [Removed Features](#removed-features)
* [Testing](#testing)
   * [Defensive Design](#defensive-design)
* [Deployment](#deployment)
* [Credits](#credits)
   * [Special Thanks & Acknowledgements](#special-thanks--acknowledgements)
***

## ![Soul Gym Logo](assets/images/sg_logo.jpg)

### Soul Gym Logo

***
## **What does it do and what does it need to fulfill?**
This is my first milestone project, where I have designed, created and built a mobile-first responsive website for a gym. My goals with this website are to share the unique perspective on fitness that this gym offers; to persuade prospective members to sign up; and to give existing members an online space to book classes and enforce a sense of community. 

I have taken my knowledge learnt from the beginning three modules of the Full Stack Web Developer course, (HTML and CSS Fundamentals, and User Centric Frontend Development Modules) to provide a clear, functioning and responsive website that demonstrates a good use of HTML5 and CSS3. The Bootstrap Framework was used along side these programming languages to give the site a good strucutre, and ensure the site is as responsive as possible for use across various screen sizes, from desktop, tablet and down to mobile.


## **User Experience**
<div style="text-align:center"><img src="assets/images/response.jpg" alt="Soul Gym Logo"></div>

#### User Stories:
* First Time visitor Goals
    * As a first visitor, I want to be able to navigate through the entire site, comfortably and securely.
    * As a first time visitor, I want to be able to easily message the gym with any initial queires that I may have.
    * As a first time visitor, I want to learn more about the gym and what is available.
    

* Prospective Gym Member
    * As a prospective gym member, I want to know how much membership costs.
    * As a prospective gym member, I want to be able to book a tour.
    * As a prospective gym member, I want to see what classes and facilities the gym offers.
    * As a prospective gym member, I want to feel comfortable and informed that this gym is right for me.
    * As a prospective gym member, I want to be able to contact and locate the gym.
    * As a prospective gym member, I want to be able to sign up to the gym.

 
* As a member of Soul Gym
    * As a member of Soul Gym, I want to be able to login to my account with the gym.
    * As a member of Soul Gym, I want to be able to book a class.
    * As a frequent user, I want to be kept up to date on any new facilities and initiatives the gym is working towards
    * As a frequent user, I want to be able to easily access a weekly class timetable, so I can plan my visits.
    * As a member of Soul Gym, I want to be able to submit any questions, feedback or complaints.

#### Design
##### 1. Colour Scheme

I chose soothing colours to make the website inviting and help visitors feel calm when visiting the site.

Colours I used are:

* ECEAEA - Platinum - Primary Colour
* C4A55F - Light French Beige - Secondary Colour
* 827081 - Old Lavender
* 000000 - Black

The primary colour used throughout the pages was used as the main colour. It supported the Navbar and footer, as well as the background colour for my forms and individual cards on both the classses page and the about page.<br>
I originally used the secondary colour within my logo, and found it had such a great contrast to the 'Platinum' colour. I implemented it for use as the icons colour, the various buttons colour, table hover, and the names of the people in the quotes section.<br>
The third colour I used was the 'Old Lavender'. With this colour I found it blended well in between the two main colours, enhancing them both further. It too had a great contrast with the 'Platinum' colour. I used this colour as user feedback when the icons were hovered over, the buttons once they were clicked, and as block dividers between content, as well as borders for the forms and cards, really making them stand out.<br>
I toyed with the idea to have a fourth colour as a main background across the pages, but I found the pages just looked too busy. As the site is for a gym that offers more than just a gym, hosting yoga and offering mindfulness ways of life and techniques, white space was so important to give that fell of comfort and simplicity.<br>
The black used was for all text across all pages, minus the names used with the quotes.

##### 2. Font

I decided to use two fonts throught my site. I included these fonts by inserting an _import_ link of Google Fonts API into the top of my style.css.<br>
The font I used for the body of the pages was "Roboto', with a fall back of 'Sans-serif', in the case of the site not loading the import correctly. I found the 'Roboto' font had a nice easy rading style to it.<br>
The second font I used was the 'Noto Sans' font, again with the fallback of 'Sans-serif', was used as the font for anything I wanted to stand out. The navbar and footer, headlines across images and headings. I found this font gave a bold statement of here I am but not in a way that is dominating, but a way that. Its clean. - chloe knows best :). 

##### 3. Logo

The logo was created using a progamme called $#$#$. I dbsjbsjfbsfbjfbfjbsfbskfbfbalsdbbwvbwvlkbewlbe

##### 4. Composition

There is a clear structure kept throughout the site. Each of the main pages was to have a hero image placed at the top with text overlaying it, and content hinting displayed at the botto of the page to encourage scrolling/more interaction. I implemented the 'Rule of Thirds' where I found it fitting, to draw the viewer's eye into the composition, rather than just glancing at the center. You can find evidence of this in the footer, but most clearly on the classes page with the cards. I was going to have the about cards following this rule but instead decided that having these centrally positioned one on top of the other drew the readers eyes down, so it felt more like the story it is intended to portray.

##### 5. Wireframes

Wireframes for this project were created using Balsamiq. I initially sketched rough ideas down on paper, to then further construct them on the computer, creating essentially more of a Mockup. The final product made using these wireframes were not too far from what they show. Find below links to these wireframes.

* [Home Page Wireframe](https://github.com/Gregory4321/milestone-project-1/blob/master/assets/images/wire-home.jpg)

* [Classes Page Wireframe](https://github.com/Gregory4321/milestone-project-1/blob/master/assets/images/wire-class.jpg)

* [About Page Wireframe](https://github.com/Gregory4321/milestone-project-1/blob/master/assets/images/wire-about.jpg)

* [Contact Page Wireframe](https://github.com/Gregory4321/milestone-project-1/blob/master/assets/images/wire-contact.jpg)

[Back to Top](#table-of-contents)

 #### Technology Used

 ##### Languages,

 * [HTML5](https://en.wikipedia.org/wiki/HTML5) - Language used to create the structure of the pages.

 * [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Language used to add styling across all pages.

##### Libraries, Frameworks and Editors

* [Bootstrap 4.5.0](https://getbootstrap.com/) -used to creat basic HTML layout and structure and using Bootstraps CSS Framwework. The resposnsive grid system was utilised well.

* [Google Fonts](https://fonts.google.com/) - was used to import the 'Roboto' and 'Noto Sans' fonts, that were used across all pages.

* [Font Awesome](https://fontawesome.com/) - was used for the social icons and the calender link found in the footer.

* [jQuery](https://jquery.com/) - was used in conjunction with Bootstrap to create the navbar collapse element.

* [Git](https://git-scm.com/) - used for version control by making use of the Gitpod terminal to commit to Git and push to Github.

* [Github](https://github.com) - used to host the projects repository and store the code, as well as host the website on Github pages.

##### Tools

* [Google](https://www.google.co.uk/) - was used for research various techniques, styles and information.

* [Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - used for testing and debugging.

* [Balsamiq](https://balsamiq.com/) - used for creating the wireframes in the design stage.

* [Coolors](https://coolors.co/) - used to find and compare colours that complimented one another.

* [Canva](https://www.canva.com/) - was used to design and create the logo, and also to resize images to specific dimensions.

* [Picresize](https://picresize.com/) - wa also used to resize images for less specific wants, such as 25% or 50% smaller.

* [Am I Responsive](http://ami.responsivedesign.is/) - used for testing the responsiveness of site and as the image found at top of page.
















**
**
**








# Soul Gym
----- One or two paragraphs providing an overview of your project. -----

Provide an inviting place for new and existing members to login/sign up to Soul Gym, see what classes are available and what Soul Gym is all about, learning that it is more than just a gym to go and get fit.

----- Essentially, this part is your sales pitch. -----

### User Experience (UX)
----- Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser. -----

* First Time visitor Goals
    * As a first time visitor, I want to clearly see the gym's feel, so I can gauge if it is the type of place i want to be.
    * As a first visitor, I want to be able to navigate through the entire site, comfortably and securely, to learn more about the gym, what they offer, where I can find it, and how to get in touch and become a member.
    * As a first time visitor, I want to be able to easily drop a message to the gym to arrange a tour to satisfy my needs and wants.

* Returning visitor Goals
    * As a returning visitor, I want to be able to login to my account at the gym.
    * As a returning visitor, I want to be able to learn more about the different classes that i may not have read about on my first visit.
    * As a returning visitor, I want to be able to book a class.

* Frequent User Goals
    * As a frequent user, I want to be able to get in touch about any issues I may want to know.
    * As a frequent user, I want to be able to book a class, and see if there are any changes to classes timetable.






Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X