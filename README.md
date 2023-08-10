## Purpose of the project
The purpose of the Taxma website project is to provide a comprehensive online platform specializing in financial services, with a primary focus on offering efficient and accurate payroll and bookkeeping services. This project aims to streamline and simplify financial management for individuals and businesses of all sizes.


![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/header.jpg)

View the live project [here](https://ghassanishag.github.io/taxma/)

## Site Owner's Goals
- Simplifying Financial Management: The site owner's primary goal is to simplify the process of managing finances for their clients. They aim to make bookkeeping, payroll, and other financial tasks easy and accessible even for individuals without a finance background.

- Enabling Focus on Business: The site owner wants to allow their clients to focus on their core business activities. By handling tasks like bookkeeping, payroll, and tax-related matters, they aim to free up their clients' time and energy so they can concentrate on running their businesses effectively.

- Peace of Mind: The site owner aims to provide clients with peace of mind by ensuring that their financial matters are in order. Clients can feel confident knowing that their financial affairs are being managed by a capable and reliable partner.

## External User's Goals
- Easily find out about Taxma and What does they do.

- Effortlessly access the range of services offered by Taxma.

- Be able to Contact Taxma for further questions or any enquiries.

## UX Design
## Wireframes
- Desktop Wireframe using Penpot:
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/desktop.svg)

- Tablet Wireframe using Penpot:
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/tablet.svg)

- Tablet Wireframe using penpot:
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/mobile.svg)

## Features
- ### Header
The header at the top of each page contains Taxma logo for their website and a navigation bar links to their Home page, Services page, About page and their Contact page. The navigation bar can extend or collapse, depending on the screen size.

- ### Footer
The footer at the bottom of all the pages contains a navigation bar links to their Home page, Services page, About page and their Contact page. Also, It contains all rights reserved phrase.

- ### Home Page
It has a big image presenting collaboration. Additionally, there is a button that takes the user directly to  Taxma services page.


![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/home.png)

- ### Services Page
This page has a brief description about all services that provided by Taxma , each of the services is included in a box with a semi-transparent grey overlay dev element  that changes to semi white  colour upon hover over the element and text changes to black.


![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/services.png)

- ### About Page
This page has a brief introduction about Taxma 


![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/aboutus.png)

- ### Contact Page
This page include the contact details and address map for the location of Taxma.
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/contactus.png)

## Future Features
- User should receive an email after sending a message.

## Typography and color scheme
### Colour Scheme
The primary color scheme employs either white (as the background) and black (for text). In addition, the website incorporates blue consistently across various elements. This vibrant hue appears in spans, background hover links, buttons.

### Typography
The website is formatted with the Roboto font. As a contingency, Sans Sherif was employed as the substitue font to be employed if designated fonts fail to import correctly on the website for any reason.

## Technology
- ### Languages Used
-	HTML5
-	CSS3
- ## Frameworks, Libraries & Programs Used:
-	Bootstrap 5.2.3: Bootstrap was used to assist with the responsiveness and styling of the website.
-	Google Fonts: Google fonts were linked into the html files throughout the project.
-	Font Awesome 6.2.1: Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
-	GitHub: GitHub is used to store the projects code after being pushed from Git.
- Canvas canvas was used to create the logo.
-	Penpot:  was used to create the wireframes during the design process.

## User Story
1.	If I would like to contact Taxma for business enquiries, then I should look for the contact page which is easily to be navigated whether from the header in each page, from the footer or from the available contact us buttons in the services page and once clicking, the I can send my message directly to the available WhatsApp number connected to each button.
2.	If I would like to understand the services provided by Taxma services website, The services page has a detailed information about their services with details.
3.	If I would like to gain more information of Taxma services, The About page provides a clear information about Taxma services.

## Structure

The main files and directories are as follows:

- `index.html`: The main HTML file that serves as the entry point of the website.
- `about.html`: The HTML file containing the "About Us" page content.
- `contact.html`: The HTML file containing the "Contact" page content.
- `services.html`: The HTML file containing the "Services" page content.
- `assets/`: Directory containing two subdirectories (css and img).
- `docs/`: Directory containing images.
  
## Files

### index.html

This is the main HTML file that serves as the entry point of the website. It includes the header, navigation bar, and the main content section. The navigation bar allows users to navigate to different pages such as Home, Services, About, and Contact.

### about.html

The HTML file containing the "About Us" page content. It includes a brief introduction about the company and its mission. The page also features an image and a description of the services provided.

### contact.html

The HTML file containing the "Contact" page content. It includes a contact form and the company's contact information.

### services.html

The HTML file containing the "Services" page content. It showcases the different services provided by the company through styled service boxes.

### style.css

The CSS file that defines the styles and layout for the entire website. It includes styles for the header, navigation bar, sections, images, and other elements.


## CSS Classes

The project utilizes ***bootstrap*** library and other CSS classes to style and layout the different elements of the website. Here are some of the main CSS classes used and their purposes:

- `.logo`: Styles the logo image in the header.
- `.home-call-to-action`: Styles the call-to-action section on the home page.
- `.service-box`: Styles the service boxes on the services page.
- `.navbar`: Styles the navigation bar at the top of the website.
- `.social-links`: Styles the social media links in the header and footer.

The CSS classes are defined in the `style.css` file and are applied to the respective HTML elements and pages to achieve the desired styling and layout.

***Flexbox*** along with media queries are utilized to create responsive and visually appealing layouts. Here's a simple breakdown of its usage:

- `.home-call-to-action`:
  
  - This class is applied to the container of the call-to-action section on the home page.
  - Flexbox properties are used to center the content both horizontally and vertically within the container.
  - Media queries are used to modify the background image and add a semi-transparent overlay on smaller screens for better readability.

- `.service-box`:
  
  - This class is applied to the service boxes on the services page.
  - Flexbox properties are used to vertically center the content within each box and create a visually pleasing layout.
  - The boxes have a background image set, which is scaled and positioned using background properties.

  
## Testing
  
  ### Code Validation
   The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
    - HTML
   1. The index file was validated by HTML Validator and no errors or warnings were found.
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/index.png)
W3C Markup Validator 
    
- CSS
   2. The style sheet was validated by using CSS validater
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/cssval.png)
W3C CSS Validator

## Using Lighthouse
When ckecking through lighthouse for desktop and mobile devices I got these results:

![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/desktop.png)
![demo](https://raw.githubusercontent.com/GhassanIshag/taxma/main/docs/mobile.png)



## Deployment
- Via github pages:
To deploy the page via github pges follow these steps:

1. On GitHub, navigate to the repository https://github.com/GhassanIshag/taxma/
2. Click Settings.
3. In the "Code and automation" section of the sidebar, click Pages.
4. Under "Build and deployment":
5. under "Source", select Deploy from a branch.
6. Under "Branch", Main Branch
7. Click "Save".
8. Refresh the page and shortly the live link of the website will appeare.
9. The live link https://github.com/GhassanIshag/taxma/

## Credits

Images came from [unsplash.com](https://www.unsplash.com/)

Bootstrap4: Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

click to chat : contact us now, was used to connect contact us now buttun to the whatsapp number. [found here](https://faq.whatsapp.com/5913398998672934)

## Content
All content was written by the developer.

## Acknowledgements
1.	Tutors and community members at Code Institute.
2.	My Mentor Guidance at Code Institute Okwudiri Okoro


