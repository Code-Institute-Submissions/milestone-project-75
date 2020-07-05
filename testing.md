# Testing
[back to README.md file](https://github.com/Gregory4321/milestone-project-1/blob/master/README.md)
## Table of Contents:
* [W3C Validators](#w3c-validators)
* [DevTools](#devtools)
* [Testing](#testing)
    * [User Stories from User Experince (UX) Section](#testing-user-stories-from-user-experience-(ux)-section)
        * [First Time Visitor Goals](#first-time-visitor-goals)
    * [User Testing](#user-testing)
        * [1. Peer Code Review](#1-peer-code-review)
        * [2. User Review](#2-user-review)
***

Testing this site was conducted using various methods to identify any bugs throughout the site.

## W3C Validators

The W3C Markup Validator and W3C CSS Validator Services were used to validate the code on all of the pages, to make sure that there were no syntax errors in the project.

* [W3C Markup Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## DevTools

Google Chrome DevTools was used for vigorous testing of the site. It was used for various different reasons.
    
* It tested for the responsiveness of the site across multiple screen resolutions
    * It revealed an issue with the social links and navbar links. Media queries were added to control and ensure size and placement on different screen sizes. 
    * The Bootstrap grid system was updated and implemented more often to control how the columns responded.
    * Containers were discovered to be of good use to keep structure flowing.
* Debugging
    * Highlighted incorrect use of styling and/or Bootstrap.

## Testing 

### User Stories from User Experience (UX) Section

* First Time Visitor Goals:
    * As a first visitor, I want to be able to navigate through the entire site, comfortably and securely.
        * When the site is first loaded, a navbar is presented clearly and easily readable. Users are made to feel comfortable with the simplicity and cleaniness of the site. 
        * A hero image underneath contains overlaying text of a welcoming and informative manner. There is also a call to action button to join the gym now. 
        * Content hinting provides evidence to scroll down.
        * The user is also invited through the navbar to click between pages, where the navbar emains present on all pages, so the security of knowing you can go back at anytime is there.

    * As a first time visitor, I want to be able to easily message the gym with any initial queires that I may have.
        * At first sighte of the home page, a navbar clearly indicates the option to 'Contact'.
        * Upon clicking contact, the user is presented with a minimal form to avoid any stress of too much information required.
        * The form encourage the user with a heading, and asks for name, email and message, follwed by a clear 'Submit' button.

    * As a first time visitor, I want to learn more about the gym and what is available.
        * After arriving at the clear home page, the navbar presents two clear options of 'Classes' and 'About'. Content hinting is also found on the home page where the user can scroll down, read testimonials, and revealed an image displaying the text 'Coming Soon' - 'SPA'.
        * Upon using the navigation to other pages, the user can read - along side an image - what classes are available and what to expect. They can also read in a vertical manner presented in cards, a flowing story of the history and birth of the gym.

* Prospective Gym Member:
    * As a prospective gym member, I want to know how much membership costs.
        * When the user first loads the site, overlaying the eye catching hero image, text clearly displays the cost of a membership.
    * As a prospective gym member, I want to be able to book a tour.
        * At the bottom of each page, in the footer, a user can clearly read "Want to see more? Book a tour here" with a calender icon that is clickable.
        * Using this link directs the user to the contact page, where they are aloso reminded that they can book a tour in the heading for the contact form.
        * The user is expected to fill out this basic form to request a tour.
    * As a prospective gym member, I want to see what classes and facilities the gym offers.
        * The user from the home page is invited to scroll down the page, which reveals an image informing of the coming soon of a spa.
        * Once navigated to the classes page using the clear navbar, the user can see what classes are available and what the each offer.
    * As a prospective gym member, I want to feel comfortable and informed that this gym is right for me.
        * The entire site is created to provide a welcoming and calming feeling. The user can navigate to the about page, where they can read an inspiring story of the owners tribulations and beginnings to start the idea of what is now 'Soul Gym'.
    * As a prospective gym member, I want to be able to contact and locate the gym.
        * As written aboove, once the user has used the navigation to the contact page, a form is presented to contact the gym. Content hinting is also used her to have the user scrol to reveal the gyms contact details, along woth an interactive map.
    * As a prospective gym member, I want to be able to sign up to the gym.
        * Using the clear and tidy navbar, the user can follow it to the Register Page, where a form is offered to be filled out creating a username, giving of email address, and password creation along with a password confirm.
        * The user cannot submit a registration until all of the form is filled out correctly.
        * The user is the redirected to a thank you page and a button to return them to the home page. The navbar is also stilll of use on this page.

* As a member of Soul Gym:
    * As a member of Soul Gym, I want to be able to login to my account with the gym.
        * The user is clearly invited through the use of the navbar to head over to the login page.
        * Here, a basic form is presented asking for username/email address and password.
    * As a member of Soul Gym, I want to be able to book a class.
        *Once the user knows what class they would like to book, they have too options to get to the same outcome. 
        * At the top of the 'classes' page, the user can clearly see a call to action button offering to 'Book Now'.
        The navigation bar can be followed as well to the same place as the call to action button, that being the contact page. The user then has to fill out the form simply stating name email and message, ie what class and what time slot they want to book. 
    * As a member of Soul Gym, I want to be kept up to date on any new facilities and initiatives the gym is working towards.
        * When following th einvitation to scroll down the page of t eh home page, a large image presents information of a coming soon spa. This section will be used to offer any new information of up and coming events.
    * As a member of Soul Gym, I want to be able to easily access a weekly class timetable, so I can plan my visits.
        * The user can use the navbar from any page. With this, once landing upon the 'classes' page, and use the scroll proved with content hinting, reveal the timetable of classes.
    * As a member of Soul Gym, I want to be able to submit any questions, feedback or complaints.
        * The navbar cleary presents a contact option. A form is first seen after the heading of 'Got a question'. The user can use this form for any query, complaint or feedbak they like.

[Back to Top](#table-of-contents)

### User Testing

#### Peer-code-review

My project was submitted to the peer-code-review channel page of the Slack community for Code Institute. The overall reviews were positive, providing compliments of dynamic and fluid structure to the scrolling image of the homepage, and a clean and tidy spacing of the elemtns of the page.

Improvements were also suggested, notifying of a bug with the navbar when viewed on Firefox, and advise of checking if Bootstraps container-fluid is neccesary over just a container. 

#### User Review

The general reviews of my page were positive, commenting on the inviting colours used. The structure was complemented along with the ease of navigation, and the site not being too busy with colours and content.

