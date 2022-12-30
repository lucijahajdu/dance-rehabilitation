# Dance & Rehabilitation #
The Dance & Rehabilitation is a website for an individual who specialises in professional dance choreography, physiotherapy and dance rehabilitation.
Users of the website will be able to recieve information about the websites owners background and offers categoriesed into different topics (e.g.: choreography, rehabilitation, kinesio taping).

![Mockup of the website](/assets/css/images/mockup-readme.png)

## Features ##
* Navigation
   * Featured at the top of the page, the navigation shows the websites name in the left corner: Dance & Rehabilitation and the Home, About, Services and Contact on the right side.
   * This sections clearly tells the user the name of the website and makes the different sections of information accessible.

![Navigation bar](/assets/css/images/navigation-readme.png)

* The landing page image 
  * The main image appears on the full width of the page with the text overlay to informe users of location this site is applicable to.
![Main image](/assets/css/images/main-image-readme.png)

* About me Section 
  * The About Me Section shows the image and offers users information about the proffesional background of the service provider.
 ![The about me Section](/assets/css/images/about-me-section-readme.png)

* How can I help you section
  * This section is divided into three boxes (Choreography, Rehabilitation trainer, Kinesio tapping) and gives important information about the services the site owner offers.
  ![Services section](/assets/css/images/howcanihelpyou-readme.png)
* Contact section
  * The contact section allows the user to finde out important informations how to get in contact with choreographer. 
   * User can also directly send the message and get in touch with the service provider.
   * The user will be asked to submit their full name, email adress and additional text.
   ![Contact Section](/assets/css/images/contact-section-readme.png)
* The Footer 
  * The footer section includes links to the facebook, twitter, youtube and instagram. The links will open to a new tab to allow easy navigation for the user.
  * The user can be connected to the Dance & Rehabilitation website owner via social media.
  ![Footer Section](/assets/css/images/footer-readme.png)

## Wireframes ##
* Before starting the project I made the wireframe to have an overview of the information arhitecture and the look of the page.

  ![Wireframe of the website](/assets/css/images/prototype.png)

## Typography and color scheme ##
* Fonts used in this project are : Raleway and Roboto. Fonts were taken from Google Fonts.
* Colors used for background is lavender (#E6E6FA).
* Text color is dark shade of gray (#3a3a3a).

## Technology ##
* HTML and CSS were used to create this website.
* Git-for version control.
* Github-to save and store the files for the website.
* [Google Fonts](https://fonts.google.com/ "Google Fonts")-to import the fonts used on the website.
* [Font Awesome](https://fontawesome.com/ "Font Awesome")-for the iconography on the website.
* [Tinypng](https://tinypng.com/ "Tinypng")-to compress images. https://balsamiq.com/
* [Balsamiq](https://balsamiq.com/ "Balsamiq")- to make a wireframe.

## Testing ##
* The website functions in different browsers: Chrome, Firefox, Microsoft Edge.
* This project is responsive. Functions well on standard screen sizes using the devtools device toolbar.
* Navigation, header, about us, services and contact section text are all readable and easy to understand.
* The form functions correctly: requires entries in evry field, will only accept an email in the email field, and the submit button works.
  * The form curently works as a dummy form. Designed to give feedback to the user but not storing any data.
  
### Bugs ###
#### Solved Bugs ####
* When I open my project on the other device the images were not visiable. 
* This was because I had absolute file paths such as this in my code : `<img src="/assets/css/images/about-me.jpg">`  
* Removing the starting / fixed the problem.


#### Unresolved Bugs ####
* Form Section
  * When pushing Send Your Message button error 404 occures.
  * `<form action=“confirmation.html” method="GET" class=“form-section”>`

## Validator Testing ##
* HTML
  * No errors were returned when passing through the official W3C validator
* CSS
  * No errors were found when passing through the official (Jigsaw) validator
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


  

