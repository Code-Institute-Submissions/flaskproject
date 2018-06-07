# You Sell Cars Website
 
## Overview
 
### What is this website for?

This website aims to facilitate the buying and selling of cars by showing the cars available for sale by the respective owners while at the same time facilitate the sale of the car to the owner by filling in a simple form

### What does it do?

This website shows ads of cars that the car owners have posted. You are able to browse the ads which display vital car information along side the owner's contact details in order to aproach the owner. 
 
### How does it work

The site is styled with **Bootstrap**. The website uses the **python** language and the **Flask** framework in order to render the data created and then used. Information given by the user when filling in the form and subsequently displayed is stored in and accessed from a mongo database. Deployment of the app has been actioned through Heroku. The site can be viewed [HERE](https://futoisaru.github.io/hippo/). 

## Features
 
### Existing Features
- Eye catching front page with no clutter
  - Sliding picture box
- Information page.
  - Sidebar to navigate to different parts of the information
- Media page with plenty of pictures and a video
- Links page to other sites with information about Hippopotami
- Quiz page for viewers to test their knowledge
    - Form for viewers to input their answers or check the correct box
    - Submit button so viewers can see how they scored on the quiz

### Features Left to Implement
- None

## Tech Used

### Some the tech used includes:
- **HTML**, **CSS** and **Javascript**
  - Base languages used to create website
- [AngularJS](https://angularjs.org/)
    - We use **AngularJS** to handle page routing and to build custom directives
- [Bootstrap](http://getbootstrap.com/)
    - We use **Bootstrap** to give our project a simple, responsive layout
- [JQuery](https://jquery.com)
    - Use **JQuery** for boostrap and displaying modal

## Testing
- Prototype code was written and tested using jasmine
- All code used on the site has been tested to ensure everything is working as expected
- Site viewed and tested in the following browsers:
  - Google Chrome
  - Opera
  - Microsoft Edge
  - Mozilla Firefox

## Contributing
 
### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. After you've that you'll need to make sure that you have **npm** installed
  1. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
4. After those dependencies have been installed you'll need to make sure that you have **http-server** installed. You can install this by running the following: ```npm install -g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server -c-1```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request

## Credits

### Media
- The photos used in this site were obtained from [Pixabay](https://pixabay.com/)
- The video used on this site belongs to Nat Geo Wild channel on [youtube](https://www.youtube.com/watch?v=WfrG95GyU9U)

### Information
- The information used to create this site was from a number of sources
    - Wikipedia webpage on [Hippos](https://en.wikipedia.org/wiki/Hippopotamus) and [Pygmy Hippos](https://en.wikipedia.org/wiki/Pygmy_hippopotamus)
    - The African Wildlife Foundation [website](http://www.awf.org/wildlife-conservation/hippopotamus)