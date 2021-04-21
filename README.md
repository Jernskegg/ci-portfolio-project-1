![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
***

## planning phase
* Purpose of the Project

   the purpose of the this project is to make a game developer website.
   this webpage is for a Fictional game developer to announce their games using the news feed and tell about them self
   it will also give the contact information about inquiries and available spot for future employees.

* User Stories

   As a game enthusiast, I want check on upcoming game so that the I know when to expect sthe game to be released and what to expect of the game.

   As a unemployed, I want find an available spot so that I can apply for work.

   As a journalist, I want to contact someone so that I can book for an interview.

* Features

   * Navigation bar
   * footer
   * news feeds with video
   * Subscribe to news
   * contact form on contact page

* Future Features

    * interactive news feed
    * Slideshow gallery

* Typography and Color Scheme

   This webpage is going to use "Roboto" for headers and "Lato" for paragraphs and smaller text, this is due to it's readability and it's also hosted on Googlefonts

   It is also going to some AwesomeFont for some visual and intuitive symbols

   the color scheme is gonna be neutral gray-scale with hints of orange to highlight 

* Wireframes

   ### Dekstop sized wireframes

   <img src="docs/wireframes/homedesktopsize.png" alt="wireframe for desktop sized home page" width="200">
   <img src="docs/wireframes/newsdesktopsize.png" alt="wireframe for desktop sized news page" width="200">
   <img src="docs/wireframes/contactdesktopsize.png" alt="wireframe for desktop sized contact page" width="200">

   ### Handheld sized wireframes

   <img src="docs/wireframes/homephonesize.png" alt="wireframe for handheld sized home" width="150">
   <img src="docs/wireframes/newsphonesize.png" alt="wireframe for handheld sized home" width="150">
   <img src="docs/wireframes/contactphonesize.png" alt="wireframe for handheld sized home" width="150">
***

## Deployement phase

* Technology
* testing
   * code validation
   * test cases (user story based with screenshots)
   * fixed bugs

      During deployment all external links worked, but all media and images did not.
      This was due to making the incorrect links such as **"/static/*"**.
      To resolve this issue I made sure to put correct pathways to resources.


   * supported screens and browsers

* Deployment
   * via gitpod
   * via github pages
* credits
### Issues



 ### Screenshots from deployed page

width 1080

<img src="docs/screenshots/shot-home-1080.png" alt="screenshot deskop home page" width="200">
<img src="docs/screenshots/shot-news-1080.png" alt="screenshot deskop news page" width="200">
<img src="docs/screenshots/shot-contact-1080.png" alt="screenshot deskop contact page" width="200">

width 720

<img src="docs/screenshots/shot-home-720.png" alt="screenshot handheld home page" width="150">
<img src="docs/screenshots/shot-news-720.png" alt="screenshot handheld news page" width="150">
<img src="docs/screenshots/shot-contact-720.png" alt="screenshot handheld contact page" width="150">

 

***

## Further maintainability

Template to add a new block to the news page

Add this to append to the "news.html" under section with the id "news-container"

      <article class="news-update">
            <img src="" alt="">
            <div>
                <h3></h3>
                <p>
                </p>
            </div>
        </article>
 

