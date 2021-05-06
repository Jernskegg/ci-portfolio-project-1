![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Casper Hille

## Full-Stack Development course (5p) | Portfolio Project 1

# Purpose of the Project

   The purpose of this project is to make a game developer website.
   This webpage is for a Fictional game developer to announce their games using the news feed and tell about them self
   it will also give the contact information about inquiries and available spots for future employees.

# User Stories

   As a user, I want to check on upcoming games so that I know when to expect the game to be released and what to expect of the game.

   As a user, I want to find an available spot so that I can apply for work.

   As a user, I want to contact someone so that I can book for an interview.

# Features

   ### Fixed Navigation bar

   The page has a navigation bar that is sticky and will always stay on top of the page. 
   This is also where the user can select between four different options to navigate through the webpage.

   ### footer

   the page offers a footer containing social links.

   ### news feeds 

   The news page contains a news feed where the user would be able to see upcoming and old news.

   ### contact form on contact page

   The contact page contains a form where the user can input their user details and then send it using the button.

   ### application form on career page

   The career page contains a form where the user can input their user details and then send it using the button.

# Future Features

## interactive news feed

   Zoom-in feature when you hover your mouse over the specified news tile.
## Slideshow gallery

   A gallery to show of work

## subscription for news feed

   a form and a submit button where users opt-in for email updates of the news.

## add files to career application

   A file upload system so the user will be able to send a CV with the application for work.

## full 4k support
   add more features to suit a full 4k screen.

## Games section


# Typography and Color Scheme

   This webpage is going to use "Roboto" for headers and "Lato" for paragraphs and smaller text, this is due to its readability and it's also hosted on Google Fonts

   It is also going to some AwesomeFont for some visual and intuitive symbols

   the color scheme is gonna be neutral gray-scale with hints of orange to highlight 

# Wireframes

   ## Desktop sized wireframes

   [Home page](docs/wireframes/homedesktopsize.png)

   [News page](docs/wireframes/newsdesktopsize.png)

   [Contact page](docs/wireframes/contactdesktopsize.png)

   ## Handheld sized wireframes

   [Home page](docs/wireframes/homephonesize.png)

   [News page](docs/wireframes/newsphonesize.png)

   [Contact page](docs/wireframes/contactphonesize.png)

# Technology
## html
   Html was used to put structure to the web-page.
## css
   CSS is used to put color and form to the html files
## Gitpod
   Gitpod is the IDE that i've used to write the underlying code for the webpage.
   Why I chose this for ease of use and its connectability with github and due to it being used during the Code Institute's walkthrough project.
## AwesomeFont
   Awesome font is a script that allows developer to use special characters on the web-page. there is a wide range of variety and it as simple copy and pasting the link provided on their webpage.

## GoogleFonts
   GooleFonts is a cloud font service where the fonts are stored on Googles cloud service which grants the developer a wider range of fonts to use on the web-page and not having to rely on the user to have the font installed.
# testing
   ## code validation
   
   Code was validated using W3 html and JigSaw css validator without warning or errors.

   ## test cases (user story based with screenshots)
   
* ### As a user, I want to check on upcoming games so that I know when to expect the game to be released and what to expect of the game.

   I would load into the [home page(desktop)](docs/screenshots/shot-home-1080.png) or [home page(phone)](docs/screenshots/shot-home-720.png) and then I have to click on the news button in the navigation bar and there I will be able to get to the [news page(desktop)](docs/screenshots/shot-news-1080.png) or [news page(mobile)](docs/screenshots/shot-news-720.png) to see the news feed.

   [Image of where need to press](docs/screenshots/testcase-news.png)
      

* ### As a user, I want to find an available spot so that I can apply for work.
   
   
   I would load into the [home page(desktop)](docs/screenshots/shot-home-1080.png) or [home page(phone)](docs/screenshots/shot-home-720.png) and then I have to click on the career button in the navigation bar and there I will be able to get to the [career page(desktop)](docs/screenshots/shot-career-1080.png) or [career page(mobile)](docs/screenshots/shot-career-720.png) to see the work application form.
   Here I would be able to fill in all details to send.

   [Image of where need to press](docs/screenshots/testcase-career.png)

   [Image of where I need to fill im the form](docs/screenshots/testcase-career-form.png)

* ### As a user, I want to contact someone so that I can book for an interview.

   I would load into the [home page(desktop)](docs/screenshots/shot-home-1080.png) or [home page(phone)](docs/screenshots/shot-home-720.png) and then I have to click on the contact button in the navigation bar and there I will be able to get to the [career page(desktop)](docs/screenshots/shot-contact-1080.png) or [career page(mobile)](docs/screenshots/shot-contact-720.png) to see the contact form.
   Here I would be able to fill in all details to send.

   [Image of where need to press](docs/screenshots/testcase-contact.png)

   [image of where I need to fill im the form](docs/screenshots/testcase-contact-form.png)
   

## fixed bugs and issues found.
   1. During deployment all external links worked, but all media and images did not.
   his was due to making the incorrect links such as **"/static/*"**.
   To resolve this issue I made sure to put correct pathways to resources.

   2. Separated career and contact pages to make it easier to find the users goals.

   3. Added confirmation page for forms on career and Contact pages.

   4. added partial 4k support.

      add a big resolution hero image.
      Changed news columns from 3 to 4.
   
   5. Bug where on a galaxy s5 where the textarea causes the user to be able to scroll horizontally.

         implemented a Fix by removing the ability to resize the text area and having it resize using percentage and a min-width of 200px.
         (this bug is happend at a different user using chrome developer tools, Galaxy s5 emulater tool and I can't recreate it.)

   
   
   ## supported screens and browsers
   The page is designed to have a maximum of 1920x1080 screen support.

   4k resolution: hero image, news images fall out of proportions and form deforms

   desktop 1920x1080 to 1920x290. works as intended.

   The following devices have been tested on chrome developer tool emulator and worked as intended.
   * Galaxy Note II
   * Kindle Fire HDX
   * Pixel 2
   * iPhone 5/SE
   * iPhone 6/7/8 Plus
   * iPhone X
   * iPad pro
   * Surface Duo
   * Galaxy Fold

   The following devices have been tested on Firefox developer tool emulator and worked as intended.
   * galaxy S9
   * iPad
   * iPhone 6/7/8 Plus iOS 11
   * iPhone 6/7/8 iOS 11
   * iPhone X/XS iOS 12
   * Kindle Fire HDX Linux

   Microsoft Edge works as intended.

   Internet Explorer does not support the video on homepage and links open in Microsoft Edge.

# Deployment
   ## via gitpod
 
   To use gitpod you have to start a repository on Github. 
   from there if you have the gitpod plugin on your browser a green button stating "Gitpod" is available. that button redirects you to the GitPod IDE
   
   When it's done loading you will see down in the bottom a few tabs, when you press on terminal you will be able to input a command 
   
   to deploy your application through a http server you can write "Python3 -m http.server". this will open the http service and GitPod will give you a notification "A service is available on port 8000" with three buttons ( make public, open preview, open browser) so when you open your browser it will open the  index.html files, if that doesn't exist it will open the readme.md file instead.
 
   This is a good place to test your applications before pushing and deploying on github.

 
   ## via github pages
 
   To deploy a web page in github pages you need to go to your repository on github. there you will see a settings tab. Once you click that you will have a list on the left. scroll down to "pages and click it.
 
   there you will see a drop down menu and there you have to choose your branch of the project you want to deploy then you have to press save.
 
   Once saved you'll receive a notification on the same page with the link to your newly deployed site, although note that github pages can take a few minutes before it's fully deployed.
 
   When you have waited a few minutes you can click on the link provided and now you can test if everything works as intended. if not you have to update your files and push it again. Github pages will update the page for you and again, this might take a few minutes.

# credits

   Hero image: Image by [psychofladoodle](https://pixabay.com/users/psychofladoodle) from [Pixabay](https://pixabay.com)

   application screenshots were taken from actual products
   * [blender](https://www.blender.org/)
   * [krita](https://krita.org/)
   * [Audacity](https://www.audacityteam.org/)

   Font script was provided by [Font awesome](https://fontawesome.com/)

   Video was made by me using Blender.

# My personal achievements and what I feel I need to work on. 
   I wanted to learn to use the git commits and use it more often. I have realized I should write down all content that needs a fix or correction so I can have them on separate commits to make it more clear on what I have done between each commit.
 
   I have learnt how to plan and structure a web application more efficiently, it can still be greatly improved.
