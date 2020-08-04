# Kimmy Kaminski 

Kimmy is an excellent musician with over 10 years experience. She has played in various bands over her career and is now offering music tuition in Bass, Guitar, Piano and Music Theory. She can provide friendly, tailored lessons to people of all ages and abilities at competitive prices. She posts videos on social media showcasing her talent and can provide virtual lessons where required.
 
## UX


This website is aimed at people who want to take music lessons. It was designed to be easily navigated, to make its purpose obvious without reading related documentation and to make information easily accessible by the user. The navbar provides clear links to each page and shows which page the user is on. The brand on the far left provides easy navigation back to the home page, which is useful in mobile view where the navbar is collapsed into a hamburger icon. The homepage provides a general overview of services required, with links to relevant site sections for more information. Contact information is easily found on the footer of each page and on the contact page. Users can quickly discern what the site is for, what services are offered, further information and how to get in touch.

User stories:
- As someone who wants to find out how Kimmy is qualified to teach music, there is a short biography on the home page which provides relevant information on her experience and qualifications.
- As someone who wants to find out what type of music lessons are available, there are icons for each lesson type on the home page, which link to further information on the tuition page about lesson format and prices.
- As someone who is interested is hiring a musician for a show or gig, there are videos and links to social media where Kimmy's playing is showcased, and contact information in the footer and on the contact page.
- As someone who wants to enquire about music lessons, there is contact informtation at the footer of each page, and a contact page with a form that can be submitted with a lesson enquiry.

Wireframes: wireframes/kkwireframes.pdf 

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- The Nav bar - allows users to easily navigate between pages of the site. In medium and large screens, the pages are listed across the left side of the nav bar, and on small screens the nav bar is collapsed into a hamburger icon which expands when clicked. The brand link on the far left provides easy navigation back to the home page, which is useful especially on small screens. 
- The hero image and text - allows users to get a feel for the tone and style of the site and encourages them to scroll further down the page as the heading text is visible on the first screen view.
- Biography text - allows users to find out a bit about Kimmy's experience and qualification to teach music.
- Photo icons with "learn more" buttons for each lesson type - allow users to find out what lessons are offered and get more information on each lesson type by clicking the "learn more" button which links to the relevant section of the tuition page.
- Videos - allows users to see Kimmy playing instruments to reinforce her qualification to teach.
- Footer - allows users to see contact information for Kimmy no matter what page of the site they are on.
- Tuition section - provides more detailed information to users on the types of tuition provided.
- Photo gallery - allows users to see pictures of Kimmy playing instruments either by herself or as part of a band to further reinforce her experience.
- Contact form - allows users to easily get in touch with Kimmy to enquire about lessons and provides a dropdown menu to select the type of enquiry. The form is user friendly and will not permit submission without all information present.

### Features Left to Implement
- Make the form inputs clear once the form is submitted. I tried to research how to do this, and think it involves JQuery which I am not familiar with yet, so this is something I can come back and change later in the course.
- Contact form - the current contact form does not function, in that it does not send an email to Kimmy with the user enquiry. This feature will be implemented once I have progressed to that stage of the course.
- Online lesson booking system.

## Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML5]
    - The project uses **HTML** language for the site content.

- [CSS]
    - The project uses **CSS** for the styling.

 - [GoogleFonts] (https://fonts.google.com/)   
    - The project uses **Google Fonts** for the text font, weight and sizing.

- [Bootstrap](https://getbootstrap.com/)
    - The project uses the **Bootstrap** toolkit to implement responsive design.

- [Fancyapps](https://fancyapps.com/fancybox/3/)
    - The project uses the **Fancyapps** to create a photo gallery carousel.    

- [JQuery](https://jquery.com)
    - The project uses **JQuery** for the fuction of the fancybox photo gallery.


## Testing
Manual testing carried out:

1.  Navbar:
    1.  Click on the Tuition page link
    2.  Click on the Gallery page link
    3.  Click on the Contact page link
    4.  Click on the Home page link
    5.  Click on the Brand link
    6.  In mobile view click on the hamburger menu icon
    7.  Click on the Tuition page link
    8.  Click on the Gallery page link
    9.  Click on the Contact page link
    10. Click on the Home page link
    11. Click on the Brand link

2.  Music Lesson icons:
    1.  Go to the Home page
    2.  Click on the "Learn more" button on the Bass icon
    3.  Click on the "Learn more" button on the Guitar icon
    4.  Click on the "Learn more" button on the Piano icon
    5.  Click on the "Learn more" button on the Music Theory icon

3.  Video on Home page:
    1.  Go to the Home page
    2.  Press play on the embedded YouTube video

4.  Social Media link:
    1.  Go to the Footer
    2.  Click on the Facebook link
    3.  Click on the Instagram link
    4.  Click on the YouTube link 

5.  Photo Gallery:
    1.  Go to the Gallery page
    2.  Click on the first photo to ensure it opens in full view
    3.  Scroll through the carousel to view every photo to ensure each photo appears with correct caption

6.  Video Gallery:
    1.  Go to the Gallery page
    2.  Press play on the first embedded YouTube video to ensure it plays
    3.  Press play on the first embedded YouTube video to ensure it plays

7. Contact form:
    1. Go to the Contact page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with no first name and verify that a relevant error message appears
    3. Try to submit the form with no last name and verify that a relevant error message appears
    3. Try to submit the form with no phone number and verify that a relevant error message appears
    3. Try to submit the form with no email address and verify that a relevant error message appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

The HTML code was validated using W3C HTML Validator and the following errors were flagged:
-   The <button> element could not be a descendant of the <a> element. 
    Fix: I created a form with a button inside and put the link in the action attribute.
-   The inline frameborder styling in the <iframe> element was flagged as redundant.
    Fix: styled the border using CSS.

The CSS was validated using W3C CSS Validator and no errors were found.

The site has been tested on the following browsers and devices:-
1.  Google Chrome
2.  Mozilla Firefox
3.  Safari
4.  Apple MacBook Air 
5.  Toshiba Windows laptop
6.  Apple iPad
7.  Huawei Mate 20 pro 
8.  Samsumg Galaxy S7 
9.  Apple iPhone

### Responsive design:

# Home:
    -   On large and medium screens the navbar links are displayed along the top left hand side of the screen. The music lesson icons are then displayed two per row.
    On small screens, the navbar links collapse into a hamburger icon, with the brand link still viable on the left hand side, providing easy access back to the home page.
    The music lesson icons are then displayed stacked one on top of the other. 

# Footer:
    -   On large ad medium screens the contact info and social links are displayed in line, but on small screens the social links are displayed below the contact details.

# Tuition:
    -   On large and medium screens, the tuition sections are displayed with the image to the left and the text to the right, and on small screens they are displayed with the image above the text.

# Gallery:
    -   On large screens the gallery is displayed with four images in a row and on small screens, the images are displayed stacked on top of eachother. On all screen sizes, the videos are displayed one per row.

# Contact:
    -   The contact form is styled to width 70%, so it's size is responsive.

# Bugs:
-   The hero text was originally positioned on top of the hero image, however in mobile view, the text moved down the page when the hamburger menu was expanded. 
I couldn't work out how to fix this bug using positioning, so I moved the text down to below the hero image to remove this issue all together.

-   On medium and small screens, the tuition images were displayed too big and they were covering the text. To fix this I used the Bootstrap grid to change the column
configuration.

-   The final image on the tuition page was overlapping on the footer. To fix this I changed the z-index of the footer so it was displayed on top of the image.

-   On the Tuition page, the main body of the section element is wider than the other elements. I tried styling the divs within the section, the margin and padding, but I was not able to fix this bug.

## Deployment

Deployment process:
1.  In GitHub, go to Settings.
2.  Scroll down to GitHub Pages section on Settings page.
3.  Under "Source", click the dropdown menu and select "Master Branch".

## Credits

### Content
- The CSS styling for the size of the videos was copied from (https://css-tricks.com/fluid-width-video//).
- The YouTube videos were embedded using the code provided by YouTube on each video (https://www.youtube.com/).

### Media
- Some of the photos used in this site were taken by Angela Soutar Photography and such images have been marked appropriately with copyright. Permission was obtained for use of the images.
- The rest of the photos on the site were taken by myself or belong to Kimmy.
- The YouTube videos were recorded by Kimmy Kaminski and are published on her YouTube page https://www.youtube.com/channel/UCICSegaoPTz8yb-7TYggkCA.

### Acknowledgements
- I received inspiration for this project from The Code Institute mini projects Love Run and Whiskey Drop and from other music websites: Fresh Music Aberdeen (https://www.freshmusicaberdeen.co.uk/), Red Rock Scotland (https://www.redrockscotland.co.uk/) and Aberdeen Music Lessons (http://www.aberdeenmusiclessons.com/).
