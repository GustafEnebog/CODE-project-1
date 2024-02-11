
Compression of word files
Mix of black and white boxes in form!!!
Glöm inte atts kapa hyperlänkar som Bonsai
Saved jpg with progressive check box checked so that a lower grade resolution image load first before the higher res…
Add screenshots to readme


![Image of site on different sized devices.](assets/images/enebogart-logo.png)

# My Art portfolio Page
This art portfolio website is a shop window for my art and a place where I can market myself as an artist.
Users of this website will be able to view a selection of my art and upcoming events. It also serves as a point of contact springboard the users to the London based online gallery, artfinder.com where my art can be purchased as well as links to further social media.

[View the live project here.](https://gustafenebog.github.io/CODE-project-1/index.html)


## Features
![Screenshot of header](assets/images/enebogart-logo.png)


![Screenshot of the navbar for small devices.](assets/images/enebogart-logo.png)
![Screenshot of the navbar for large devices.](assets/images/enebogart-logo.png)

### The header with the navigation bar

  + The header features the artist Enebog-logo to the left and the four navigation links: Home, Works, About, Contact (for larger devices) or the “hamburger” icon (for smaller devices) to the right.
  + This is a single page scrolling website (with the exception of the individual art-piece-display pages the user is taken to when clicking on an art piece on the main page) that takes the user to the correct section, within the page, when a link is clicked.
  + The header with its nav elements is always fixed  (except on the individual art-piece-display pages) and creates therefore a quick and easy to understand navigation experience.
  + The Enebog-logo also doubles as an extra home button.
  + On larger devices the navigation is lined up in a row on the right side of the header.
  + The navigation links for large screen devices are being underlined when hoovered over.
  + A click anywhere on an individual art page takes the user back to the last place he was at on the main page.  


![Screenshot of whero image for small and large devices.](assets/images/enebogart-logo.png)

+ The top of the page “introductory”-“attention grabbing”-“lateset”image
  + The top of the page features a high-resolution image of an art piece with a text overlay to give the user a wow-effect to grab the users attention
  + MORE HERE

![Screenshot of works for small and large devices.](assets/images/enebogart-logo.png)

### The Works-section
  + The Works-section displays three galleries with nine art pieces each displayed in a 3x3 grid
  + The images of the art-pieces zooms to a larger size when hovered and can be clicked if the user want to see a larger display of the art piece. The user is then taken to a separate display page (unique for each art piece) where the art is annotated and display in a larger size. Currently the display page of only one art pieces has been implemented which is the first image (braided flask).

![Screenshot of works for small and large devices.](assets/images/enebogart-logo.png)

### The full-size display-page
  + A selection of the artist art-pieces organized in a rectangular grid.

![Screenshot of about for small and large devices.](assets/images/enebogart-logo.png)

### The ABOUT-section
  + This section features a photo of the artist together with a short bio explaining his process, favorite motives and mediums and his reasons for drawing and painting.

![Screenshot of contact for small and large devices.](assets/images/enebogart-logo.png)

### The Contact-section
  + The contact section provides postal address, email and telephone number to the artist as well as non-interactive map showing where in Europe the artist is based. All fields (except subject) are reqiered to be filled in and filled in correctly before the message is allowed to be submitted.
  + The contact section also provide a form which the user can use as a way of reaching out to the artist directly.
  + A call-to-action button linking to a “Get in touch forms/contact ”SCREEN SHOOT OF FOOTER
![Screenshot of Footer for small and large devices.](assets/images/enebogart-logo.png)

### The Footer
+ xxxxxxx
  + The footer contain icons linking to all the places the artist can be found in social media (not yet implemented) including a link to the London based online gallery, Artfinder, where Enebog’s art can be acquired. 

+ Features remaining to be implemented
  + Make carousel/slide show of top of the page image 
  + Responsive design on the art display page to make the image (with annotation) fill the screen without overflowing 







## Design
+ One page website (ideally unless modal screen is not implemented) with header with logo and navbar always visible.
Since the users can be expected very often to not be very IT savvy (older and culturally oriented rather than technically oriented ) the website needs to be very simple (single page site) and intuitive and should remain so even if more content is being added. The solution for this is a single page website and with the logo and navbar always visible as well as a clean, simplistic uncluttered design

![Wireframe](Wireframe-p1.png "initial wireframe")

As this is an artist website showing of Art, the Surface Plane with its graphics is arguably more important than the sites functional features (providing they all work, that is) since this is to work in concert with and enhance the content/art.
### Design
The minimalistic, uncluttered, and sober graphics of the site are not only modern and user friendly for less it-savvy artist lovers but it does also provide the perfect setting for displaying art much like the simple white walls in a real art gallery.
### Colors
The Black and White color theme provides a color-neutral background that does not interfere with the color theme of the actual art. It also has the secondary benefit of not distracting or drawing attention to itself but rather to put all of the attention and focus on the art. 
One accent color, orange, has been used (away from the vicinity of the gallery section) on a “call to action”-button, again, the effect of the accent color becomes more efficient with the otherwise neutral color scheme.
Art is classically displayed on an either white or black background. We use a white background for the overview grid with large thumbnails and a black background when an image has been clicked and being displayed full size. The black background on the last two sections (“About” and “Contact”) sets these two sections apart from the rest of the site and allow the footer to “return” to a white without any dividing line.
Font color on the black background sections (“About” and “Contact”) is set to a light grey rather than white for making user experience easier on the eyes according to article: When to Use White Text on a Dark Background ( https://uxmovement.com/content/when-to-use-white-text-on-a-dark-background/#:~:text=The%20kind%20of%20text%20that,can%20strain%20the%20user's%20eyes. ) A photoshop color picker on a example screen shots was used to determine hex code () 
Used font color to not be white but rather grey according to the following article. Using a color picker to determine what white gitpod was using in its dark mode

[Screenshot of color scheme.](assets/images/enebogart-logo.png)

[Screenshot of fonts used.](assets/images/enebogart-logo.png)

### Typography
Care has been taken to match the font for the headers with that of the paragraphs. A match making tool was used pairing for example x with y however...  fontpair.co
'Open Sans Regular400 font family with Montserrat as a fallback font and sans-serif as the second fallback font

'Open Sans Regular 400', 'Montserrat', sans-serif;
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,300;0,400;1,300;1,400&family=Open+Sans:ital,wght@0,300;0,400;1,300;1,400&family=Spectral+SC:ital,wght@0,300;1,200&display=swap');




## Technologies Used
+ HTML5
+ CSS3
+ [Google Fonts:](https://fonts.google.com/) To import font family ’XXXXXXXXX’ into the style.css file which is used on all pages.
  
Added fallback font sans-serif.
+ [Font Awesome:](https://fontawesome.com/) used in footer section to social icons and "hamburger"-icon in navbar for devices below a screens width of XXXXXXXXX.

Fontpair.coxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

+ [Krita:](https://krita.org/en/) Used for creating, editing and re-sizing images (bitmap art).
+ [Clip Studio Paint:](https://www.clipstudio.net/en/) Used for creating and editing vectorgraphics-art such as the Enebog-logo.
+ 
+ [Tiny PNG:](https://tinypng.com/) Compressing images.
+ 
+ [Am I Responsive:](http://ami.responsivedesign.is) Checking the responsiveness and generating the image in the beginning of this document showing my website on different devices/screensizes.
+ [GitPod](https://www.gitpod.io/) GitPod has been used as a cloud based IDE from which code was commited and pushed to GitHub.
+ [GitHub:](https://github.com/) GitHub is used to store the code that has been pushed from GitPod.


## Testing
### Manual testing
+ I have manually tested that:
	++ the links work and land you on the correct page or correct section within the page
	++ a wrong input, e.g. email address field without an @-sign receive a complaint as well as a form submission-button-click results in a confirmation page
 
  + I have tested that the links in the header works correctly.
  + I have tested that the navigation links work and the user is directed to the correct sections of the page.
  + I have tested that the navigation links change text colour when hovering over.
  + I have tested that the external link in the about section opens in a new tab and that the address is correct.
  + I have tested that name, email and message is required to submit the form in the contact section.
  + I have tested that the email input field must contain @ symbol to submit the form in the contact section.
  + I have tested that the form submit button change text colour when hovering over.
  + “zoom on hover” work in gallery-section
+ Browser testing
+ Manual testing has been carried out using different browsers: Chrome, Firefox and Safari 
+ Responsiveness
as well as different standard screen sizes testing the responsive design.
+ Validator testing
  + CSS and code was tested using a free software from W3C https://jigsaw.w3.org/css-validator/
  + Only Java script!?: (https://jshint.com/)
  + Lighthouse (Chrome developer tools) to test for performance, accessibility, progressive web apps, SEO, and more.
+ Githubs built in code-beautify function
### Validator Testing
+ All code was tested for syntactical errors with perfect results using official validators:
+ HTML using the the W3C validator
	+ CSS using Jigsaw

![Screenshot of the navbar for small devices](assets/images/enebogart-logo.png)
+ The website’s Accessibility was also tested using Chrome Dev tools official
+ 	
![Screenshot of the navbar for small devices](assets/images/enebogart-logo.png)

SCREENSHOT LIGHTHOUSE

![Screenshot of the navbar for small devices](assets/images/enebogart-logo.png)


 
### Bugs
+ Fixed bugs:
  + Change in logo and header height would not come through due to conflicting css-rules
  + Page overflowed horizontaly (slider appeared)
+ Remaining bugs
  + the "underline on hoover" has stopped working at some version of the code.
  + Box shadow under header does not disapear with the responsive design for larger screensizes.

+ YES BUCKET!!!
  + Create link "arrow" back back to index.html from the large, high-resolution image page (braide-flask.html).
  + Fix gallery grid
  + Fix About and contact
  + Adjust start of main content as to not hide under header
  + Right align send button
  + Make message field larger
  + Make first and last name field sideby side
  + Padding before gallery headlines
  + Padding before About section and between about and contact
  + Make background all the way down on gallery display page

+ Delete unused image files(2000px)
+ Clean up code (delete commented out code)
+ Delete unused files
+ Clean up surplus CSS-rules
+ Clean up row structure (delete multiple empty rows etc.)
+ ...and OMG there is more!

+ MAYBE BUCKET!
  + Make logo slightly larger, header slightly higher and push nav elements further down
  + Add slider/carousel for the Hero image
+ NO BUCKET

### Deployment
+ The site was deployed to GitHub pages. The steps to deploy are as follows:
  + Log in to GitHub and locate the GitHub Repository.
  + In the GitHub repository, navigate to the "Settings" tab.
  + In Settings, choose "Pages" from the left hand menu.
  + Under "Source", select branch "Main" and select folder "(Root)".
  + Click Save and the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.


+ Go to your GitHub repo and choose the **settings** tab and then **Pages** on the left-hand sidebar and then make sure that the following is set as below:
  + **Sources** is set to ‘Deploy from Branch’
  + **Main** branch is selected.
  + **Folder** is set to / (root)
+ Click save and go back to the **Code** tab and wait a few minutes for the build to finish. Make sure that you do not push to the repo during this time since this will cause the rebuild to fail.
+ Go to the **github-pages** under the **Deployment** section, further down on the right hand side.
+ Now you can see the URL to your deployed site under **Active deployments**. Click on the URL to go to your site. The URL will follow the following format: your-username.github.io/your project name/


### Miscellaneous
+ Commit messages
A review of the commit messages for the first 12 days of programming showed that the soft rule of max 50 characters was broken with 10 characters on average. Furthermore, the hard rule of max 72 characters was (out of the 44 commits) broken in 30% of the commits. The commits after this point was improved both in number of characters and in terms of text.
+ Loading time for images
  + The large images was reduced to the approximate size it was to be displayed at. The Hero image was set to to 2000px based on a largest common desktop screen size width of 1920px. The width of the gallery images displayed on index.html was set to 900px. This was determined based on a three row column with a 150% “zoom on hover”: 1,5*(1920/3)=960. Taking this number minus padding and we would end up with roughly 900 px. 
  + A further adaption of image sizes for smaller screens has not yet been carried out due to time constraints.
The idea was further to reduce loading times by zipping files using “tinyPNG” or similar to create .zip or .rar files however efforts to find out if this was at all possible was abandoned due to time constraint reasons.
## Credits
### Content
+ The code to make the social media links was taken from the CI Love Runnings Project.
+ Readme of
++ Coding Club
++ My Bonsai Page - mittnamnkenny

### Media
Zoom on hover
The five pillars of webdesign by Jesse James Garrett
This webpage has its first implementation in a Squarespace-version of this site (Also including the artist art courses which is omitted on this site). This new implementation has improved on weak points of the first implementation which was:
The all-important art was not displayed directly upfront but one or two clicks away
This webpage has its first implementation in a Squarespace-version of this site (Also including the artist art courses which is omitted on this site). This new implementation has improved on weak points of the first implementation which was:
The all-important art was not displayed directly upfront but one or two clicks away
+ Even after one click all of the art was not displayed in one single grid but required the user to step through each gallery one picture at a time.
+ The about and contact sections was separated albeit they intuitively belong together 
Although the header and footer was decided beforehand it did almost perfectly coincided with that of the “love running”-site so this was used as a code base.
Give credit for 2 code snippets
Change logo size! Might be reason for overflow
ami
### Acknowledgement
A special thanks to my mentor at Code Institute for most helpful input.

