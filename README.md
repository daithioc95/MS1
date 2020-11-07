# User Centric Frontend Development Milestone Project 

This project is a portfolio website to showcase my skills and experience to recruiters and potential clients.
The website will also be interactive and include designs which can be appreciated by the user.
The website will both a vehicle for my brand and a means of contact for interested parties.

## UX

The website will contain a simple design to ensure the primary function of providing information to the audience on devices of all sizes.
To complement this, an interactive, easy on the eye design will be implemented.
This will be executed by designing a single paged long scroll website, with options to navigate to any particular sections using the Menu bar.
Implementing this design will keep the audience engaged and compliment the users stories by firstly feeding the user with “what” it is that do, secondly, showing projects to convey “How” I do it and finally, providing a means of contact should they want to collaborate.

### User Stories
- As a recruiter/potential client, I want to see the web developers experience, so that I can see if this is relevant to the job/project requirements.
- As a recruiter/potential client, I want to see the web developers’ skills, so that I can see if these skills match the job/project.
- As a recruiter/potential client, I want to see the developer’s portfolio, so that I can see if his previous projects require capabilities relevant to this job/project.
- As a recruiter/potential client, I want to easily find this information while appreciating the websites design, so that I can see that the developer is competent in front-end development.
- As a recruiter/potential client, if interested I want to contact to the developer, so that I can see if he is available for work.

### Design Process 
- I began the design process by firstly identifying the sections neccessary to meet the criteria of my use stories. This included the Home, About, Experience, Portfolio & Contact sections.
- The next stage of the process was to brainstorm features. 
  - In addition to the usual sections a portfolio website contains, I wanted to use an interactive map as a statement piece to showcase CSS skills and provide information on my international experience.
  - I decided on this feature for large screens only as using a small screen would be difficult to select specific points on the map.
  - When searching for potential maps on pxhere.com, I can accross a treasure island like map which suited the feature aestetically.
  - Using the lightest and darkest colors from the map, I input this to https://mycolor.space/ to generate a 3 color gradient and thats when I choose a teal-like #5FFBF1 as my primary site color.
  -Other features I decided on were a progress bar for skills, I took inspiration for thing for the mini-project as it is a great was to visually portray my skills.
- When all my sections and additional features were decided upon, I moved onto creating wireframes for both the mobile and browser.
I began this by using pen and paper with the bootstrap grid system in mind and once a general, responsive idea formed, I created the below using balsamiq.

- See Desktop Wireframe [here](assets/MS1_Desktop.pdf)

- See Mobile Wireframe [here](assets/MS1_Mobile.pdf)

## Features
Breakdown of the website features by section

### Navbar
I created the Navbar using Bootstrap and editing the color to suit my websites design.

### Home
Simple image which I found on pxhere.com.
I choose this as the yellow glow from the wood matches the teal and the map feature image to appear later.
Additionally, the laptop, phone, books etc. represent convey a design/service use case for the website. 

### About
The About section contains a heading with a circle container and a circle headshop image.
The end of the about section contains a progress bar section.
Other features include font awesome icons.

### Experience
For desktop, this seciton includes an interactive map which shows experience depending on location.
When the location is selected, experience relvant to this location apeears in an expanded box.
I have included icons with links to media and files to back up my experience.

For mobile, I included the same content, however to make up for lack of visuals compared to the desktop version, I included the organisations logos. 

### Porfolio
For the portfolio seciton, I included a simple bootstrap grid design to show each project in a size-responsive manner.

### Contact
The contact seciton is designed using a bootstrap form.
An icon is used to transition into this section with relevant information prompted to contact the web developer. 

### Footer
I included a simple footer design, I used font awesome icons to represent each link. 

### Future Features
Please see below list of features which I intend to implement at a later stage.
- Media carosel: When an icon is selected in the desktop media section, I plan to implement a media carosel/slideshow for videos/images corresponding the the entry. Currently I have a link to youtube for each entry.
- Background: I plan to implement subtle background styles for each section to aid the transition. For this version, I stayed with a white background but at a future stage I believe the website can benefit with some variety.
- Responsity: I plan to improve the general responsity of the site once I have a greater JavaScript understanding, this includes the below.
  - Ensuring the Navbar reappears on scroll
  - Allowing progress bars to interactively appear
  - When desktop experience is landed on, map points appear one by one
- Logo: The brand logo is currently represented by a teal CodeDoc in the top left hand corner. I plan to design a more unique logo using Adobe Illustrator in the future.
- Language: I intent on translating the website to mandarin chinese to tailor for the chinese market. This feature will be an optional change which the user can action using a button.

## Technologies Used
The main technologies used are as below.

- HTML
  Used to added content to the website
- CSS
  Used to add structure and design to my site
- CodePen
  Used for the map feature, which required alot of trial and error. CodePen was great to instantly see how my changes effected positioning.
- Bootstrap
  Used throughout the website to easily implement consitent designs, such as the below
  - Navbar: https://getbootstrap.com/docs/4.0/components/navbar/
  - Grid System: https://getbootstrap.com/docs/4.0/layout/grid/
  - Progress bars in skills section: https://getbootstrap.com/docs/4.0/components/progress/
  - Layout of entries in experience section: https://getbootstrap.com/docs/4.0/components/list-group/#custom-content
  - Form in the contact section: https://getbootstrap.com/docs/4.0/components/forms/
- FontAwesome
  - FontAwesome was used to input icons throughout the project. I used 8 different icons throughout the project.
 
- Balsamiq
  - Used in the design process for wireframes.
- Pxhere
  - Used for images and design inspiration.
- Google Fonts
  - Used for font implementation and inspiration.
- https://mycolor.space/
  -Used for pallet testing.
 -GitPod
  - Used to create, commit and push the HTML and CSS changes for the website.
 -GitHub
  - Used to deplot the website and store files and code.
 -Stackoverflow
  - Used for problem solving to implement desired designs.
  - Used to gain better understanding of how I should approach the implementation of elements.
 -W3Schools
  - Used to gather a theoretuical knowledge of elements and effects (in particular <button> element)
    https://www.w3schools.com/w3css/w3css_buttons.asp
 -W3 Validator
  - Used throghout the project to ensure I was following best practices with my code.

## Testing
### Browsers
Tested and working consistently on the below browsers for desktop.
- Google Chrome
- Microsoft Edge 
- Firefox

## Deployment
This project was created using Gitpod for commit and push actions.
This project was deployed using GitHub pages at https://daithioc95.github.io/MS1


## Credits
### Content
All the content was written by myself.

### Media
Home Image: https://pxhere.com/en/photo/33
Experience map image: https://pxhere.com/en/photo/1450907
Interactive Front-end image: https://commons.wikimedia.org/wiki/File:JavaScript-logo.png
Data Centric image: https://commons.wikimedia.org/wiki/File:Python-logo-notext.svg
Full-Stack Frameworks image: https://www.pexels.com/photo/assorted-map-pieces-2859169/
CodeInstitute logo: https://www.facebook.com/Code.InstituteIRL/
Zhejiang University logo: https://en.wikipedia.org/wiki/Zhejiang_University
University College Dublin logo: https://en.wikipedia.org/wiki/University_College_Dublin


### Acknowledgments
The experience map was taken from code the following code written by Michael Mroz and edited to match my map and content.
Inspiration for elements in the about and skills section layout came from the resume section of CodeInstitutes "Mini Project". This include the using the font aweson icons and the progress bars.
Inspiration to use fontawesome icons with hover glow in the footer section was also from the CodeInstitutes "Mini Project".
Inspiration for the circular headshot image in the about section came from the the HTML/CSS Project - love running section of the CSS Fundamentals module.
Thanks to the Code Institute Tutors for helping me problem solving, in particularly regarding the my experience section to satify the HTML W3 Validator.
Thanks to my mentor, Mark Railton for guidence throughout the project.
Thanks to the Code Institute Slack channel for providing me with a wealth of information on each aspect of the project.
