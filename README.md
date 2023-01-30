# Vibrant Cuts

Welcome to website for Vibrant Cuts! My goal is to provide a convenient and user-friendly platform for customers to view the salons services and gallery, and to strengthen the specialisation they have in hair coloring. This website is designed to be accessible to all, with an intuitive layout and easy navigation.

With the website, you can easily view Vibrant Cuts range of hair services, read about their experience, and get contact information so you can book your next appointment with just a few clicks. The gallery showcases their talented team's work and the variety of styles they offer. 

## Features
*** 

### Existing features

#### Navigation bar

- The navigation bar of the salon website is designed to provide a seamless user experience for our customers 
- The navigation bar is fixed at the top to always be easily accessible and will let us skip having a "back-buttong"
- It´s fully responsive and includes the links to Logo, Home page, Prices, Gallery and Contact page. 

![Navigation bar for Vibrant Cuts webpage](/assets/images/readme/nav.jpg)

#### Home

##### Landing page section

- The landing page has a background image with a very vibrant color pink to not only catch the eye, but to also directly show the viewer the salons strength - hair coloring. 
- text overlay with statement to show exactly what this webpage is about.  
- We can see that we have more information below directy on landing page to make people scroll down. 

![landing page for Vibrant Cuts](/assets/images/readme/landingpage.jpg)

##### What we do section

- When scrolled down to the next section we see 3 images and short text about the services that Vibrant Cuts offer. 

![What we do section](/assets/images/readme/landingpage2_what-we-do.jpg)

##### Life is too short section

- Here we place another eye catching image with a strong statement to encourage the viewer to contact the salon. This message is placed together with with the footer 
-  On top of the page still have the fixed header with links. 

![Last section of Home page](/assets/images/readme/landingpage3_life.jpg)

#### Footer

- Gives quick information of the phone number and social media links.

![Footer](/assets/images/readme/footer.jpg)

#### Prices

-  Outlines the various hair and beauty services offered by the salon and the price range the client can expect.

![Prices page](/assets/images/readme/prices.jpg)

#### Gallery

- Showcases the salon's portfolio in a scrollable page. 

![Gallery page](/assets/images/readme/gallery.jpg)
![Gallery page scrolled down a bit](/assets/images/readme/gallery2.jpg)

#### Contact 
- Allows customers to easily get in touch with the salon and make appointments or fill in the form to get contacted by the salon. 

![Contact page](/assets/images/readme/contact.jpg)

### Features left to implement

#### Home page

- Section "What we do" should be linked to information pages about the services. 

#### Contact page

- Booking system.

## Testing
***

### Functionality Testing

The webiste is tested in Chrome and Firefox on a PC. On phones/tablets I have tested both iOS and Android. 

All internal links are ok. 
All external links work ok and open in a new browser. 
Form in Contact page is working ok and will demand name, lname and email to be able to submit.

#### Bugs

- When deployed none of the images in the gallery is working in any screen or system. It workes fine in Gitpod, but not when deployed to Github. 
- Pink background image and white overlay text at the bottom om Home page is not showing in iOS.
- Hero image a bit large (height) on table and mobile.
- Background image 2 furthest down at Home page is a bit large (height) on table and mobile.

#### Fixed bugs

- What we do section on Home page not responsive. <br>
*I re-made the whole section and put the content in a flexbox to have a better control over it*

- Text under images in What we do section on Home page is not placed under the associated image. <br>
*I restructured the content and used a flexbox nested in a flexbox to get control over the text and its placements with the associated image* 

- Pricelist needs to be centered on smaller screens. <br>
*Fixed with media query*

- Checkboxes in form at Contact page seem to have a strange padding on the left side that pushes it out of the actual form. <br>
*I re-structured the form with flexbox instead and got better control over the checkboxes. Now they are a tiny bit indented which I want since it seperates the checkboxes a bit from the rest of the form. I also removed the checkbox "Other" and instead added a text area below so user can put in more information if wanted.*

- Footer not responsive <br>
*I re-structured the footer and used a flexbox to get better control*

- White overlay text at the bottom om Home page is not showing in iOS.
*Added background color pink to show when image is not working.*

### Validator testing

#### HTML

All pages tested with the offical [W3 Validator](https://validator.w3.org/nu/).

#### CSS

Checked with [W3 Validator](https://validator.w3.org/nu/)



## Deployment
***

The site was deployed to Github pages. The steps where:
1. In the github repositary, navigate to Setting tab
2. Navigate to Pages on the left
3. Select Master Branch in the source section drop down list. 
4. The page will automatically be updated and give you a link where you also have the information with the latest deployment. 

The link is: https://sandrabergstrom.github.io/PP1/

## Credits
***

I would like to extend my gratitude to Code Institute for providing me with the education and resources needed to develop my skills in HTML and CSS. Their lessons have been instrumental in helping me understand the fundamentals of web development.

Special thanks to my mentor at Code Institute, who encouraged me to dive deeper into flexbox and its capabilities. Their guidance has allowed me to bring my projects to the next level and has been invaluable in my growth as a web developer.

Thank you, Code Institute and my mentor, for all your support and guidance!

### Content

The text for the webpage was written together with [ChatGPT](https://chat.openai.com/)

Instructuions and help about flexbox I have gotten from [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) and [W3 Schools](https://www.w3schools.com/css/css3_flexbox.asp)

Instructions and help about form I have gotten from [W3 Schools](https://www.w3schools.com/css/css_form.asp)

Icons in the footer is from [Fontawesome](https://fontawesome.com/)

Fonts is taken from [Google Fonts](https://fonts.google.com/)

### Media

The photos used throughout the webpage is coming from [Unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/)

## UX
***

The idea from the beginning was to create a very minimal webpage but with strong vivid colors as a contrast. This desicion was made because of several reasons:
- To mirror the salons interior and it´s brand. They have a very light, clean and minimal interior design since they want to create a bit of a clinical feeling rather than the hairdresser down the street. 
- To enhance their strengt in hair color. 
- The salon is known for being THE salon when it comes to pink hair color and therefore the desicion of pink as a contrast color was made. 

