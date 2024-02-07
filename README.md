![Enebog art logo](assets/images/enebogart-logo.png)

Deployed version:
https://gustafenebog.github.io/CODE-project-1/index.html


##THE FIVE PILLARS OF WEB DESIGN BY JESSE JAMES GARRETT HAS BEEN USED FOR THE BELOW SECTION OUTLINING THE CORE FACTS ABOUT THIS WEBSITE:

**Strategy (goals to achieve and target audience)
This website allows the artist to market himself by showcasing his art and provide information about himself, where his art can be found including upcoming events and to provide a point of contact.
The external user is naturally people interested in the artist and like to view his art, view upcoming events, where to buy it etc.

**Scope (features)
Content requirement:
-- Display of artist logotype
-- High-resolution Images of portfolio art along with text
-- Short artist bio
-- Contact info.
-- Info on upcoming events
-- Ways of connecting with artist on social media, online gallery etc.
Function spec:
-- Zoom on Hover and clickable art for displaying larger, high-resolution image of art piece on separate page or on same screen with mode screen
-- One page website (ideally unless modal screen is not implemented) with header with logo and navbar always visible.
-- Links to upcoming events, social media, online gallery etc.

**Structure (information structure and logical grouping)
Since the users can be expected very often to not be very IT savvy (older and culturally oriented rather than technically oriented ) the website needs to be very simple (single page site) and intuitive and should remain so even if more content is being added. The solution for this is a single page website and with the logo and navbar always visible as well as a clean, simplistic uncluttered design
Interface navigation and Information 
Skeleton
Potential features to include:
-- A selection of the artist art-pieces organized in a rectangular grid.
-- Artist bio/about/contact info
-- Artist features
-- A call-to-action button linking to a “Get in touch forms/contact”
-- Link to external artist.
-- Online gallery


Skeleton (information presentation, navigation and features)
Potential features to include:
-- A slider/carousel
-- A selection of the artist art-pieces organized in a rectangular grid.
-- Artist bio/about/contact info
-- Artist features
-- A call-to-action button linking to a “Get in touch forms/contact”
-- Link to external artist.
-- Online gallery

![Wireframe](Wireframe-p1.png "initial wireframe")

**Surface (Colors, typography and design)
As this is an artist website showing of Art, the Surface Plane with its graphics is arguably more important than the sites functional features (providing they all work, that is) since this is to work in concert with and enhance the content/art.

**Design
The minimalistic, uncluttered, and sober graphics of the site are not only modern and user friendly but it does also provide the perfect setting for displaying art much like the simple white walls in a real art gallery.

**Colors
The Black and White color theme provides a color-neutral background that does not interfere with the color theme of the actual art. It also has the secondary benefit of not distracting or drawing attention to itself but rather to put all of the attention and focus on the art. 
One accent color, orange, has been used (away from the vicinity of the gallery section) on a “call to action”-button, again, the effect of the accent color becomes more efficient with the otherwise neutral color scheme.
Art is classically displayed on an either white or black background. We use a white background for the overview grid with large thumbnails and a black background when an image has been clicked and being displayed full size. The black background on the last two sections (“About” and “Contact”) sets these two sections apart from the rest of the site and allow the footer to “return” to a white without any dividing line.
Font color on the black background sections (“About” and “Contact”) is set to a light grey rather than white for making user experience easier on the eyes according to article: When to Use White Text on a Dark Background ( https://uxmovement.com/content/when-to-use-white-text-on-a-dark-background/#:~:text=The%20kind%20of%20text%20that,can%20strain%20the%20user's%20eyes. ) A photoshop color picker on a example screen shots was used to determine hex code () 
Used font color to not be white but rather grey according to the following article. Using a color picker to determine what white gitpod was using in its dark mode

**Typography
Care has been taken to match the font for the headers with that of the paragraphs. A match making tool was used pairing for example x with y however...


------
##TECHNICAL INFORMATION
**Commit messages
A review of the commit messages for the first 12 days of programming showed that the soft rule of max 50 characters was broken, on average, with 10 characters. Furthermore, the hard rule of max 72 characters was (out of the 44 commits) broken in 30% of the commits. The commits after this point was improved both in number of characters and in terms of text.

Decrease loading time for images
The large images was reduced to the approximate size it was to be displayed at. The Hero image was set to to 2000px based on a largest common desktop screen size width of 1920px. The width of the gallery images displayed on index.html was set to 900px. This was determined based on a three row column with a 150% “zoom on hover”: 1,5*(1920/3)=960. Taking this number minus padding and we would end up with roughly 900 px. 
A further adaption of image sizes for smaller screens has not yet been carried out due to time constraints.
The idea was further to reduce loading times by zipping files using “tinyPNG” or similar to create .zip or .rar files however efforts to find out if this was at all possible was abandoned due to time constraint reasons.

**Credits
This webpage has its first implementation in a Squarespace-version of this site (Also including the artist art courses which is omitted on this site). This new implementation has improved on weak points of the first implementation which was:
The all-important art was not displayed directly upfront but one or two clicks away
This webpage has its first implementation in a Squarespace-version of this site (Also including the artist art courses which is omitted on this site). This new implementation has improved on weak points of the first implementation which was:
The all-important art was not displayed directly upfront but one or two clicks away
-- Even after one click all of the art was not displayed in one single grid but required the user to step through each gallery one picture at a time.
-- The about and contact sections was separated albeit they intuitively belong together 
Although the header and footer was decided beforehand it did almost perfectly coincided with that of the “love running”-site so this was used as a code base.

**Testing
Testing has been carried out using:
-- Manual testing of site (checking links, different devices etc.)
-- CSS and code was tested using a free software from W3C https://jigsaw.w3.org/css-validator/
-- Only Java script!?: (https://jshint.com/)
-- Lighthouse (Chrome developer tools) to test for performance, accessibility, progressive web apps, SEO, and more.
-- Githubs built in code-beautify function

Fixed bugs:
-- Change in logo and header height would not come through due to conflicting css-rules 
-- Page overflowed horizontaly (slider appeared)

Remaining bugs
-- the "underline on hoover" has stopped working at some version of the code.
-- Box shadow under header does not disapear with the responsive design for larger screensizes.

Remaining to do list
-- Create link back back to index.html from the large, high-resolution image page (braide-flask.html).
-- Make logo slightly larger, header slightly higher and push nav elements further down
-- Adjust start of main content as to not hide under header
-- Delete unused image files(2000px)
-- Clean up code (delete commented out code)
-- Delete unused files
-- Fix gallery grid
-- Fix About and contact
-- Clean up surplus CSS-rules
-- Clean up row structure (delete multiple empty rows etc.)
-- Add slider/carousel for the Hero image
-- ...and OMG there is more!
