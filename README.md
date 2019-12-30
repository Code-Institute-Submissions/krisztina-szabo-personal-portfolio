# Krisztina Szabó Personal Portfolio Website
This page is my portfolio website. I made as my first milestone project at Code Institute.
The purpose of the project is to introduce myself and my work to potential customers and recruiters.
Browsing this page the user can get every kind of useful information about me: my portfolio, my work history, my interests, a group of  the links to my social media account and to my GitHub repository. If the user it's not interested in browsing, they can reach my resumé in printable (pdf) version directly from the homepage.
The website contains 4 pages: *Homepage*, *About me*, *My portfolio* and *Get in Touch*. I've built my project using HTML5, CSS3 and Bootstrap.

You can check out the live demo [here](https://krisztinatxt.github.io/first-milestone-project/). 


# UX
### User Story

* As a recruiter, I would like to get an insight into Krisztina's work and I also want to have a printable resumé what I can present to my superior.
* As an employer, I visit this page to see a showcase of a potencial employed's work. </li>

### Wireframes
 When I started working on this project, I've had a picture of the site in my head. This picture changed a lot in the last few weeks. You can see the progress below.

[First drafts ](https://github.com/krisztinatxt/first-milestone-project/tree/master/wireframes/first)

[Planning of the final version, on different devices](https://github.com/krisztinatxt/first-milestone-project/tree/master/wireframes/modified)

## Features
### Existing Features

- On the Homepage (index.html) you can see the menu navigation bar with relevant Fontawesome icons. When you hover, the background color becomes green (#3b853f). This color sees you through the whole page, you find it in the portrait picture,  borders, buttons. Besides this gradiation, I've used only black and white.
You can also see a small introduction, a portrait picture, three navigation buttons helping in orientation on the page, and also three rounded icons leading you to my social media profiles.
- On About me page you can find two navigation bars, first one is the menu I've presented before, the other one is the footer containing two buttons, drawing the attention to my LinkedIn profile and GitHub repositories. These two navigation items appear on three of the four pages (I thought that having a footer on my Homepage makes the general aspect too cluttered.
On this page, I have a small introduction about myself, and a timeline with my imaginary and real work history. The basic structure of the timeline was written by Andrew R McHugh, you can find the source code [here](https://codepen.io/armthethinker/pen/nEtke).
 It was significantly modified.
- My portfolio page is a showcase of my recent work (also fiction). Under the card, you can see the name of the project, and for more information, you can click on the navigation button located beneath each of the cards.
-On the Get in touch page, you can contact me using a form. After typing your name and email address, you can choose the best option for scheduling the project, and you can also tell me about your ideas.
Your name and your valid email address are required.  

### Features Left to Implement

- In the future I plan to add further projects, work experience to make My portfolio and About me pages better. 
- On my Get in touch page, I would like to fix my form to work properly, so when I have enough knowledge for this, I will come back to this section, and I will make the submit button work. 

## Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML5)
- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Bootstrap](https://getbootstrap.com/)
- [HTML-Formatter](https://htmlformatter.com/)
- [HTML-Validator](https://validator.w3.org/)
- [CSS-Beautifyer](https://www.freeformatter.com/css-beautifier.html)
- [CSS-Validator](https://validator.w3.org/)
- [Autoprefixer](https://autoprefixer.github.io/)

# Testing

All links were manually tested, and all of them open in a new tab using target:"_blank" attribute.
The whole website is responsive using a different type of devices.

## Fixed issues

- My menu navigation bar (the last list items of it) created an overflow on my page, so I had a narrow white space on the right. After trying everything I could do it, I asked the Slack community about the reason of the overflow, they helped me out with it. The problem was with the Get in touch list item's bootstrap part, changing the col-sm to 2, it solved the problem.
- I've used px to set the height of my background image, which was nice on a small desktop screen, but it gave me a white space browsing from a phone, tablet, or wider screen. With this issue, one of the tutors helped me out: I changed the height to 100% and I've set a min-height. After that, I've realized that I have the same problem with my contact form, and I fixed it using the same method.

### Homepage

- When you open my portfolio website, you can see on each page the menu with Fontawesome icons. If you hover, the section changes the background to green. The same thing happens if you move your cursor to my portrait picture or any of the buttons.
- In the background, you can see a picture, which covers the whole page. 
- You can jump to Get In touch form (via I have and idea button), to About me page (via Tell me more success button) and you can also download my printable CV by clicking on Download my CV button.
- Below the success buttons, you can connect me on social media (Facebook and LinkedIn) or You can visit my GitHub repositories.



### About me

- In About me section you can see a textbox with a self-introduction.
- Under the introduction, it's a timeline with five different sections (icon, year, positions, a dividing line, and a description). 
- On About me, My portfolio and Get in touch pages, you can find a footer, where you can find two buttons: one leading you to my LinkedIn and one to my GitHub profile.

### My portfolio
 - My portfolio contains six cards showing my "recent projects". In the body of the card, you can see the name of the project, and by clicking on the  "More information" button, in a new tab will open the original page of the projects.
 - The footer section is the same as before.

### Get in touch!
 - The Get in touch page contains a contact form and the footer.
 - Before you submit the form, you have to type your name, and your valid email address, these sections are required.

# Deployment

My first website was written in GitPod, and it's hosted using Github, deployed from the master branch (via Settings). I've saved after every important change: starting with git status, git add ., git commit -m"" and in the end pushing the git to the Github repository.
After every commitment, when you refresh the repository, you can see the changes. 
If you want to clone the git because you would like to edit locally, you can type **git clone** plus the [link](https://github.com/krisztinatxt/first-milestone-project) to my git.

The main (landing) page of the website is named index.html. 


# Credits


## Content

- All the content were written by me. The timeline code was written by Andrew R McHugh.  

## Media

 - The portrait picture is my property. 
 - The background picture of the homepage is from [Pexels](https://www.pexels.com/photo/gray-laptop-computer-showing-html-codes-in-shallow-focus-photography-160107/). 
 - The photos used in this site were obtained from [Steam](https://store.steampowered.com/), [Prezi](http://prezi.com), [Arab Games](https://www.ar-gamez.com/planetbase/) and [Nintendo](https://www.nintendo.nl/Games/Nintendo-Switch-download-software/Machinarium-1464925.html).


 
## Acknowledgements
- The bootstrap codes are from the official website of the [Bootstrap](https://getbootstrap.com/).
- I've set the responsive breakpoint using [this](https://gist.github.com/EmranAhmed/8044351) template. 
- I've couldn't understand how to Bootstrap without [this video](https://www.youtube.com/watch?v=zDpCejbl1sU&amp;feature=youtu.be).
- I've learned how to center a form from [this article](https://stackoverflow.com/questions/20853066/how-to-center-form-in-bootstrap-3).
- To write this README I used this [template](https://github.com/Code-Institute-Solutions/readme-template) and this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
- I've learned a lot just browsing other sites using devtool, and reading the Slack. Thank you for the help to my mentor, the tutors and the Slack community. 



**This site is for educational use.**

***Krisztina Szabó***

***Code Institute*** 

***2019***