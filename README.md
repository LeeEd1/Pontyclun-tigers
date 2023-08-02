# Pontyclun Tigers

Pontyclun tigers is a branch of Steve Tottle Tae Kwon Do (TKD) located in Pontyclun, South wales. Our aim is to enrol as many children between the ages of 3 and 6 and with encouragement and support, kick start their journey into the TKD world! Established in 2018 We have secured our own unit with all the necessary equipment for any child to become a young tiger.

Our ultimate goal of this website is to raise as much awareness as possible for Pontyclun tigers, introduce ourselves and show everyone what we are able to offer.

![Site view across devices](/assets/readme-img/pagelayout.PNG)

Pontyclun Tigers site is live and the link can be found [here](https://leeed1.github.io/pontyclun-tigers/)

## UX

### Site Purpose

Our main objective is to raise awareness about our identity and mission. We aim to reach a wider audience by using different means and platforms to share information about our values, principles, and overall goals.

### Site Goal

Our site goal is to reach as many parents and children as we possibly can to start their journey with us and provide them with as much information as we possibly can.

### Audience

Our audience is aimed towards children aged between 3 and 6 who are willing to start a new adventure in TKD, develop discipline and have fun along the way.

### Current user goals

- To gain as much information about Pontyclun Tigers TKD
- View our current class times and location
- View any updates or changes in times/events

### New user goals

- To be able to navigate the website easily with concision.
- For information to be up to date and informative
- Aim to captivate and inspire all those visiting the website for the very first time.

## Design:

### Typography

Merriweather was selected for all Headings and Nav Bar with Monserrat selected for all other content on the page. I chose these after many google searches because i found them to be easy on the eye and very clear to read.

### Colour Scheme

The colour scheme was based around the logo and general colours of the tigers club.

![Site Colours](/assets/readme-img/Capture.PNG)

### Images

All images were taken from the client except the two main images which were sourced through pexels.

### WireFrames

#### Desktop wireframes

- View Home Wireframe [Here](/assets/readme-img/homewire.pdf)
- View About Wireframe [Here](/assets/readme-img/aboutwire.pdf)
- View Contact Wireframe [Here](/assets/readme-img/contactwire.pdf)

#### Mobile Wireframes

- View Mobile Wireframes [Here](/assets/readme-img/mobilewire.pdf)

## Features:

### NavBar

This is the navbar for both desktop and tablet devices, I decided to keep full nav bar for tablet as it is one less click for the user.

![Navigation-bar](/assets/readme-img/navbar.PNG)

Below is the navbar for mobile devices which collapses to a Hamburger.

![Navigation-mob](/assets/readme-img/navbarmob.PNG)

### Home page

The hero image for the landing page is the gym the students will be training in with the equiplment that will be used. I feel this is important as it gives potential members a flavour of what to expect prior to attending the venue. This page also displays a degree of dedication and authenticity from the club due to the quality and range of equpiment and space. As shown below.

![gym image](/assets/readme-img/gymhome.PNG)

Below the hero image is a detailed histology of how the club was established. This was provided by the client. Below welcome to pontyclun tigers I changed h2 from About us to Introduction, On reflection I found it to be confusing with About us then a navlink with About.

![About section](/assets/readme-img/gymabout.PNG)

The last section of the home page is the potential benefits of TKD.

![Benefit section](/assets/readme-img/gymbenefit.PNG)

### About page

The about hero image is another angle of the gym followed by a personal statement from the gym owner and classes.

![about page](/assets/readme-img/aboutpage.PNG)

### Contact page

The contact page features a contact form for registering interest followed by an interactive map pinpointing where the gym is located.
![Form](/assets/readme-img/contactform.PNG)
![Map](/assets/readme-img/mapcontact.PNG)

### Footer

Social media links along with youtube were added to the footer for more viewing pleasure, I also decided to add site map below for the user to quickly access the other pages from the bottom as shown below.

![Footer](/assets/readme-img/footer.PNG)

## Testing:

During testing I found my images were getting distorted or not reacting how I wanted them too due to image sizing, I fixed these issues by applying the following style rules.

![Fix1](/assets/readme-img/imagefix.PNG) ![Fix2](/assets/readme-img/imagefix2.PNG)

I also found that my logo dropped down slighly overlapping my hero image on mobile devices only, I believe this is due to my nav link compressing to a Hamburger menu. To fix this issue i added in a media query at 767px to resize the image as shown below.

![Logofix](/assets/readme-img/logofix.PNG)

I was also having issues with my hero images on smaller devices cropping out alot of the gym, to fix this I added a media query to justify the content right as shown below.

![Herofix](/assets/readme-img/herofix.PNG)

### Manual testing

Below is a table of manual testing carried out by myself.

| Feature Tested                      | Action                   | Outcome                       | Result                                   |
| ----------------------------------- | ------------------------ | ----------------------------- | ---------------------------------------- |
| Logo (All Pages)                    | Left Click               | Take user back to home page   | Succesfully loads home page              |
| Home navigation link (All Pages)    | Left click Home link     | User directed to Home page    | All links navigate and load successfully |
| About navigation link (All Pages)   | Left click About link    | User directed to About page   | All links navigate and load successfully |
| Contact navigation link (All Pages) | Left click Contact link  | User directed to Contact page | All links navigate and load successfully |
| Footer Links                        | Left click required link | User directed to correct page | All links navigate and load successfully |
| Map                                 | ctrl+scroll              | Zoom in and out to locate gym | Interacts successfully                   |

### Browsers & devices tested

- I have tested the site on Chrome, Firefox, Edge & safari with no issues.
- I have tested the site on Multiple devices such as Desktop, Laptop, tablet & mobile via link with no issues.

### Validator Testing

- Html files Passed through w3c with no issues found, As shown below.

- [Home page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleeed1.github.io%2Fpontyclun-tigers%2Findex.html)
- [About page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleeed1.github.io%2Fpontyclun-tigers%2Fabout.html)
- [Contact page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleeed1.github.io%2Fpontyclun-tigers%2Fcontact.html)
- [Thank you page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fleeed1.github.io%2Fpontyclun-tigers%2Fthankyou.html%3F)

- Css file passed through w3c with no issues found other than the 16 errors through bootstrap.

- [CSS](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fleeed1.github.io%2Fpontyclun-tigers%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Lighthouse reports

| Location        | Result                                             |
| --------------- | -------------------------------------------------- |
| Home Desktop    | ![deskhome](/assets/readme-img/deskhome.PNG)       |
| Home Mobile     | ![deskmob](/assets/readme-img/deskmob.PNG)         |
| About Desktop   | ![aboutdesk](/assets/readme-img/abouthome.PNG)     |
| About Mobile    | ![aboutmob](/assets/readme-img/aboutmob.PNG)       |
| Contact Desktop | ![contactdesk](/assets/readme-img/contactdesk.PNG) |
| Contact Mobile  | ![contactmob](/assets/readme-img/contactmob.PNG)   |

### Responsiveness

Pontyclun Tigers was meticulously crafted as a fully responsive page to ensure a smooth user experience on all devices. Throughout the testing phase, I thoroughly examined the page on different device sizes using developer tools, and I also sought feedback from various family members by sharing the live link to ensure its responsiveness across their devices as well.

### Bugs

After my final testing phases, There are no known bugs to date.

## Technologies Used:

### Languages

- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

- ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

### Frameworks, libraries & Programs used

- Font Awesome - To add icons to benefits section and social icons.
- Code Anywhere - To create my HTML and CSS files.
- Git Hub - To store my repostiory.
- Photoshop - To create the benefit section image.
- Am I Responsive - To view site on all devices.
- Google Fonts - For the fonts Merriweather and Monserrat.
- Balsimiq - For my wireframes.

## Deployment

The site was deployed through Github pages, The steps to deploy are as follows:

- In the git hub repository navigate to the settings tab.
- Under the Code and Automation section, select Pages.
- From the sourcedrop-down menu, select the MAIN branch. Then select Save.
- Once the main branch has been selected , the page with autimatically be refreshed with a detailed ribbon to diplay the deployment was successful.
- The live site can be found [here](https://leeed1.github.io/pontyclun-tigers/)

## Credits & Ackknowledgement

### Content

- [Bootstrap](https://bootstrap.com/) For my grid layouts and some styling classes.
- [fontawesome](https://fontawesome.com/) For my icons.
- [Googlefonts](https://fonts.google.com/) For my fonts.
- [Pexels](https://www.pexels.com/) For some of my images.

### Media

- [Pexel](https://www.pexels.com/photo/a-girl-practicing-karate-near-glass-windows-7045408/)
- [Pexel](https://www.pexels.com/photo/a-woman-in-karate-position-7045663/)
- All other images were sourced from client.

### People

- I would like to thank My Mentor [Spencer barriball](https://github.com/5pence) for his support throughout my first project milesone.
- I would like to thank the [Code institute](https://learn.codeinstitute.net/ci_support/level5diplomainwebappdevelopment/tutor) tutor team for their support throughout my project.
- I would like to thank my good friend [Nicolas Mobey](https://www.linkedin.com/in/nicolas-mobey-79149049) for his support and help with correcting my image issues within my page.
