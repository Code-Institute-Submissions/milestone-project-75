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
   * [Existing Features](#future-features)
   * [Future Features](#removed-features)
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

[Back to Top](#table-of-contents)

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

* [Unsplash](https://unsplash.com/) - used to find images for use across site.

* [Pexels](https://www.pexels.com/) - used to find images for use across site.

##### Tools

* [Google](https://www.google.co.uk/) - was used for research various techniques, styles and information.

* [Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - used for testing and debugging.

* [Google Maps](https://www.google.co.uk/maps) - used to embed a map to the whereabouts of the gym.

* [Balsamiq](https://balsamiq.com/) - used for creating the wireframes in the design stage.

* [Coolors](https://coolors.co/) - used to find and compare colours that complimented one another.

* [Canva](https://www.canva.com/) - was used to design and create the logo, and also to resize images to specific dimensions.

* [Picresize](https://picresize.com/) - wa also used to resize images for less specific wants, such as 25% or 50% smaller.

* [Am I Responsive](http://ami.responsivedesign.is/) - used for testing the responsiveness of site and as the image found at top of page.

#### Features

##### Existing Features

* Navbar - Featured across all pages, can be used for navigation between the pages of the site using the links on the right. These links also collapse down to a hamburger icon when at smaller screen sizes. The logo, found on the left, can be clicked on all pages and links directly to the home page.

* Footer - Also featured across all pages, the footer is used for imforming that the user can book a tour and provides a link in the fform of an icon to the contact page where said tour can be booked. This is found on the left third of the footeer. On the right third of the footer social icons can be found that link to required social page.

* Hero images -  These can be found across the three main pages (Home, Classes and About), and display reference to what page the user is on. There is also text displayed on top of the image, relating to the page, as well as a call to action button linking to desired pages - Register page from the Home and About pages, and Contact page from the Classes page, encouraging the user to register to the gym and book a class. The is also a hero image used on the homepage at the bottom to advertise the coming soon of a spa. This is to ensure the user that the gym is still a growing platform, forever moving forward.

* Testimonials - The 'Why Choose Us' section was created to showcase to the user wha other customers made of the gym and what it has to offer

* Classes Page - This page showcases what classes are available, informing the user what to expect from each class. It also contains a timetable that the user can use to decide what classes they can take on a particular day and time.

* About Page - This page was creatd to give the user a feeling of how the gym came about, providing a story into the feel of the gyms owner and what the gyms goals are

* Contact Page - This page presents a form to contact the gym about information, booking a class, booking a tour, and any other general enquiries. The user can also find the contact details of the gym below, with an interactive map that can be clicked on and viewed on a larger scale in a seperate tab.

* Forms - Forms were used on the login and register page. The user is invited to sign up to the gym by filling out the form, or alternatively sign in to their already crearted account.

* Join Now Button of Registration Form - Once the user has completed the registration form and clicks 'Join Now', they are redirected to an internal page providing them with feedback that the registration has gone through successfully. It is important to provide feedback to the user so they feel validated.

##### Future Features

* Gallery Page - A seperate page to showcase images of the gyms classes and innteractions with their customers. This would give the user a more concrete idea of how the gym operates through using friendly and fun images.

* Donate Page / Modal - As described in the story on the about page, the gym donates 20% of its earnings to help towards the rebuilding of the ashram that the owner was mentored in in Bangalore. A page where members and/or non-members can help contribute themselves towards the rebuilding of communities and temples.

* A more defined view of membership costs by perhaps creating a membership page containg different packages on offer.

[Back to Top](#table-of-contents)

#### Testing

Testing this site was cinducted mainly by myself, using various methods to identify any bugs throughout the site.