# Thrive

Thrive is a website which aims to shed light on mental health as well as providing information and support resources. It is geared toward anyone with an interest in improving their mental wellbeing, including people who may be in emotional distress from common issues such as stress, anxiety or depression.

## UX/UI

The goals of this project are:

- Promoting awareness of mental health and mental health issues
- Redirecting the user to helpful pages and resources for seeking help
- Providing information and reassurance in a visually pleasing and calming layout

To this end, the website is presented with a cheerful but not overwhelming colour palette and feel-good imaging. Inspiring quotes, mental health tips and links to resources have also been provided in light of our goals.

The following is a wireframe of how the page is planned to look on a mobile when scrolled down to the bottom of the page:

![Wireframe](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/Wireframe.PNG)

The project may deviate from this wireframe due to potential design improvements during the process

## Features 

### Existing Features

1. Navigation bar
- The NavBar is fully responsive and contains the website logo and the navigation elements "Home", "About Us" and "FAQ"
- The navbar collapses into the burger icon for small devices and expands along the top of the page in larger devices thanks to a media query
- A line under the relevant section indicates to the user what part of the webpage they are on

![NavBar](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/navbar.PNG)

3. Hero image
- A cheerful and attention-grabbing image sits at the top of the Home page to give a positive first impression to the user and make the website look friendly and welcoming. 
- It contains a text overlay with the website's slogan to make it clear what the page is about

![Hero](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/hero%20image.PNG)

4. Introductory information section
- A list format is used to present begginer-friendly information about mental health
- FontAwesome icons are used to decorate the list and make it more easily digestible

![Intro](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/section%201.PNG)

5. Quotes section
- Some inspiring quotes from fictional characters who have overcome mental illness are introduced to inspire the reader with hope
- A fixed background image of sunflowers makes the section more eye-catching and cheerful
- The assymetrical layout (on tablets and larger devices) made with Bootstrap grid elements gives the quotes more space to stand out and provides a more fun and interesting layout to kee the readers attention
- Translucent background colours on the sections of text make it easier to read

![Quotes](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/section%202.PNG)

6. Mental health tips section
- Bootstrap cards provide general mental health tips in a fun and engaging way, breaking up sections of text
- CSS was used to style the cards to look unique, attractive and eye-catching

![Tips](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/section%203.PNG)

7. Further information section
- The Further Information section provides a simple list to avoid user fatigue, with easily viewable links to provide the reader with more resources for help and information

![FurtherInfo](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/section%204.PNG)

8. Footer
- The footer contains the social media links for the website
- It has been made responsive using Bootstrap grid elements and fixed to the bottom of the screen on the empty pages

![Footer](https://github.com/eva-may-JS/Individual-Project-Formative-Assessment/blob/main/assets/images/footer.PNG)

### Features Left to Implement

- Create new pages within the website which currently display as "Under Development"
- Create clickable images in the Further Information section with the recommended websites' logos to make this section stand out more

## Testing 

This project was tested using DevTools on the deployed product. All links and buttons have been checked and are clickable and functional and the layout has been inspected and found satisfactory on all screen sizes using the "Responsive" Dimentions option and dragging the viewport to all possible and reasonable shapes and sizes.

The code was also checked using HTML and CSS validation systems.

### Validator Testing 

- HTML
  - Three errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
    - Missing alt attribute on logo image (Fixed)
    - White space in an ID value field (Fixed)
    - Use of "hr" inside lists (Unfixed)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

Testing revealed incorrect use of "hr" element. A suitable alternative to create the desired effect is yet to be implemented.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://eva-may-js.github.io/Individual-Project-Formative-Assessment/index.html


## Credits 



### Content 

- The text for the Home page was taken from:
     - GOV.UK: Public mental health (https://www.gov.uk/government/collections/public-mental-health) 
     - ChatGPT (https://chatgpt.com/)
     - Samaritans (https://www.samaritans.org/)
     - Mind (https://www.mind.org.uk/)
- The text for the Deployment section of this README.md was taken from the CI README.md template (https://github.com/Code-Institute-Solutions/readme-template)
- The fonts were obtained from Google Fonts (https://fonts.google.com/)



### Media

- The images were taken from Pixabay (https://pixabay.com/) and Pexels (https://www.pexels.com/)
- The Favicon was created using Favicon.io (https://favicon.io/)
- The logo was created using LOGO.com (https://logo.com/)
- The icons were taken from [Font Awesome](https://fontawesome.com/)