# Wave Eye Clinic
Wave Eye clinic is an ophthalmic surgery centre which offers laser refractive and lens surgery. The website aims to gives prospective patients the essential information about the practice and surgeons, surgical procedures and finance options. Patients are also able to submit contact details to arrange an consultation. View the live site [here](https://nataliatesarova.github.io/project-one/index.html)

![multiple screens](assets/doc/monitor.png)

## Features 
### Navigation bar
![navigation bar](assets/doc/navigationbarandlogo.png)
* Navigation Menu
    * Contains links to the About us, Services and Contact on all pages, with hover feature, and will be responsive on devices of differing size.
    * Opens in the same tab and allows users to easily navigate between the pages within the site.
 
![brown eyes image](assets/doc/brown-eyes.jpeg)

### The landing page image
* The landing page has a pleasant image of a woman's eyes which immediately tells the viewer that the site is ophthalmic. The image of eyes literally makes eye contact with the user.

### Introduction to the clinic and main surgeon
* Information on the educational and training background of the principle surgeon and clinic owner, and the high level of care and treatment that patients can expect.
![laser eye surgery](assets/doc/lasereyesurgery.png)

### Surgical videos
*  Embedded Youtube videos of LASIK and cataract surgery, which are the two main treatmens offered by the clinic. 
![videos of surgery](assets/doc/videos.png)

### Emphasis of clinic attributes
* The high quality of the surgeons and surgical equipment, and finance options are briefly summarised in three headed columns. 
![three paragraph of text](assets/doc/threeparagraph.png)

### Footer
* The footer contains the icons and links to the clinic's social media sites on Facebook, Instagram, YouTube and Twitter that will open in new tabs. 
* This will alow the user to see the most up-to-date information, which may not yet be available on the clinic website.
![footer](assets/doc/footer.png)
  
### Services
* The services section gives the user information on the main surgical procedures offered by the clinic including laser eye surgery (LASIK, LASEK and SMILE), cataract surgery, refractive lens exchange and implantable collmaer lenses.
![services](assets/doc/services.png)
* Three images are included in a gallery at the bottom of the page showing an operating eye surgeon, doctor checking the eye with a torch and doctor examining a patient at the slit-lamp microscope.
![three images](assets/doc/threepics.png)

### Contact
* The contact page allows users to request an appointment for a consultation at the clinic. The user is presented with 5 boxes to input first name, last name, email address, telephone number and comments/questions. 
* On pushing the send button a new page is opened stating 'Thank you for contacting us. We will reply shortly'. (INSERT PIC OF THANK YOU PAGE)
* The clinic address and telephone number are also presented on the contact page allowing another mode of contact.
![request an appointment](assets/doc/contactpage.png)

### Features left to implement
* A possible future enhancement would be to add javascript to send an email directly to the Wave Eye Clinic.

### Accesibility
* Use of semantic HTML
* Use of ARIA labels allowing ientification by by screen readers
* Use of alt attributes to provide alternative information for users
* Use Adobe Color to check colour contrast
* Color contrasts meet the standards specified in [WCAG 2.1 contrast guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)

##  Design
### Color scheme
The background color on the header and footer was pink RGB (255,182, 193). Font color in header, footer, and headings was brown RGB (130, 65, 18).

### Typography
* Raleway font from Google fonts
* Times font

### Logo
Logo was designed on [Free Logo Design](https://www.freelogodesign.org/) and incorporated into the header
![logo](assets/doc/logo.png)

### Images
The source of all images are provided in the credit section

### Balsamiq frameworks

Home page
![wireframe desktop computer](assets/doc/squareaboutus.png)

![wireframe mobile phone](assets/doc/aboutusm.png)

Services page
![wireframe desktop computer](assets/doc/squareservice.png)

![wireframe mobile phone](assets/doc/maboutus.png)

Contact Page
![wireframe desktop computer](assets/doc/requestsquare.png)

![wireframe mobile phone](assets/doc/requestm.png)

Submission and thank you page
![wireframe desktop computer](assets/doc/squarethankyou.png)

![wireframe mobile phone](assets/doc/thankyoum.png)

## Testing

### Responsiveness
* All pages were tested for resposiveness on 320px and up using the developer tools. The web site was tested on Google Chrome, Safari, Mozilla Firefox, Microsoft Edge and Opera browsers with iPhone SE, iPhone 14 Pro, iPhone 14 Pro Max, Samsung Galaxy S8+, Ipad Air devices.
* The web site opened as expected with no responsive issues in all cases apart from the navigation bar appearing too crowded on the smaller device screens. This issue was fixed by decreasing the navigation bar text font size.

### Validator
* HTML: Errors were not found when passing through the official W3C validator
![html validator](assets/doc/index.png)
![html validator](assets/doc/service.png)
![html validator](assets/doc/contact.png)
![html validator](assets/doc/thankyou.png)
* CSS: Errors were not found when passing through the official Jigsaw validator
![Jigsaw validator](assets/doc/validator.png)

### Accessibility
* Adobe Color was used to test contrast for accessibility. ![adobe colour contrast test](assets/doc/Adobecolor.png)
* Lighthouse in the Chrome Developer Tools was used to test website performance, accessibility, best practices and SEO. 
![](assets/doc/lighthouseabout.png)
![](assets/doc/lighthouseservices.png)
![](assets/doc/lighthouserequest.png)
![](assets/doc/Screenshot%202023-01-22%20at%2019.24.28.png)
* Manual testing was also performed

### Bugs
An error was found with the footer since the h3 ("Follow Wave Eye Clinic") was placed in the ul. This was fixed by moving the h3 above the ul. 

## Technologies used
### Languages
* HyperText Markup language (HTML) - the standard markup language for documents designed to be displayed in a web browser
* Cascading Style Sheets (CSS) - used to describe the presentation of the document written in HTML

### Frameworks, Libraries and Programs
* [Balsamiq](https://balsamiq.com/wireframes/)- used to create the wireframes
* [Github](https://github.com/) - cloud based hosting service to save and store the files for webite 
* Git - version control system
* [Visual Studio Code](https://code.visualstudio.com/) - the website was created using Microsoft Visual Studio Code integrated development environment (IDE)
* [Font Awesome](https://fontawesome.com/) - font and icon toolkit
* [Google Fonts](https://fonts.google.com/about) - used to importing the fonts on the website
* [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) - used for troubleshooting and testing features, and to solve issues with responsiveness and styling
* [Multi Device Website Mockup Generator](https://techsini.com/multi-mockup/) - used to show website on range of devices

## Deployment

### Version control
The site was created using Visual Studio Code editor (Microsoft) and pushed to github to the remote repository ‘ADD NAME’.

The following git commands were used to push code to the remote repository:

```git add <file>``` - This command added the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command allowed the commit of changes to the local repository queue.

```git push``` - This command pushed all committed code to the remote repository on github.

### Deployment to Github Pages

* The site was deployed to GitHub pages. Deployment requires the following steps: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully. The live link is available [here](https://github.com/nataliatesarova/project-one)


## Credits

I would like to thank my mentor Gareth McGirr especially for advice regarding flexbox and the readme template. Chris Quinn gave valuable general information in the teaching sessions and especially helped with advice on the action attribute in the form tag of my HTML

### Content
Logo was designed on [Free Logo Design](https://www.freelogodesign.org/)

Instructions on how to use FlexBox to split text in three columns on the About us page was provided by [The Wheelchair Guy](https://www.youtube.com/watch?v=Q1d-1FzdXEE), and [Cem Eygi Media](https://www.youtube.com/watch?v=qXRYMdvq_Dc).

The website icons were provided by [Font Awesome](https://fontawesome.com/)

### Media
All images and youtube videos are used here for educational purposes and there were no known copyright issues.

The brown eyes image on the index page was provided by the educational website [All About Vision](https://www.allaboutvision.com/conditions/eye-color-brown.htm) 

The LASIK animation was provided by [Vold Vision](https://www.youtube.com/watch?v=j9SANdddTlo&t=1s)

The cataract surgery animation was provided by [Fauquier ENT](https://www.youtube.com/watch?v=gRj6J0AGpPs)


Image of surgeon operating was provided by [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:U.S._Air_Force_Maj._Matthew_Caldwell,_foreground_right,_a_cornea_and_refractive_surgeon_with_the_59th_Medical_Wing,_performs_cataract_surgery_June_5,_2013,_during_New_Horizons_2013_at_the_Southern_Regional_130605-F-FO324-008.jpg_eye_surugery)

Young Caucasian girl getting an eye examination picture taken from [Rawpixel](https://www.rawpixel.com/image/259737/girl-getting-eye-exam)


The image of the patient at the slit-lamp microscope was taken from the website of [Ekol International Hospitals](https://www.ekolhospitals.com/assets/upload/930185_8950-8251.jpg)












