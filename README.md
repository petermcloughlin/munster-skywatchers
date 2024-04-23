# Munster Skywatchers
The Munster Skywatchers website was designed with astronomy enthusiasts in mind as a way to link up with people,via meet-ups every few weeks for night sky watching events where they can meet up for coffee and view scheduled events in the night sky. Whilst using Munster as its base for sky watching events, it is open to all who are interested in signing up to join the group. The purpose of the meet-ups is to educate group members on the various objects and events that are happening within our solar system and beyond. There is also a social aspect to the gatherings with coffee meet-ups as a form of meet and greet which is very helpful for new members to the group, along with the outlining of the importance of safety as meet-ups generally take place in one of four locations at night throughout the Munster region.
The url for the deployed site is accessible [here](https://petermcloughlin.github.io/munster-skywatchers/).

![AmIResponsiveImage](docs/readme_images/Am_I_Responsive.PNG "Am I responsive image")

* Contents
    * Features
    * User Experience / User Interface
    * Testing
    * Deployment
    * Bugs / Fixes
    * Credits


## Features
The Munster Skywatchers website is comprised of three webpages:
* index.html
    * This is the homepage or landing page in which the detailed content of what we are about and what we offer to new members is outlined.   
* gallery.html
    * This page displays some images of celestial objects and events that have been previously witnessed.
* joinus.html
    * The joinus.html page contains a form which allows interested visitors, to sign up to our group and be notified of upcoming events which they can attend along with other members.

### Common features 
Both the navbar and footer are common features to the website giving a simple flow to the user experience as they navigate the website. The navbar utiltises a collapsed burger icon image on mobile devices , expanding to show the websites navigation pages on the top right of each page on larger devices such as tablets, laptops and desktops.

* Navbar
![NavbarImage](docs/readme_images/Navbar.PNG "Navbar Image")

The footer contains four social media links to Facebook, Instagram, Twitter and YouTube, all of which open in a new tab when clicked by the user. On devices such as tablets, laptops and Desktops, the gold hover effect keeps the user interface colouring in line with the themed color scheme used across the site, making the user experience more intuitive.

* Footer
![FooterImage](docs/readme_images/Footer.PNG "Footer Image")

### Home Page (Landing page)
The index.html or landing page uses a high resolution hero image of the moon to engage the visitor and demonstrate the kind of detail members would experience when viewing celestial objects such as the moon through our telescopes. This page also details more information about what we do, reason to join us and some information on upcoming events in the summer to autumn of 2024.

![LandingPageImage](docs/readme_images/Homepage1.PNG "HomePage Image")

![LandingPageInformationImage](docs/readme_images/Homepage2.PNG "HomePage Information Image")

### Gallery Page
The gallery.html contains a list of images relating to space, the solar system, celestial events and sky watchers with a final image of coffee mugs on a table reminding the user that there is a social aspect to the the sky watch meet ups.
The images are separated by a small white space on mobiles to define the individuality of each image. I opted to keep the enlargened images with a vertical page scroll on larger screen sizes such as laptops and desktops with a ccs overlay descriptive text block which appears and disappears as the user hovers their mouse over each image. I felt that the enlargened images would ensure the high resolution would be more pleasing to the user , visually.

![GalleryPageImage](docs/readme_images/Gallery.PNG "Gallery Page Image")

### Join Us Page
The last page is the joinus.html, where the user gets the opportunity to join the Skywatcher group by completing the form,filling in their Firstname, Lastname, Email, Contact number and selecting Private or Public to notify that they use their own vehicle or public transport when travelling to the Skywatch meet-ups. There is a gold hover effect on each text-input box when the user hovers their mouse over each text-input box to enhance the user experience when interacting with the UI on laptops and desktops. The transparent Join Us button turns green when the users mouse enters the button element on large screens for a more improved, intuitive user experience.
Each text-input box , including the radio button options have 'required' attribute that displays an alert prompt to the user if they attempt submit the form without completing these fields. 

![JoinUsPage](docs/readme_images/JoinUs.PNG "JoinUs Page Image")

## User Experience / User Interface

When designing the website at the planning stage, I tried to keep the target audience in mind when designing the UI display. The target audience in this case would predominently be astronomy enthusiasts, experts and novices, who would like to enjoy the educational and social experience that comes with signing up to be a member of the Skywatcher group. The name 'Munster Skywatchers' is to place emphasis on the locations of our viewing points across the Munster region of Ireland.

The colour selection of #040404 for the backgrounds, #ffffff for text and some icons , along with #gold and #goldrun for icons and text-input hover effect worked well with the high resolution image of the moon on the landing page and the background image on the joinus.html page.

I checked the color contrasts using [webaim.org](https://webaim.org/resources/contrastchecker/) to ensure it would provide enough contrast for visually impaired visitors to the site.

### User Story
As a visitor, the user of the website;
* will want to discover more information about what the Munster Skywatchers do
* will see some images that visually relate the text content to their understanding of what is involved in Skywatch meet-ups.
* will be able to avail of the option to join the group by competing the form on the last page to become a member and available of notifications of upcoming Skywatch meetings.
* will be able to potentially view the groups social media links to gain a greater sense of what is involved, with access to the icons in the footer of the website. (For the purposes of this website, the footer social media links only take to the user to the standard social media sign in pages)

### Wireframes
At the initial stage of planning, I created some mobile-first approach wireframes to demonstrate a visual display of the user interface.
Below are a snapshot of the wireframes, one for each page of the website. The final project deviated slightly from the exact design laid out.

* [Index.html](docs/readme_images/Index_wireframe.PNG)
* [Gallery.html](docs/readme_images/Gallery_wireframe.PNG)
* [JoinUs.html](docs/readme_images/JoinUs_wireframe.PNG)

## Testing
The testing of the Munster Skywatchers website was ongoing throughout the development stages, including the use of element inspection for addition of new elements to the pages before committing to GitHub. Testing of the website included the following approaches;

* Manual Testing
* HTML Validation
* CSS Validation
* Lighthouse Inspection
* Responsiveness

### Manual Testing
As a manual test of the website, I accessed the deployed url on a variety of devices such as iPhone, Android mobile, Tablet, iPad, laptop and Desktop to view the sites visual responsiveness, access to the footer links, completion of the joinus.html form and toggling of the burger icon and navbar links.
The form validation alerts appeared to work fine on larger devices such as laptops and desktops, with the hover effect on the text-input boxes turning a border color of gold and the submit button turning dark-green on hover.

* Footer links - opened social media links in new tab as expected
* Navbar burger icon - toggled as expected
* Navbar items - hover underline effect appeared on hover as expected
* Navbar items - navigated to new pages on click event, as expected
* The Gallery's image text overlays appeared to work fine on larger devices such laptops and desktops when the mouse hovered on the images.
* Form text-input fields - validation alerts appeared as expected with the required attribute working on each one.
* Form radio-button transport options - selected item submitted successfuly along with text-input fields, on submission.
* Form submission was successful.

### HTML Validation
I used [validator.w3.org](https://validator.w3.org/) to validate the html of each page and [jigsaw](https://jigsaw.w3.org/css-validator/) to validate the css stlyes in the website.

* HTML Testing Results

    * [HomePage](docs/readme_images/Index.html.validation.PNG)
    * [GalleryPage](docs/readme_images/Gallery.html.validation.PNG)
    * [JoinUsPage](docs/readme_images/Joinus.html.validation.PNG)

I encountered a warning on the HTML validation for the Gallery page due to a missing h2 element within the section with id=gallery.

The Landing page and Join Us page validated successfully without any errors or warnings.

### CSS Validation
The css stylesheet validated successfuly without any warnings or errors. Please the CSS validation results [here](docs/readme_images/CssValidation.PNG).

### Lighthouse Inspection
The Lighthouse inspection results returned good results for Accessibilty , Best Practices and SEO, however they dropped a little on the Performance test. After discussion with my Mentor, this was probably due to the images loading times on the pages, especially on mobile devices.

The Lighthouse Inspection reports can be accessed below;
* Mobile Inspection
    * [HomePage](docs/readme_images/Index.html.Mobile.PNG)
    * [GalleryPage](docs/readme_images/Gallery.html.Mobile.PNG)
    * [JoinUsPage](docs/readme_images/JoinUs.html.Mobile.PNG)

* Desktop Inspection
    * [HomePage](docs/readme_images/Index.html.Desktop.PNG)
    * [GalleryPage](docs/readme_images/Gallery.html.Desktop.PNG)
    * [JoinUsPage](docs/readme_images/JoinUs.html.Desktop.PNG)

### Responsiveness
The website appeared to be responsive on mobile, tablet, laptop and desktops with sizes adjusting to fit the screen widths for each device type. I used the [Am-I-Responsive](https://ui.dev/amiresponsive) website to test the responsiveness of the website on various devices as a further test.

## Deployment
I used GitHub pages for deployment of the web project at an early stage of the design process. This made it easier to do quick visual tests on each commit that was made from my GitPod workspace. I followed the steps below when deploying the website project to GitHub;

* I navigated to the Settings option in GitHub
* I selected the main branch and root folder under the Build and Deployment section
* Once saved, the deployment process ran and the saved link appeared.

Here is a link to the live website , [munster-skywatchers](https://petermcloughlin.github.io/munster-skywatchers/)

## Bugs / Fixes
During the development process, I fixed any bugs or issues as I encountered them, using incremental steps of code addition whilst constantly checking the live output in GitPod, prior to committing to GitHub.

Overall, I did not encounter any major bugs. However, one existing bug within the project is the text overlay on hover on the image of Saturn. The effect apears to work over every other image within the Gallery page, except for the image of Saturn.

## Credits
The following are credits for the sources of code, imagery and font sourced for the project build;

*   All images for the project within the index.html, gallery.html and joinus.html were sourced from [pexels.com](https://www.pexels.com/)
*   The CSS text overlay code for the images on the gallery.html page were sourced from [w3schools.com](https://www.w3schools.com/howto/howto_css_image_overlay_title.asp)
*   The icons for the index.html and joinus.html pages were sourced from [Font Awesome](https://fontawesome.com/)
*   I used the navbar and footer from the Love-Running project. I liked its design and how it would collapse the navbar into a burger icon using pure css, for mobile. 

## Summary
In summary, I would like to thank my mentor Alan for some useful hints and tips for the future and for some useful links and tools to improve the design process regarding UI/UX. I felt perhaps a repsonsive css carousel or some design element of that nature may have been a better option for the gallery page, especially on larger devices , to avoid a lot of vertical scrolling. I just felt at this early stage of the journey with CSS, it might have been a slight jump too far for now but definitely something I hope to become a lot more comfortable with, in time and practice. 







