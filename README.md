# Haley Schafer Portfolio
Stream One Project: User-Centric Frontend Development - Code Institute 

This is my portfolio website to present to prospective employers. The portfolio highlights six projects that cover a range of technologies, as well as including a bit about myself, my coding skills, and a contact form. The contact form does not currently work, and it's just for presentation on the site. As I am bilingual, it has both an English and a French version.


## Demo
A live demo can be found [here](https://www.haleyschafer.com/).

![Desktop Demo](https://raw.githubusercontent.com/hschafer2017/HSCHAFER-Portfolio/master/assets/images/portfolioview.gif "Desktop Demo")


## UX
My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist design. The greyscale color scheme was chosen to create a sleek and modern feel. 

For employers, I wanted to provide them with a brief overview of myself and my capabilities via a user-friendly design. This way, they would be able to get a glimpse of who I am, my background, work I've done, and my skills, with the option to contact me if they choose. In the 'Work/Travail' section, I wanted them to be able to quickly access work that I've done, providing a short summary of the project and main technologies with a link to each GitHub Repository and live demo. A link to my LinkedIn profile, my GitHub, and a downloadable PDF version of my CV were also provided for their ease of access. 


## Technologies
1. HTML
2. CSS
3. Bootstrap (3.3.7)


## Features
This site uses the scrollSpy feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. The navbar also stays collapsed regardless of the screen size to promote a minimalist design.


### Features Left to Implement
In the future, I would like to add further projects that I've worked on to create a more comprehensive 'work/travail' section. I would like to also add animations to the progress circles in the "skills/compétences" section to animate on a hover. 


## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo of me. They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer. 

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar. 

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. During the testing phase, I realized that ```background-attachment: fixed``` was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the ```background-attachment: scroll``` property value was added in a media query.


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/hschafer2017/HSCHAFER-Portfolio.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.


## Credits

### Content
All content in the "About Me/À Propos" and "Work/Travail" sections in this portfolio site were written by me. 

### Media
All photos were taken from [Pexels](https://www.pexels.com/), a stock image library, with the exception of the photo of myself in the background of the 'about me/À Propos' section in the desktop view. A greyscale filter was applied to each one prior to upload to preserve the greyscale theme. 

### Acknowledgements
The scrollSpy delay JavaScript function was found through this tutorial [here](https://www.abeautifulsite.net/smoothly-scroll-to-an-element-without-a-jquery-plugin-2).

The progress circles from the skills section are modeled after the following Stack Overflow [example](https://stackoverflow.com/questions/14222138/css-progress-circle). They were significantly modified to fit the styling, sizing, and progress for each skill.

The media query for the collapsed navbar regardless of viewport width was taken from this [site](https://www.codeply.com/go/iaM1zcNsQB/bootstrap-navbar-always-collapsed).

**This is for educational use.** 
