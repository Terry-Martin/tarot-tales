# Tarot Tales
(adapted from Love Running tutorial readme)


This site is designed to give users an overview of the services provided by Tarot Tales. We offer both in person and online readings with experienced and friendly staff members. There is a bookings page to contact us directly and make an appointment

  - ![Responsive pic](assets/images/readme/responsive.jpg)

## Design




## Features

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Home page, Tarot Cards page and Booking page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](assets/images/readme/tarot-top-menu.jpg)


- __Weclcome Message__

  - Featured on the index/home page, this is the first info that will draw the eye of the user. It gives a short description of the site and tarot cards, themselves

![Welcome message](assets/images/readme/tarot-welcome.jpg)

- __Services Provided__

  - Featured on the index/home page, this sets out the services on offer, the types of readings and the price.

![Services provided](assets/images/readme/tarot-services.jpg)


- __Tarot Cards__

  - Featured on the Cards page, the first 10 cards of the major Arcana are displayed as pics - starting with The Fool.

![Tarot cards](assets/images/readme/tarot-cards.jpg)

- __Booking Form__

  - Featured on the Booking page, users can submit a form to request a booking. Name, Email, Phone, Date, Time and Reading Type information is captured here. There is also a text area to allow the user to supply any other information that they think is relevant.

![Booking Form](assets/images/readme/tarot-booking.jpg)


- __Footer__

  - Featured on all three pages, the footer includes links and logos to four social media platforms - YouTube, X, Facebook and TikTok.

![Footer with Social Media Links](assets/images/readme/tarot-footer-menu.jpg)


### Features Left to Implement

- Some of the next features to add would include testimonial videos from existing customers and more interactive booking system to display availability of each reader.


## Testing 

- All the links in the nav bar work correctly from each page of the site. 
- The social media links in the footer open to the correct page and in seperate browser.
- For the bookings page, validation is in place after the user presses the "Book a Reading" button to check that al required fields are populated and in the correct format (in the case of Email). A prompt is displayed to to user next to the field that needs attention.
- As this website is a course project, the user information is saved to any database but a Code Institute confirmation page is displayed to confirm the user info was captured. 

Media Queries are used to display on different screen sizes. Different back ground image is used for mobile than tablet or above. Also, the burger menu is used for mobile view with standard nav bar used for other screens. These were tested using the Responsive feature within Chrome DevTools.

Section tags need to have a H2 to H6 tag inside them. This was highlight in HTMl Validator.


Last minute bugs that delayed submission were incorrect paths for image files (for both the site itself and for ReadMe file).
The quality of images on large screens was another issued that needed to be corrected. 


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 