# Iconic Car Meets

### Project Portfolio 1 - HTML/CSS Essentials

This is a website based on an imagined nationwide car meet, where people from all around the nation that own iconic cars, 
can meet up, have a chat and show off their cars. This websites main goal is to attract members of the public who are car enthusiasts, 
especially those who like iconic cars. The websites goal is to show users where spesific car meets will take place (iconic car meets) 
all around the country. The website does not sell tickets to the events however, the users can book a stand for their car on the website
using the 'Contact us' section of the page. There will be stand out images of some of the most iconic cars throughout the website and 
especially on our gallery page. We will have some pictures from our recent car meets and a schedule for when the next meets will take place. 
Also, within the header there is a 'Sign up' section, users can go here to become a member of Iconic car meets. There will also be a 'Contact us'
 section where users can contact us if they would like to have their car on a stand or on track. Users can also use this sections to ask any 
 further questions they may have.

## Demo 
Here you can find a demo of my website [here](https://mat2801.github.io/project1-Iconic-Car-Meet/)

# UX
I have chosen to base my project around iconic cars as they are a huge interest to me and something I can relate to easily. There 
is also a very large gap on the internet regarding car shows and locations. The primary focus of this website, is to allow full 
functional interaction with it's users to allow for a quick and easy user experience. 
My main goal was to create a interactive website to allow users to gain easy accessibility to information they require without
any hassle. I choose to use a simple layout using an attractive landing page image, to catch users attention. I opted for a colour scheme
of black and orange, the reason for this is I feel darker screens are easier on the eyes and also orange compliments the black to create 
a welcoming feeling. 

This websites users are interested in iconic cars and locations of iconic car meets. As well as to get a more information regarding the
car meets. The site owners goal is to provide a webpage that allows users to read a reliable source of information in regards to
iconic car meets e.g (location, time, date). 

- Home page - the user lands on this page and can see an image of a huge car show, with a small message which is linked to the location section.
- For users intrested in who organises these car meets they can read short information on the home page or can head to the about us page for 
  more information relating to rules at these car meets.
- If a user is intrested but unsure about anything involving the car meets there is an easily accesible contact us page. They can simply send 
  a question via filling in a short form. 
- Any user intrested in seeing updates and future car meets can sign up to the website by navigating to the sign up page. Again, by filling out a
  simple form. 
- The gallery page is where the user wants to go to see some of the previous meets and incredible iconic cars. 

### Clickable navigation on the home page
- A text box appears within the landing image, the 'Click here' text links directly to the times and locations.
- Social media links for Facebook, Twitter, Instagram and Youtube.

### User Stories
User001 - This user is on a laptop and has come to the website to find out, when and where the events for the next month are taking place.
User001 has visitied the Home Page and saw the message on the landing page, then clicked 'Click here' and it took them to the relevent 
place to find out more information about the upcoming events.

User002 - This user was using a mobile phone and came on the website as they wanted to place their car on a stand. The user also wanted to know 
the rules around the event. 
The user started on the home page and when reading through they saw the 'join the club' section which gave them instruction to be able to place 
their car on a stand. Following the instructions led them to the 'Contact us' page where they were able to contact us to get a place for their car. 
They then clicked the logo to go back to the home page and clicked the hamburger menu which showed them a section called 'About us'. Here they 
found all the rules surrounding the events. 

User003 - This user wanted to 'Join the club'. They were able to find how to do this when seeing the 
join the club section by scrolling down the home page. On the 'Join the Club' section the user will see to go to the 'sign up' page to 
become a member. To do this the user clicked the sign up navigation and filled in their details.
When typing in the email they missed off the @ but when clicking submit, the form let them know and they were able to Sign up successfully.

User004 - This user has visited the site to check out what cars they can find at the events. They clicked onto the navigation gallery option 
which took them straight to the gallery when they found the images from previous meets.

User005 - This user was already a member and wanted to follow the socail media accounts for the latest news and updates. By scrolling through
any page on the website the social media links could be easily found in the footer, once the user clicked the social media link it opened a new
tab and opened the relevant link.
 
# Features
- Event location and times.
- Gallery.
- Reliable information regarding car meets. 
- Images from previous car meets. 
- Contact us form
- Sign up form to join the club.
- Link to times and locations by clicking the icon at the top of the page 
- Use of a hamburger menu when on a mobile device.
- Social media links open in a new tab.

## Future Features
- Forum could be added to allow members to communicate with each other. 
- A larger gallery, which is broken down into individual events so users know what to expect.
- Memebership area could be added for paying members.
- Shop section where users can purchase merchandise. 
- Yearly events calendar where users can see events up to a year in advance.

```Wireframes and Mock write ups``` can be found [here](https://drive.google.com/drive/folders/1uIGPxjE4VvPzef1UZPZA6M2fdmo0NrP8?usp=sharing)

# Technologies Used
- w3s
- Developer mozilla
- Gitpod
- GitHub
- Funkypic 
- Unsplash
- HTML
- CSS

# Testing
- w3s Markup Validation service - All html code has been ran through via direct input and passed (screenshots here)
- w3s CSS Validation Service - All CSS code has been ran through via direct input and has passed (screenshots here)
- Chrome was used to create the website and works correctly only issue we have got is the home page video responsivness (check screenshots here)
- firefox (check screenshots here)
- edge (check screenshots here)
- user stories all tested and corretly working. (check screenshots here)

JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

# Bugs throughout creating this website
- Time and location tiles images wouldn't center. Fixed by manually resizing images and putting images into CSS instead of HTML.
- Step back on a commit due to messing up css code unsure what the issue was.
- Trying to fade images for location and time using rbga background colour but not working. Fixed using an overlay.
- Times and location images not lining up correctly, one is a little lower than all the rest. Fixed using padding
- Creating a burger menu and keeping text in a list. Fixed using visability as hidden and visible depending on active.
- Video centering - Still having issues, tried using positioning such as absolute.

# Deployment
1. Load up GitHub
2. Choose my project I want to deploy
3. Head over to settings
4. Now click on the Pages tab
5. There will be a drop down box with 'none' written in it. Click this and select Master branch
6. Now save and refresh your page and your website is hosted on github

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

# Credits
Text for about us section was copied from santapod raceway. (Text has been edited for my website purpose)
Youtube for the basic structure of my forms
Youtube for the basic hamburger menu 

# Media
- Personal images taken myself and edited using funkypic and windows editor.
- unsplash 

# Acknowledgements
I received inspiration for this project as I am a car enthusiast and I have attend many car shows. I thought this could be the beginning of a much 
bigger website where all car meets and shows could be placed online for everyone to see and attend also possibly book there tickets or purchase
tickets. 
