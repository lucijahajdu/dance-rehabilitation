# Dance & Rehabilitation #
The Dance & Rehabilitation is a website for an individual who specialises in professional dance choreography, physiotherapy and dance rehabilitation.
Users of the website will be able to recieve information about the websites owners background and offers, categoriesed into different topics (e.g.: choreography, rehabilitation, kinesio taping).

![Mockup of the website](/assets/css/images/mockup-readme.png)

## Features ##
* Navigation
   * Featured at the top of the page, the navigation bar shows the websites name in the left corner: Dance & Rehabilitation and the Home, About, Services and Contact on the right side.
   * This sections clearly tells the user the name of the website and makes the different sections of information accessible.

![Navigation bar](/assets/css/images/navigation-readme.png)

* The landing page image 
  * The main image appears across the full width of the page. 
  * The text overlay informs users of location this site is applicable to.

![Main image](/assets/css/images/main-image-readme.png)

* About me Section 
  * The About Me Section shows the image and offers users information about the proffesional background of the service provider.

 ![The about me Section](/assets/css/images/about-me-section-readme.png)

* How can I help you section
  * This section is divided into three topics (Choreography, Rehabilitation trainer, Kinesio tapping) and gives information about the services the site owner offers.

  ![Services section](/assets/css/images/howcanihelpyou-readme.png)

* Contact section
  * The contact section allows the user to find out information on how to get in contact with choreographer. 
   * User can also directly send the message and get in touch with the service provider.
   * The user will be asked to submit their full name, email address and additional text with the customers request.
   ![Contact Section](/assets/css/images/contact-section-readme.png)
* The Footer 
  * The footer section includes links to Facebook, Twitter, YouTube and Instagram. The links will navigate to a new tab to allow easy acces for the user.
  * The user can be connected to the Dance & Rehabilitation website owner via social media.
  ![Footer Section](/assets/css/images/footer-readme.png)

## Wireframes ##
* Before starting the project I made the wireframe to have an overview of the information arhitecture and the apperance of the page.

  ![Wireframe of the website](/assets/css/images/prototype.png)

## Typography and color scheme ##
* Fonts used in this project are : Raleway and Roboto. Fonts were used from [Google Fonts](https://fonts.google.com/ "Google Fonts").
* Colors used for background is lavender (hex:#E6E6FA).
* Text color is dark shade of gray (hex:#3a3a3a).

## Technology ##
* HTML and CSS were used to create this website.
* GitPod was used for writing the codes.
* Github-to save and store the files for the website.

## Testing ##
* The website functions in different browsers: Chrome, Firefox, Microsoft Edge.
* This project is responsive. Functions well on standard screen sizes using the devtools device toolbar.
* Navigation, header, about us, services and contact section text are all readable and easy to understand.
* The form functions correctly: requires entries in every field, it will only accept an email in the email field, and the submit button works.
  * The form curently works as a dummy form. Designed to give feedback to the user but it does not store any data.
### Test cases ###
* The webpage responds web scrolling scrolling
* When tapping the options Home, About, Services or Contact, it navigates the user to the section of the page where the aproporiate information can be found.
* In the form section
      * When hovering over the input fields, the frames turns green, indicating that it can be filled in
      * If there are missing informaion in the data section of the form, when tapping "Send your messge", a warning message appears to inform users to fill in the missing information.
      * Tapping "Send your message" CTA opens the confirmation site
* In the footer section, the Facebook, Twitter, YouTube and Instagram CTAs navigate the user to the corresponding website.
* Tapping on the "Dance and Rehabilitation" title will direct the user to the main page

### Bugs ###
#### Solved Bugs ####
* When I open my project on the other device the images were not visible. 
* This was because I had absolute file paths such as this in my code : `<img src="/assets/css/images/about-me.jpg">`  
* Removing the "/" in the beginning of the code fixed the bug.
* Form Section
  * When I taped "Send Your Message" CTA it did not direct to the confirmation site. 
  * The bug was solved: instead of quatiation mark, apostrophe was used in the code. When corrected, the bug was resolved.

## Validator Testing ##
* HTML
  * No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/ "W3C Validator").
* CSS
  * No errors were found when passing through the official [Jigsaw W3 Validator](https://jigsaw.w3.org/css-validator/ "Jigsaw W3 Validator").
* Accessibility 
 * Chosen colors and fonts are easy to read and accessible by running it through lighthouse in devtools.

 ![Accessibility in Lighthouse](/assets/css/images/accessibility-readme.png)

## Deployment ##

* The site was deployed to GitHub pages. The steps to deploy are as follows:
  * In the GitHub repository push the green Gitpod button
  * In the Gitpod terminal type python3 -m http.server to run frontend application
  * To save our code type git add ., git commit -m "" and git push to push our code to the GitHub
  * In the GitHub repository, navigate to the Settings tab
  * On the right side of the page push Pages
  * From the source section drop-down menu, select the Master Branch
  * Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

  The live link can be found here: https://lucijahajdu.github.io/dance-rehabilitation/

## Credits ##
### Content ##
* The code to make the social links was taken from CI Love Running Project.
* The idea for header and positioning main image was taken from Love Running Project.
* The text for About me section was based on the CV of the website owner.
* The icons in the footer were taken from Font Awesome.
* Instructions on how to  create certain codes were found on Code Institute LMS
## Media ##
* The images were provided from Anita Hajdu(site owner).
* The background image in the Services section was taken from [Pexels](https://www.pexels.com/ "Pexels").
## Resources ##
* [Google Fonts](https://fonts.google.com/ "Google Fonts")-to import the fonts used on the website.
* [Font Awesome](https://fontawesome.com/ "Font Awesome")-for the iconography on the website.
* [Tinypng](https://tinypng.com/ "Tinypng")-to compress images. https://balsamiq.com/
* [Balsamiq](https://balsamiq.com/ "Balsamiq")- to make a wireframe.