<h1>Diamruid Sheeran's Personal Profile</h1>
<p>This is a personal profile website for me (Diarmuid Sheeran) to showcase some of my skills in a static HTML/CSS website.</p>
<p>The aim of the website is to give the user a brief introduction to what I am currently studying and what I hope to achieve.<br> 
It will give the user an oppertunity to download my CV. <br>
It will also give the user an oppertunity to leave feedback to help me improve my site.</p>

<img src="assests/images/Responsive.jpg" alt="picture of Website on differnet devices">

<h1>Features</h1>
<ul>
    <li><h2>Navigation</h2>
        <ul>
            <li>Positioned in the center at the top of the page in the header: Diarmuid Sheeran provides a link to the home page.</li>
            <li>This Logo also outlines to the user my name and what languages i am currently studying with the additions of the font awesome symbols of HTML, CSS, Javascript and Python.</li>
            <li>Underneath that is a navigation bar positioned in the center of the page with three seperate links to the home page, a cv download page and a feedback form page.</li>
            <img src="assests/images/header-navigation.jpg" alt="picture of header navigation"> 
            <li>The footer at the bottom of the page contains all links provided in the website. <br>
            This allows users to navigate without having to return to the header of the page.</li>
            <li>The Footer also contains my email address allowing interested user a way of contacting me.
            </li>          
            <img src="assests/images/footer-navigation.jpg" alt="picture of footer navigation">
            <li>When viewing the site on a desktop monitor links are provided on both the left and right of the main section centered either side of the main section image.<br>
            These Links will open up either my Github page or my Linkedin Page in a new tab.</li>
            <img src="assests/images/main-section-navigation.jpg" alt="picture of main section navigation">
            <li>When viewing the images on a mobile device a justify content wrap feature was used to position the contnet for the main section on top of one another for a more responsive design.</li>
            <img src="assests/images/mobile-device-navigation.jpg" alt="picture of main section navigation used on a mobile device">
            <li> All navigation is clealry named sized and styled for ease of use while navigating throught the site.</li>
        </ul>
    </li>
    <br>
    <li><h2>Download Button</h2>
        <ul>
            <li>The purpose of the download button is to allow a user to download a copy my CV.</li>
            <li>I added a download link to a pdf file i saved in a folder called data.</li>
            <li>The download button was made large to emphasise the purpose of the download page and entice the user to download a copy of my CV.</li>
            <li>The download button changes it's properties when hovered over and the mouse cursor is changed to a pointer.</li>
            <img src="assests/images/download-button.jpg" alt="picture of download button">
            <img src="assests/images/download-button-highlighted.jpg" alt="picture of download button highlighted">
        </ul>
    </li>
    <br>
    <li><h2>Feedback Form</h2>
        <ul>
            <li>The feedback form allows the user to input their name, email and write in a text area to submit feedback on my work.</li>
            <li>There are 3 standered text input fields with 1 larger text area field</li>
            <li>There is a submit button underneath the input fields that allows the user to submit the data they have entered.</li>
            <li>When the submit button is hovered over its properties change and the mouse changes to a pointer.</li>
            <img src="assests/images/feedback-form-container.jpg" alt="picture of feedback form">
            <img src="assests/images/submit-button-highlightedjpg.jpg" alt="picture of submit button highlighted">
        </ul>
    </li>
    <li><h2>Transform and Transition Properties</h2>
        <ul>
            <li>To create a more interactive UI design some transorm and transition properties were added.</li>
            <li>The Github and Linkedin links will grow both left and right while keeping the text centered using a transition technique is css. </li>
            <li>Using hover:hover allows the user to not get these effects on smaller devices that dont have a mouse to hover over. This avoided any bad UI implications.</li>
            <img src="assests/images/github-highlight.jpg" alt="picture of github link highlighted">
            <img src="assests/images/linkedin-highlight.jpg" alt="picture of linkedin link highlighted">
            <li>When the page loads the about me section floats into position before doing a full 360 degree flip.</li>
            <li>This is achived by using keyframe, transform and translate3d in css.</li>
            <li>The aim of this is to instantly engage the user and create intreague about the site.</li>
            <li>Click the gif below for a demonstration.</li>
            <img src="assests/images/loading-page.gif" alt="picture of the loading page in gif format on loop">
        </ul>
    </li>
<br>

<h1>Testing</h1>
<ul>
    <li>I tested the website worked on different web browsers such as Chrome, Edge and Firefox.</li>
    <li>I tested and confiremd the responsive nature of the site on different devices such a mobile device, a tablet and a desktop computer.</li>
    <li>I confirmed that the the navigation bars direct the user to the correct destination.</li>
    <li>I tested the download capabilities of my download link and confirmed that it downloads my CV.</li>
    <li>I confirmed that the Linkedin and the Github links take the user directly to my respective pages.</li>
    <li>I have tested the form and confirmed that it takes in inputs and submits it to the Code Institute form dump.</li>
</ul>

<br>

<h1>Bugs</h1>
<h2>Solved Bugs</h2>
<ul>
    <h3>Problem:</h3>
    <li>When I was trying to make my website responive on a tablet i had problems lining the 3 divs for the main section in a line verticaly.</li>
    <h3>Solution:</h3>
    <li> I figured out that by changing the width from 33% of the screen to 100% fixed the issue</li>
   <h3>Problem:</h3>
    <li>I had issue lining up the logo on the header with smaller devices because of the large text size.</li>
    <h3>Solution:</h3>
    <li>I fixed this by moving all the font awsome onto a new line to keep it space apropriatly with my name.</li>
    <h3>Problem:</h3>
    <li>When using the site on a mobile device i noticed that when the github and linkedin links were clicked and I returned to the site they would permanently have changed there properties because of the trasition.</li>
    <h3>Solution:</h3>
    <li> I fixed this by adding the hover:hover syntax to make sure this feature was only availble on devices with the capabilities of hovering.</li>
</ul>

<br>

<h1>Valedator Testing</h1>
<ul>
    <li>HTML</li>
        <ul>
            <li>No Issues found on W3C HTML Validator</li>
        </ul>
</ul>
<ul>
    <li>CSS</li>
        <ul>
            <li>No Issues found on W3C HTML Validator</li>
        </ul>
</ul>
<ul>
    <li>HTML</li>
        <ul>
            <li>No Issues found on jigsaw.w3.org Validator</li>
        </ul>
</ul>
<ul>
    <li>CSS</li>
        <ul>
            <li>No Issues found on jigsaw.w3.org Validator</li>
        </ul>
</ul>

<ul>
    <li>Accessibility</li>
        <ul>
            <li>I confirmed that my colors and fonts are readable by using the lighthouse tool for each page scoring 100 in accessibility on all 3 pages.</li>
            <img src="assests/images/lighthouse-home.jpg" alt="picture of github link highlighted">
            <br>
            <img src="assests/images/lighthouse-cv.jpg" alt="picture of github link highlighted">
            <br>
            <img src="assests/images/lighthouse-feedback.jpg" alt="picture of github link highlighted">
        </ul>
</ul>

<br>
<h1>Deployment</h1>
<ul>
    <li>This site  was deployed to GitHub pages</li>
        <ul>
            <li>In the github repository of Personel Profile navigate to the settings tab.</li>
            <li>On the left-hand side navigation bar click on the Pages tab.</li>
            <li>Click on the dropdown menu for branches and select main.</li>
            <li>Reresh the page.</li>
            <li>The page provided a link to the completed website.</li>
        </ul>
    <li>The link to the finished website can be found by clicking the link to <a href="https://diarmuidsheeran.github.io/Personal-Profile/">Diarmuid Sheeran's Personal Profile</a></li>
</ul>

<h1>Credits</h1>
<ul>
    <li>Contet</li>
        <ul>
            <li>Some of the HTML and CSS used in the general layout of the web page was taken from the <a href="https://diarmuidsheeran.github.io/love-running/" target="_blank">Love Running</a> project.</li>
            <li>The flex direction syntax along with some other CSS styling were taken from <a href="https://www.youtube.com/watch?v=Xm4BObh4MhI&t=8897s\" target="_blank">Code with Ania KubówCode's</a> youtube video.</li>
            <li>The form was created and styled following the guidelines from both Ania's youtube video linked above and <a href="https://www.w3schools.com/css/css_form.asp" target="_blank">W3 Schools Website.  </a></li>
            <li>The @Keyframe property for the about me section to work on the loading screen was taken from the <a href="https://diarmuidsheeran.github.io/love-running/" target="_blank">Love Running</a> project.</li>
            <li>The translate3d and transform properties were both taken from the <a href="https://www.w3schools.com/css/css3_3dtransforms.asp" target="_blank">W3 Schools Website.</a></li>
            <li>The code for the download button was inspired by <a href="https://www.youtube.com/watch?v=mwqz0TOSKI8" target="_blank">Kode youtube video.</a></li>
            <li>The code to stop the hover feature on non hoverable devices was inspired by <a href="https://www.youtube.com/watch?v=uuluAyw9AI0&t=347s" target="_blank">Kevin Powells </a>youtube video.</li>
        </ul>
<br>
    <li>Media</li>
         <ul>
            <li>The Image for the feedback form was taken from <a href="https://pixabay.com/illustrations/fax-white-male-3d-model-isolated-1889009/" target="_blank">Pixelbay.</a> </li>
            <li>The image for the cv download page was taken from<a href="https://pixabay.com/illustrations/globe-space-galaxy-data-technology-6858907/" target="_blank">Pixelbay.</a></li>
            <li>The image on the index page was taken from my own personal gallery.</li>
            <li>The image of the CSS certification in the footer of each web page was given by<a href="https://jigsaw.w3.org/css-validator/" target="_blank">Jigsaws CSS Validation Service</a> on retrieving 0 errors for my CSS Code.</li>
            <li>All images were resized using the built in feature in windows.</li>
            <li>All Screenshots used in the Readme.md file were pasted to paint and cropped for what ever purpose needed using microsofts built in image editor feature.</li>
            <li>The gif was created using a free trial version of the <a href="https://www.movavi.com/adv/screenrecorder.html?utm_campaign=619742607&campaignid=619742607&adgroupid=59044575104&gclid=Cj0KCQjw2v-gBhC1ARIsAOQdKY1fGoOIxtmj-xfXWHdbJi21gOLP9PFAwsSbkjqp7NGL_vZMLSJWYyUaAlGhEALw_wcB" target="_blank">Movavi</a> screen recorder tool.</li>
        </ul>
</ul>











