# Diamruid Sheeran's Personal Profile
This is a personal profile website for me (Diarmuid Sheeran) to showcase some of my skills in a static HTML/CSS website.

The aim of the website is to give the user a brief introduction to what I am currently studying and what I hope to achieve.

It will give the user an oppertunity to download my CV.

It will also give the user an oppertunity to leave feedback to help me improve my site.

![picture of Website on differnet devices](documentation/responsive.jpg)

## Contents
* [Features](#Features)
  * [Navigation](#Navigation)
  * [Download Button](#Download-Button)
  * [Feedback Form](#Feedback-Form)
  * [Transform and Transition Properties](#Transform-and-Transition-Properties)

* [Testing](#Testing)

* [Bugs](#Bugs)
  * [Solved Bugs](#Solved-Bugs)

* [Validator Testing](#Validator-Testing)

* [Accessibility](#Accessibility)

* [Deployment](#Deployment)

* [Credits](#Credits)
  * [Content](#Content)
  * [Media](#Media)





## Features
### Navigation
* Positioned in the center at the top of the page in the header: Diarmuid Sheeran provides a link to the home page.
* This Logo also outlines to the user my name and what languages i am currently studying with the additions of the font awesome symbols of HTML, CSS, Javascript and Python.
* Underneath that is a navigation bar positioned in the center of the page with three seperate links to the home page, a cv download page and a feedback form page.
![picture of header navigation](documentation/header-navigation.jpg)

* The footer at the bottom of the page contains all links provided in the website.
  This allows users to navigate without having to return to the header of the page.
* The Footer also contains my email address allowing interested user a way of contacting me.       
![picture of footer navigation](documentation/footer-navigation.jpg)

* When viewing the site on a desktop monitor links are provided on both the left and right of the main section centered either side of the main section image.

    These Links will open up either my Github page or my Linkedin Page in a new tab.
![picture of main section navigation](documentation/main-section-navigation.jpg)

* When viewing the images on a mobile device a justify content wrap feature was used to position the contnet for the main section on top of one another for a more responsive design.

![picture of main section navigation used on a mobile device](documentation/mobile-device-navigation.jpg)
* All navigation is clealry named sized and styled for ease of use while navigating throught the site.


### Download Button

* The purpose of the download button is to allow a user to download a copy my CV.
* I added a download link to a pdf file i saved in a folder called data.
* The download button was made large to emphasise the purpose of the download page and entice the user to download a copy of my CV.
* The download button changes it's properties when hovered over and the mouse cursor is changed to a pointer.
![picture of download button](documentation/download-button.jpg)
![picture of download button highlighted](documentation/download-button-highlighted.jpg)

### Feedback Form

* The feedback form allows the user to input their name, email and write in a text area to submit feedback on my work.
* There are 3 standered text input fields with 1 larger text area field
* There is a submit button underneath the input fields that allows the user to submit the data they have entered.
* When the submit button is hovered over its properties change and the mouse changes to a pointer.
![picture of feedback form](documentation/feedback-form-container.jpg)
![picture of submit button highlighted](documentation/submit-button-highlightedjpg.jpg)

### Transform and Transition Properties

* To create a more interactive UI design some transorm and transition properties were added.
* The Github and Linkedin links will grow both left and right while keeping the text centered using a transition technique is css.
* Using hover:hover allows the user to not get these effects on smaller devices that dont have a mouse to hover over. This avoided any bad UI implications.
![picture of github link highlighted](documentation/github-highlight.jpg)
![picture of linkedin link highlighted](documentation/linkedin-highlight.jpg)

* When the page loads the about me section floats into position before doing a full 360 degree flip.
* This is achived by using keyframe, transform and translate3d in css.
* The aim of this is to instantly engage the user and create intreague about the site.
* Click the gif below for a demonstration.
![picture of the loading page in gif format on loop](documentation/loading-page.gif)



## Testing

* I tested the website worked on different web browsers such as Chrome, Edge and Firefox.
* I tested and confiremd the responsive nature of the site on different devices such a mobile device, a tablet and a desktop computer.
* I confirmed that the the navigation bars direct the user to the correct destination.
* I tested the download capabilities of my download link and confirmed that it downloads my CV.
* I confirmed that the Linkedin and the Github links take the user directly to my respective pages.
* I have tested the form and confirmed that it takes in inputs and submits it to the Code Institute form dump.

## Bugs

### Solved Bugs

#### Problem:
* When I was trying to make my website responive on a tablet i had problems lining the 3 divs for the main section in a line verticaly.
#### Solution:
* I figured out that by changing the width from 33% of the screen to 100% fixed the issue
#### Problem:
* I had issue lining up the logo on the header with smaller devices because of the large text size.
#### Solution:
* I fixed this by moving all the font awsome onto a new line to keep it space apropriatly with my name.
#### Problem:
* When using the site on a mobile device i noticed that when the github and linkedin links were clicked and I returned to the site they would permanently have changed there properties because of the trasition.
#### Solution:
* I fixed this by adding the hover:hover syntax to make sure this feature was only availble on devices with the capabilities of hovering.

## Valeiator Testing

* HTML
  * No Issues found on W3C HTML Validator
* CSS
  * No Issues found on W3C HTML Validator

* HTML
  * No Issues found on jigsaw.w3.org Validator
* CSS
  * No Issues found on jigsaw.w3.org Validator

## Accessibility

* I confirmed that my colors and fonts are readable by using the lighthouse tool for each page scoring 100 in accessibility on all 3 pages.

![picture of github link highlighted](documentation/lighthouse-home.jpg)
![picture of github link highlighted](documentation/lighthouse-cv.jpg)
![picture of github link highlighted](documentation/lighthouse-feedback.jpg)

## Deployment

* This site  was deployed to GitHub pages
* In the github repository of Personel Profile navigate to the settings tab.
* On the left-hand side navigation bar click on the Pages tab.
* Click on the dropdown menu for branches and select main.
* Reresh the page.
* The page provided a link to the completed website.
* The link to the finished website can be found by clicking the link to [Diarmuid Sheeran's Personal Profile](https://diarmuidsheeran.github.io/Personal-Profile/)


## Credits
### Content
* Some of the HTML and CSS used in the general layout of the web page was taken from the [Love Running](https://diarmuidsheeran.github.io/love-running/) project.

* The flex direction syntax along with some other CSS styling were taken from [Code with Ania KubówCode's](https://www.youtube.com/watch?v=Xm4BObh4MhI&t=8897s) youtube video.

* The form was created and styled following the guidelines from both Ania's youtube video linked above and [W3 Schools Website.](https://www.w3schools.com/css/css_form.asp)

* *The @Keyframe property for the about me section to work on the loading screen was taken from the [Love Running](https://diarmuidsheeran.github.io/love-running/) project.

* The translate3d and transform properties were both taken from the [W3 Schools Website.](https://www.w3schools.com/css/css3_3dtransforms.asp)

* The code for the download button was inspired by [Kode youtube video.](https://www.youtube.com/watch?v=mwqz0TOSKI8)

* The code to stop the hover feature on non hoverable devices was inspired by [Kevin Powells](https://www.youtube.com/watch?v=uuluAyw9AI0&t=347s) youtube video.

### Media
* The Image for the feedback form was taken from [Pixelbay.](https://pixabay.com/illustrations/fax-white-male-3d-model-isolated-1889009/)

* The image for the cv download page was taken from [Pixelbay.](https://pixabay.com/illustrations/globe-space-galaxy-data-technology-6858907/)

* The image on the index page was taken from my own personal gallery.

* All images were resized using the built in feature in windows.

* All Screenshots used in the Readme.md file were pasted to paint and cropped for what ever purpose needed using microsofts built in image editor feature.

* The gif was created using a free trial version of the [Movavi](https://www.movavi.com/adv/screenrecorder.html?utm_campaign=619742607&campaignid=619742607&adgroupid=59044575104&gclid=Cj0KCQjw2v-gBhC1ARIsAOQdKY1fGoOIxtmj-xfXWHdbJi21gOLP9PFAwsSbkjqp7NGL_vZMLSJWYyUaAlGhEALw_wcB) screen recorder tool. 












