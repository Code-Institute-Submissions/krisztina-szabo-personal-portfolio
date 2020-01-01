# Krisztina Szabó Personal Portfolio Website

This page is my portfolio website. I made it as my first milestone project at Code Institute.
The purpose of the project is to introduce myself and my work to potential customers and recruiters.
Browsing this page the user can get every kind of useful information about me: my portfolio, my work history, my interests, a group of  the links to my social media accounts and to my GitHub repository. If the user it's not interested in browsing, they can reach my resumé in printable (pdf) version directly from the homepage.
The website contains 4 pages: *Homepage*, *About me*, *My portfolio* and *Get in Touch*. I built my project using HTML5, CSS3 and Bootstrap.

![Responsive design](https://github.com/krisztinatxt/krisztina-szabo-personal-portfolio/blob/master/assets/images/amiresponsive.JPG "Responsive Design")

## UX

### User Story

* As a new visitor of the website, I want to easily navigate on the page.
* As an interested client, I want to have a contact form easy to fill out.
* As a potential client, I want to get to know Krisztina's background and personality to see if I want to hire her.
* As a recruiter, I would like to get an insight into Krisztina's work and I also want to have a printable resumé what I can present to my superior.
* As an employer, I visit this page to see a showcase of a potential employee's work.

### Wireframes

 When I started working on this project, I had a picture of the site in my head. This picture has changed a lot in the last few weeks. You can see the progress below.

[First drafts](https://github.com/krisztinatxt/first-milestone-project/tree/master/wireframes/first)

[Planning of the final version, on different devices](https://github.com/krisztinatxt/first-milestone-project/tree/master/wireframes/modified)

## Features

### Existing Features

* On the Homepage (index.html) you can see the menu navigation bar with relevant Fontawesome icons. When you hover, the background color turns green (#3b853f). This color sees you through the whole page, you find it in the portrait picture,  borders, buttons.
  * Besides this gradiation, I used only black and white.
  * You can also see a small introduction, a portrait picture (with an ease in transition and a green hover), three navigation buttons helping in orientation on the page, and also three rounded icons leading you to my social media accounts.
* On About me page you can find two navigation bars, first one is the menu I've presented before, the other one is the footer containing two buttons, drawing the attention to my LinkedIn profile and GitHub repositories. These two navigation items appear on three of the four pages (I thought that having a footer on my Homepage makes the general aspect too cluttered.
On this page, I have a small introduction about myself, and a timeline with my imaginary and real work history. The basic structure of the timeline was written by Andrew R McHugh, you can find the source code [here](https://codepen.io/armthethinker/pen/nEtke). It was significantly modified.
* My portfolio page is a showcase of my recent work (also fiction). Under the card, you can see the name of the project, and for more information, you can click on the navigation button located beneath each of the cards.
  * If you click on the pictures, it leads you to the same page as "More information".
* On the Get in touch page, you can contact me using a form. After typing your name and email address, you can choose the best option for scheduling the project, and you can also tell me about your ideas.
Your name and your valid email address are required.  

### Features Left to Implement

* In the future I plan to add further projects, work experience to make My portfolio and About me pages better.
* On my Get in touch page, I would like to fix my form to work properly, so when I have enough knowledge for this, I will come back to this section, and I will make the submit button work.
* After having enough knowledge, I want to come back, and use jquery and popper.js to make my menu transform to a drowdown menu on small screens.
* Getting to know how to use JavasScript, I want to fix my form (currently you can submit with Choose your answer).

## Technologies Used

* [HTML](https://en.wikipedia.org/wiki/HTML5)
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
* [Bootstrap](https://getbootstrap.com/)
* [HTML-Formatter](https://htmlformatter.com/)
* [HTML-Validator](https://validator.w3.org/)
* [CSS-Beautifyer](https://www.freeformatter.com/css-beautifier.html)
* [CSS-Validator](https://validator.w3.org/)
* [Autoprefixer](https://autoprefixer.github.io/)
* [FontAwesome](https://fontawesome.com/)
* [GoogleFonts](https://fonts.google.com/)
* [markdownlint](https://dlaa.me/markdownlint/)
* [AmIResponsive](http://ami.responsivedesign.is/)

## Testing

All links were manually tested, and all of them open in a new tab using `target:"_blank"` and `rel="noopener"` attribute.
The whole website is responsive using a different types of devices.

### Fixed issues

* My menu navigation bar (the last list item of it) created an overflow on my page, so I had a narrow white space on the right. After trying everything I could do it, I asked the Slack community about the reason of the overflow, they helped me out with it. The problem was with the Get in touch list item's bootstrap part, changing the col-sm to 2 solved the problem.
* I used px to set the height of my background image, which was nice on a small desktop screen, but it gave me a white space browsing from a phone, tablet, or wider screen. With this issue, one of the tutors helped me out: I changed the height to 100% and I set a min-height. After that, I realized that I have the same problem with my contact form, and I fixed it using the same method.
* Before submitting this project, I posted my GitHub page in Slack, and I've got a lot of useful feedback on how to make this site more professional.
* I changed the structure of the code, I fixed some inconsistency in my bootstrap grid, I made the content more readable, I made my portfolio picture clickable,  I updated the links, I edited my README file. Thanks for the help to [Simon Daehlin](https://github.com/Eventyret) and [Richard Wells](https://github.com/D0nni387).

#### Homepage

* When you open my portfolio website, you can see on each page the menu with Fontawesome icons.
  * If you `hover`, the section changes the background to green. The same thing happens if you move your cursor to my portrait picture or any of the buttons.
* In the background, you can see a picture, which covers the whole page.
* You can jump to Get In touch form (via I have and idea button), to About me page (via Tell me more success button) and you can also download my printable CV by clicking on Download my CV button.
* Below the success buttons, you can connect me on social media accounts (Facebook and LinkedIn) or You can visit my GitHub repositories.
* On every page you can find a footer, where you can see two buttons: one leading you to my LinkedIn profile and one to my GitHub repositories.
  * All of the buttons on the website have the same style.

#### About me

* In About me section you can see a textbox with a self-introduction.
* Under the introduction, there is a timeline with five different sections (icon, year, positions, a dividing line, and a description).
* The footer section is the same as before.

#### My portfolio

* My portfolio contains six `cards` showing my "recent projects".
  * In the body of the card, you can see the name of the project, and by clicking on the  "More information" button, a new tab will open with the original page of the projects.

#### Get in touch

* The Get in touch page contains a contact form and the footer.
* Before you submit the form, you have to type your name, and your valid email address, these sections are required.

## Deployment

My first website was written in GitPod, and it's hosted using Github, deployed from the master branch (via Settings). I've saved after every important change: starting with git status, git add ., git commit -m"" and in the end pushing the git to the Github repository.
After every commitment, when you refresh the repository, you can see the changes.
The main (landing) page of the website is named index.html.

### How to deploy

* Login to GitHub.
* From the list of the repositories, select [this one](https://github.com/krisztinatxt/first-milestone-project).
* From the menu, click on the Settings (you can find under the name of the repository).
* Scroll down to the Page section, select Master Branch from the dropdown menu.
* The website is deployed, you can find the link in Page section.
* If it's not working, or you can't see the changes you've made, wait a minute, and refresh the page.
* Every time you commit changes, you can find the link of the deployed site at the same place.

### Local deployment

If you want to clone this project and run locally, you have to do this:

* Follow [this](https://github.com/krisztinatxt/first-milestone-project) link to my repository on GitHub.
* Click on the Clone or download button (right side, next to the Gitpod button).
* Copy the clone URL.
* In your local IDE open Git Bash.
* Change the working directory to the location where you want the cloned directory to be made.
* Type `git clone`, and paste the URL you copied from the Clone or download section.
* Press Enter. Your local clone it's created.

## Credits

### Content

Most of the content is written by me.

The timeline code was written by [Andrew R McHugh](https://codepen.io/armthethinker/pen/nEtke).

The base of the Deployment section is taken from a  README  written by [Anna Greaves](https://github.com/AJGreaves).

### Media

* The portrait picture is my property.
* The background picture of the homepage is from [Pexels](https://www.pexels.com/photo/gray-laptop-computer-showing-html-codes-in-shallow-focus-photography-160107/).
* The photos used in this site were obtained from [Steam](https://store.steampowered.com/), [Prezi](http://prezi.com), [Arab Games](https://www.ar-gamez.com/planetbase/) and [Nintendo](https://www.nintendo.nl/Games/Nintendo-Switch-download-software/Machinarium-1464925.html).

### Acknowledgements

* The bootstrap codes are from the official website of the [Bootstrap](https://getbootstrap.com/).
* I  set the responsive breakpoint using [this](https://gist.github.com/EmranAhmed/8044351) template.
* I couldn't have understood how to Bootstrap without [this video](https://www.youtube.com/watch?v=zDpCejbl1sU&amp;feature=youtu.be). Thanks, [Anna](https://github.com/AJGreaves)!
* I learned how to center a form from [this article](https://stackoverflow.com/questions/20853066/how-to-center-form-in-bootstrap-3).
* To write this README I used this [template](https://github.com/Code-Institute-Solutions/readme-template) and this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
* Special thanks to [Richard Wells](https://github.com/D0nni387) and [Simen Daehlin](https://github.com/Eventyret) for the detailed feedback on my project.
* I learned a lot just browsing other sites using devtool, and reading the Slack. Thank you for the help to my mentor, the tutors and the Slack community.

**This site is for educational use.**

***Krisztina Szabó***

***Code Institute***

***2019***
