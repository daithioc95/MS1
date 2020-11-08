# User Centric Frontend Development Milestone Project 

This project is a portfolio website to showcase my skills and experience to recruiters and potential clients.
The is an interactive website which include designs which can be appreciated by the user.
The website is a vehicle for my brand and a means of contact for interested parties.

## UX

The website will contain a simple design to ensure the primary function of providing information to the audience on devices of all sizes.
To complement this, an interactive, easy on the eye design will be implemented.
This will be achieved by executing a single paged long scroll website, with options to navigate to any particular sections using the Menu bar.
Implementing this design will keep the audience engaged and compliment the users stories by firstly feeding the user with “what” it is that do, secondly, showing projects to convey “How” I do it and finally, providing a means of contact should they want to collaborate.

In creating my website, I followed the 5 levels of development below and have outlined these in the following headings.
This is an effective means of web development which ensures an appropriate order of approach with each plane becomming less conceptual as the project evolves.
 This process originates from Jesse James Garrett's book, The Elements of User Experience. 

- Strategy Plane
- Scope Plane
- Structure Plane
- Skeleton Plane
- Surface Plane

### Strategy Plane
The strategy plane is the most high level plan of the website.
This planes is important as it ensures that all the following sections and website end product aligns to the websites objectives.
For this plane, I identified my primary objects and user stories of the website below.

#### Project Objectives
- Portray my experience and what the website is for
- Showcase my CSS & HTML skills to the audience.
- Provide the user with a means of contact.

##### User Stories
- As a recruiter/potential client, I want to see the web developers experience, so that I can see if this is relevant to the job/project requirements.
- As a recruiter/potential client, I want to see the web developers’ skills, so that I can see if these skills match the job/project.
- As a recruiter/potential client, I want to see the developer’s portfolio, so that I can see if his previous projects require capabilities relevant to this job/project.
- As a recruiter/potential client, I want to easily find this information while appreciating the websites design, so that I can see that the developer is competent in front-end development.
- As a recruiter/potential client, if interested I want to contact to the developer, so that I can see if he is available for work.

### Scope Plane
The scope plane is included in order to identify needed sections and features for the website.
This is an important section of the process as it ensures the project alignes with the previous mentioned objectives in the Strategy Plane.
It also reduces the risk of "Scope Creep" whereby project features grow in number throughout development.

- Necessary sections which align to the user stories are identifies as below.
  - Home
  - About
  - Experience
  - Portfolio
  - Contact
  
 - The next stage of the process was to brainstorm features to ensure I Showcase my CSS & HTML skills to the user. 
 - In addition to the usual sections a portfolio website contains, I wanted to use an interactive map as a statement piece to showcase CSS skills and provide information on my international experience.

### Structure Plane
The structure plane is the next stage which outlines how to projects sections and features will fit into the website.
While anticipating the text-heavy nature potfolio websites can be, my objective for this plane was to provide the content to the user in an interactive and easy to digest manner.

#### Design Process 
  - I decided on the interactive map feature for large screens only as using a small screen would be difficult to select specific points on the map.
  - When searching for potential maps on pxhere.com, I can accross a treasure island like map which suited the feature aestetically.
  - Using the lightest and darkest colors from the map, I input this to https://mycolor.space/ to generate a 3 color gradient and thats when I choose a teal-like #5FFBF1 as my primary site color.
  - This color was used as the header font color thoughout.
  - Paragraph font was a standard black color throughout. 
  - Other features I decided on were a progress bar for skills, I took inspiration for thing for the mini-project as it is a great was to visually portray my skills.
  - Font Awesome Icons were used thoughout the website to provide more infomation on sections and links.
 
### Skeleton Plane
Once the sections and features of the website is identified, the skeleton plane can begin.
This plane focuses on the arrangement of the sections and features of the website.

- I created wireframes for both the mobile and browser to visualise the arrangment of my scope.
I began this by using pen and paper with the bootstrap grid system in mind and once a general, responsive idea formed, I created the below using balsamiq.

- See Desktop Wireframe [here](assets/MS1_Desktop.pdf)

- See Mobile Wireframe [here](assets/MS1_Mobile.pdf)

- The only major changes between the wireframes and the final site version is that I changed the mobile version portfolio section to include 1 entry per column as opposed to 2 in the wireframe.

### Surface Plane
The final plane involves the execution of everything collated and in the previous 4 planes. 
It is important to ensure this planes aligns to the previous 4 planes however when the real website is being designed different stylistic decidions can be made in a agile manner. For example, I decided on my font in this stage as I could visually identify by trial and error suitable options.

#### Features
Breakdown of the website features currently implemented on the website.

##### Navbar
I created the Navbar using Bootstrap and editing the color to suit my websites design.

##### Home
Simple image which I found on pxhere.com.
I choose this as the yellow glow from the wood matches the teal and the map feature image to appear later.
Additionally, the laptop, phone, books etc. represent convey a design/service use case for the website. 

##### About
The About section contains a heading with a circle container and a circle headshop image.
The end of the about section contains a progress bar section.
Other features include font awesome icons.

##### Experience
For desktop, this seciton includes an interactive map which shows experience depending on location.
When the location is selected, experience relvant to this location apeears in an expanded box.
I have included icons with links to media and files to back up my experience.

For mobile, I included the same content, however to make up for lack of visuals compared to the desktop version, I included the organisations logos. 

##### Porfolio
For the portfolio seciton, I included a simple bootstrap grid design to show each project in a size-responsive manner.

##### Contact
The contact seciton is designed using a bootstrap form.
An icon is used to transition into this section with relevant information prompted to contact the web developer. 

##### Footer
I included a simple footer design, I used font awesome icons to represent each link. 

#### Future Features
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
- GitPod
  - Used to create, commit and push the HTML and CSS changes for the website.
- GitHub
  - Used to deplot the website and store files and code.
- Stackoverflow
  - Used for problem solving to implement desired designs.
  - Used to gain better understanding of how I should approach the implementation of elements.
- W3Schools
  - Used to gather a theoretuical knowledge of elements and effects (in particular <button> element)
    https://www.w3schools.com/w3css/w3css_buttons.asp
- W3 HTML Validator
  - Used throghout the project to ensure I was following best practices with HTML code.
- Jigsaw CSS Validator
  - Used throghout the project to ensure I was following best practices with CSS code.
 
## Testing
### Browsers
Tested and working consistently on the below browsers for desktop.
- Google Chrome
- Microsoft Edge 
- Firefox

## Deployment
This project was created using Gitpod for commit and push actions.
This project was deployed using GitHub pages at https://daithioc95.github.io/MS1

## Known Bugs and Fixs
- Progress Bars
  - When rendered to mobile size, the progress bars for 70% and 80% render to an almoast identicle size. This is a known bug which I plan to correct later on.

## Credits
### Content
All the content was written by myself.

### Media
- Home Image: https://pxhere.com/en/photo/33
- Experience map image: https://pxhere.com/en/photo/1450907
- Interactive Front-end image: https://commons.wikimedia.org/wiki/File:JavaScript-logo.png
- Data Centric image: https://commons.wikimedia.org/wiki/File:Python-logo-notext.svg
- Full-Stack Frameworks image: https://www.pexels.com/photo/assorted-map-pieces-2859169/
- CodeInstitute logo: https://www.facebook.com/Code.InstituteIRL/
- Zhejiang University logo: https://en.wikipedia.org/wiki/Zhejiang_University
- University College Dublin logo: https://en.wikipedia.org/wiki/University_College_Dublin


### Acknowledgments
- The experience map was created by adapting and editing code written by Michael Mroz which can be found in the following link (https://codepen.io/mirichan/pen/jEBmyG).
- Inspiration for elements in the about and skills section layout came from the resume section of CodeInstitutes "Mini Project". This include the using the font aweson icons and the progress bars.
- Inspiration to use fontawesome icons with hover glow in the footer section was also from the CodeInstitutes "Mini Project".
- Inspiration for the circular headshot image in the about section came from the the HTML/CSS Project - love running section of the CSS Fundamentals module.
- Thanks to the Code Institute Tutors for helping me problem solving, in particularly regarding the my experience section to satify the HTML W3 Validator.
- Thanks to my mentor, Mark Railton for guidence throughout the project.
- The form submit button message prompt was completed using JavaScript written by Mark Railton. 
- Thanks to the Code Institute Slack channel for providing me with a wealth of information on each aspect of the project.
