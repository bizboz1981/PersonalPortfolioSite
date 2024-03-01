![Am I Responsive Mockup](assets/documentation/am_i_responsive.png)

# Bill Saunders: Personal Portfolio Site
Link to live project: https://bizboz1981.github.io/PersonalPortfolioSite/index.html

## Table of Contents
[User Experience (UX)](#user-experience-ux)  
[Features](#existing-features)  
[Design](#design)  
[Technologies Used](#technologies-used)  
[Testing](#testing)  
[Deployment](#deployment)  
[Credits](#credits)  

# User Experience (UX)
## User Stories
### First Time Visitor Goals
1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the skills, interests, and ethos of Bill.
2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find coding projects and to be inspired about software and web development.
3. As a First Time Visitor, I want to find and use a simple contact form and social media links to get in touch with Bill.

### Returning Visitor Goals
1. As a Returning Visitor, I want to be able to view the new projects Bill has linked from GitHub.
2. As a Returning Visitor, I'm interested in learning about any new skills or technologies Bill has acquired, which could inspire my own learning paths or professional development.
3. As a Returning Visitor, I want to be able to contact Bill to explore opportunities for collaboration, to give feedback, or ask questions.

### Frequent Visitor Goals
1. As a Frequent Visitor, I want to see the latest projects Bill has worked on, including any updates to existing projects, to understand his current focus and skills development.
2. As a Frequent Visitor, I'm interested in Bill's career advancements, such as new roles, responsibilities, achievements, or changes in his professional direction.
3. As a Frequent Visitor, I look forward to reading Bill's latest blog posts or articles that share insights into his field of expertise, reflect on industry trends, or provide valuable advice to others in the profession.

# Features & Structure
## Existing Features
### Site-Level Elements
##### Navbar
This is a [bootstrap](https://getbootstrap.com) navbar that is fixed to the top of the page. It contains links to the Home, About, Projects and Contact sections of the site. The navbar is responsive and collapses to a hamburger menu on smaller screens.
![alt text](assets/documentation/navbar.png) 
![alt text](assets/documentation/navbar_collapsed.png)
##### Social Media Links
These are located in the footer of the site and are represented by the social media icons for LinkedIn, GitHub, Instagram and Twitter. They are links to Bill's profiles on these platforms.
##### Footer
The footer uses bootstrap classes and the code was sourced from [mdbootstrap](https://mdbootstrap.com/docs/standard/navigation/footer/). It represents my intention to buy and deploy to a custom domain.
![alt text](assets/documentation/footer_social.png)
### Page-Level Elements
#### Home
The home page is all about getting a sense of who Bill is. The feel of the site is clean and slick, with a modern, techy feel. The colour scheme is grey with a the odd pop of lime green and hot pink.
##### Hero Image
This is a full-width image of Bill Saunders, the site owner, and is the first thing the user sees when they visit the site. It is designed to be eye-catching and to give the user a sense of who Bill is and what he does.
##### Buzz Words
Catchy phrases that describe Bill's skills and interests. These are designed to be impactful and to reinforce the user's sense of what Bill is about. A pop of lime green is used to make one of the buzz words stand out.
##### All about Bill
This is essentially a personal statement written in a distinctive and personal style, rather than a dry, corporate bio. It is designed to be engaging and to give the user a sense of Bill's personality and ethos.

#### About
The branding on the About page is consistent with the homepage. The page is designed to give the user more detail Bill's background and career journey. There is no hero image on this page - the visuals do the work instead.
##### Timeline
This is a timeline of Bill's career, with key events and achievements. It is designed to be easy to read and to give the user a sense of Bill's career journey. The template code was sourced from a [Code Institute lesson](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/) and 'translated' to Bootstrap 5 and customised to suit the site's design.
##### Skills & Competencies
This provides some more detail on the programming languages, technologies and tools that Bill is skilled in. The progress bars were inspired by [Matt Rudge](https://github.com/lechien73)'s lesson on building a [resume page](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4/) in the Code Institute course. However, the code was taken from [Bootstrap 5](https://getbootstrap.com/docs/5.3/components/progress/) and customised with custom css.
#### Projects
This is a list of Bill's favourite project on GitHub. The look and feel of the site is on-brand, consisting on mainly grey with pops of lime green and hot pink. The hero image on this page was generated by AI ([DALL-E](https://openai.com/dall-e-3)) and is designed to be eye-catching and to give the user a sense of what the page is about.

#### Contact
This is a simple contact form that allows the user to get in touch with Bill. The branding is consistent with the rest of the site. The form is designed to be simple and easy to use, with a clean, modern feel. The form is very basic HTML but uses [Bootstrap 5](https://getbootstrap.com) classes for style and format.

## Future Features
* I will leverage JavaScript to programmatically interact with [GitHub's API](https://docs.github.com/en/rest/using-the-rest-api/getting-started-with-the-rest-api?apiVersion=2022-11-28), enabling the automatic population and updating of the list showcasing my most recently starred repositories.
* I will use JavaScript to randomly highlight individual 'Buzz Words' in lime green for a few seconds.
* I will use JavaScript to recreate the parallax effect, as this is not supported in CSS in mobile browsers I tested (apparently due to the [high repaint cost](https://forums.developer.apple.com/forums/thread/99883)).
* I will, in due course, deploy to a custom URL.

# Design
## Colour Scheme
The colour scheme uses a lot of grey. The main colour "brand-dark-gray" (#2f2f2f) was sampled from the hero image on the home page. The inspiration of pairing this with the secondary brand colour green ("brand-lime": #00ff00) and the tertiary pink ("brand-pink": #ff00ff) was taken from [here](https://www.schemecolor.com/pink-grey-green.php). Contrast was checked for accessibility using[WebAIM's contrast checker](https://webaim.org/resources/contrastchecker/). The green and pink are used sparingly to add a pop of colour and to make the site feel modern and fresh. The green is used for the navbar, the hero image on the home page, the 'Buzz Words' on the home page, the progress bars on the About page and the 'Send' button on the Contact page. The pink is used for the 'Buzz Word' on the home page and the 'Send' button on the Contact page. The grey is used for the background of the site and the text. The white is used for the text and the progress bars on the About page.

# Technologies Used
## Languages
* HTML5
* CSS3
* Markdown

## Applications
* [Git](https://git-scm.com) - for version control
* [GitHub](https://github.com) - for version control and website hosting
* [Visual Studio Code](https://code.visualstudio.com) - for coding the project and managing the files
* [Adobe Photoshop](https://www.adobe.com/uk/products/photoshop.html) - for photo editing
* [OpenAI's DALL-E](https://openai.com/dall-e-3) - for image generation
* [Convertio](https://convertio.co/) - for converting images to webp format

## Frameworks, Libraries & CDNs
* [Google Fonts](https://fonts.google.com/) - 'Exo' is used for headings and the monospace 'Anonymous Pro' is used for body text for it's 'codey' feel.
* [Font Awesome](https://fontawesome.com/) - Font Awesome is used for social media icons.
* [Bootstrap 5](https://getbootstrap.com) - Bootstrap 5 is used extensively througout the project for responsiveness and for providing template code for several elements. However, all Bootstrap elements are styled with custom css.

## Other Tech & VS Code Extensions
* [GitHub CoPilot]([https://](https://github.com/features/copilot)) - I used this for checking code, troubleshooting and debugging - **not for writing code**.
* [Emmet](tps://code.visualstudio.com/docs/editor/emmet) - for boilerplate html and shortcuts.
* [Prettier](https://prettier.io) - for code formatting and code completion ('intellisense').
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - for live previewing of the site.
* [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) - for markdown editing.
  

## Learning Resources
I have credited specific resources throughout the code, but during my learning journey I have used the following resources extensively and my whole project has been inspired by elements of them all:
* [Chat GPT](http://chat.openai.com) - I have used Chat GPT to explain concepts to me, and to help me use VS Code and the terminal more efficiently. I have also used it to explain code snippets from other sources in greater detail. I have specifically not used Chat GPT to write code for me. All source code in the project is credited where approrpriate.
* [W3 Schools](https://www.w3schools.com) - used extensively for inspiration, problem solving and occasionally for template code.
* [Stack Overflow](https://stackoverflow.com) - primarily for troubleshooting issues.
* [Codecademy](https://www.codecademy.com) - as a user of Codecademy for a number of years, I must credit this site for any background knowledge I may have had.

# Testing
## User Stories

## Manual Testing
### Features Testing
| Feature                | Test Case                                     | Outcome                                                       |
| ---------------------- | --------------------------------------------- | ------------------------------------------------------------- |
| Logo                   | Click on the Logo                             | User taken to homepage                                        |
| Navbar > Homepage      | Click the Home link on each page              | User brought to homepage successfully                         |
| Navbar > About Page    | Click the About link on each page             | User brought to About page successfully                       |
| Navbar > Projects Page | Click the Projects link on each page          | User brought to Projects page successfully                    |
| Navbar > Contact Page  | Click the Contact link on each page           | User brought to Contact page successfully                     |
| Social Media Links     | Click on each social media icon in the footer | User taken to the relevant social media page                  |
| Contact Form           | Fill in the form and click 'Send'             | Form data is sent to the correct server and confirmed to user |

### Device & Browser Responsiveness Testing

| Device/Browser        | Appearance | Responsiveness | Issues                        |
| --------------------- | ---------- | -------------- | ----------------------------- |
| iPad Air/Safari       | Good       | Good           | None                          |
| iPhone 14 Pro/Safari  | Good       | Good           | Parallax effect not supported |
| iPhone 14 Pro/Firefox | Good       | Good           | Parallax effect not supported |
| iPhone 14 Pro/Chrome  | Good       | Good           | Parallax effect not supported |
| Macbook Air/Safari    | Good       | Good           | None                          |
| Macbook Air/Chrome    | Good       | Good           | None                          |
| Macbook Air/Firefox   | Good       | Good           | None                          |
| Windows 10/Chrome     | Good       | Good           | None                          |
| Windows 10/Firefox    | Good       | Good           | None                          |
| Windows 10/Edge       | Good       | Good           | None                          |

In addition to the above, I have tested extensively in the Chrome DevTools device emulator and have tested the site on a number of other devices and browsers. The site is fully responsive and works well on all devices and browsers I have tested. The only issues I encountered were with the parallax effect, which is not supported on my iPhone 14 Pro, and I will need to address this in future updates with JavaScript. To solve the issue for now, I have set `background-attachment: scroll` in the media query for mobile devices.

I used the following media queries to ensure the site was responsive on all devices. The code was taken from [Coding with Jaybird](https://github.com/codingwithjaybird)'s GitHub. You can see this is in action on this [video here](https://youtu.be/BGIj3womITo?si=58FcgvDYxeEX7lY5):



```
/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) {
  #breakpoints::before {
    content: "Small screens and up (>576px Landscape phones) - 'sm'";
    background-color: aquamarine;
  }
}

/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) {
  #breakpoints::before {
    content: "Medium screens and up (>768px Tablets) - 'md'";
    background-color: aquamarine;
  }
}

/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) {
  #breakpoints::before {
    content: "Large screens and up (>992px Desktops) - 'lg'";
    background-color: aquamarine;
  }
}

/* X-Large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {
  #breakpoints::before {
    content: "Extra Large screens and up (>1200px Large Desktops) - 'xl'";
    background-color: aquamarine;
  }
}

/* XX-Large devices (larger desktops, 1400px and up) */

@media (min-width: 1400px) {
  #breakpoints::before {
    content: "Extra Extra Large screens and up (>1400px Larger Desktops) - 'xxl'";
    background-color: aquamarine;
  }
}
```


### Online Validation Services
* [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) - all colours used passed the contrast checker. Apart from white on brand dark grey (which has a contrast ration of 13.38:1) the main contrast is brand lime green on brand grey which has a score of almost 10:1.
  ![alt text](assets/documentation/contrast_check.png)
* [HTML Validator]([https://validator.w3.org) - all pages received a clean bill of health, with no errors or warnings to show.
  ![alt text](assets/documentation/html_validation.png)
* [CSS Validator](https://jigsaw.w3.org/css-validator/) - when scanning the URL of the site, the validator finds a surprising number of errors and warnings. However, all of these are associated with Bootstrap and nothing to do with the custom css (in fact, the [Code Institute site](https://codeinstitute.net)) generates a similar number of Bootstrap errors. The custom css (on direct input) has no errors.
  ![alt text](assets/documentation/css_validation.png)
* [accessiBe](https://accessibe.com/accessscan) - accessibility scan informs me that the website is mostly compliant, but did suggest some areas for improvement, which I will address in future updates., Interestingly, the [Code Institute site](https://codeinstitute.net) fails on many of the same elements, suggesting that 'accessibility' is more of an ongoing commitment rather than a realistic, perfect end-state.


### Lighthouse
I used the Lighthouse tool in Chrome DevTools to test the site's performance, accessibility, best practices and SEO. The results were as follows: 98% | 100% |100% |100% | NA. The only area for improvement was the 'Performance' score, which was 98%. This was partly due to the size and performance of the hero image. I plan to change this to webp format.
![alt text](assets/documentation/lighthouse.png)

### Bugs

# Deployment
My [site](https://bizboz1981.github.io/PersonalPortfolioSite/) is deployed to [GitHub Pages](https://pages.github.com). 

# Credits
In addition to the technologies used, I would like to credit the following for inspiration and assistance:
* My mentor, Jack Wachira
* [Smashing Magazine](https://www.smashingmagazine.com/2020/08/application-color-schemes-css-custom-properties/)
* [Thrive - Juices & Smoothies](https://elainebroche-dev.github.io/ms1-thrive/) - a Code Institute Project
* [Gary Sheng](https://www.garysheng.com)