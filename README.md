[The Bookshelf](https://the-bookshelf-milestone.herokuapp.com/) was designed, built, and deployed, by myself, Michelle Newell as the 
third project for the Code Institute Full Stack Web Development diploma. The purpose of The Bookshelf is to be an online book club 
that allows members to view The Bookshelf’s monthly recommendations, as well as provide and share book recommendations of the users 
own liking. The website is designed to share literary experiences, specifically for those looking for book suggestions and wanting to 
share their own books that they have read and enjoyed. 

## Table of Contents
1. [UX](#ux)
    - [Goals](#goals)
        - [Visitor Goals](#visitor-goals)
        - [Site Owner Goals](#site-owner-goals)
    - [User Stories](#user-stories)
    - [Design Choices](#design-choices)
    - [Wireframes](#wireframes)

2. [Features](#features)
    - [Existing Features](#existing-features)
        - [Elements on every page](#elements-on-every-page)
        - [Who we are](#who-we-are)
	    - [Login](#log-in)
	    - [Register](#register)
        - [Club picks](#club-picks)
        - [Your picks](#your-picks)
        - [Add book](#add-book)
   	    - [Log out](#log-out)
    - [Features for Future Releases](#features-for-future-releases)

3. [Information Arcitecture](#information-architecture)
	- [Database choice](#data-models)
	- [Data models](#data-models)


3. [Technologies Used](#technologies-used)
    - [Tools](#tools)
    - [Libraries](#libraries)
    - [Languages](#languages)

5. [Testing](#testing)
    - See seperate [TESTING.md](https://github.com/PillowFishSticks/My-Resume/blob/master/TESTING.md) file.

6. [Deployment](#deployment)
- [How to run this project locally](#how-to-run-this-project-locally)
- [Heroku Deployment](#heroku-deployment)
 
7. [Credits](#credits)
- [Content](#content)
    - [Images](#images)
    - [Code](#code)
    - [Acknowledgements](#acknowledgements)

----

# UX

## Goals

### Visitor Goals

The target audience for the resume website are:
- People who enjoy reading. 
- People who are interested in joining an online book club.
- People who want to share good books they read. 
- People looking for book recommendations. 

User goals are:
- To join an online book club. 
- Find new reading material via the book club. 
- Share books that I have enjoyed with other book club members. 
- Share reviews about the books I have read. 
- To be able to add, edit, and delete books on the website. 
- Be able to navigate the website easily and view detailed information on books. 

### The Bookshelf’s Goals

The goals of The Bookshelf are:
- Provide a platform where users can find book recommendations via the book club and its members. 
- For book club members to be able to add, edit, and delete books that they would like to share. 
- Provide a platform for book club members to share reviews about the books they would like to add. 
- For book club members to be able to view books in detail, including a purchase link. 

## User Stories

As a visitor to The Bookshelf website I expect/want/need:

1. To be able to easily find the information I am looking for, the layout needs to make sense so that I am not put off. 

2. The site to be laid out in a way that is easy to navigate, so that I can find what I need. 

3. The site to be responsive and navigable for various device sizes; desktop, tablet, and phone. For the content to look good 
   on all of the devices.

4. To learn more about The Bookshelf. 

5. To be able to connect to The Bookshelf’s social media accounts. 

6. To be able to click on books for further information about them. 

7. A purchase link to be provided for each book, in the event that I would like to buy it. 

8. To be able to add, edit, and delete books that I would like to share with others. 

9. To be able to write reviews about the books I would like to share. 

10. To be able to log in and out with ease. 

11. To be notified that I have logged in or out of my account. 

12. To be notified about changes that are made, inlcluding adding, editing, and deleting books. 

## Design Choices

The Bookshelf has a fun feel to it, with emphasis on displaying books in an easy to read manner. The following design choices were 
made bearing this in mind:

### Fonts
- The primary font 'Roboto' was chosen to be the main text of this site as it is easy to read, looks professional, and goes well 
  with the secondary font. 

- The secondary font 'Rocknroll One' was chosen for the headings as it looks fun, and is easy to read. 

### Icons
- Very few icons were used, as to avoid overcrowding. 
- The following icons were used in [Add book]() page to emphasize each sections purpose:        
   - The **book** icon was placed next to 'Title'. 
   - The **user** icon was placed next to 'Author'.
   - The **file image** icon was placed next to 'Image URL'. 
   - The **credit card** icon was placed next to 'Amazon store URL'. 
   - The **comment** icon was placed next to 'Synopsis'. 
   - The **pencil** icon was placed next to 'Your review'. 
- The **Facebook logo** icon, **Instagram logo** icon, **Twitter logo** icon, are included in the footer to lead visitors to The 
  Bookshelf's social media accounts.

### Colours
- Yellow: #ffff66
- Orange: #ffcc99
- Light blue: #87cefa
- Light grey: #87cefa

- The bright orange and yellow were chosen for the navbar and footer as they provide a fun, happy feel to the website. No other bright 
  colours were used as the book covers provide an array of different colours. The light gray was chosen for the 'Donate Books' section
  as it goes well with the bright colours, but provides a subtle colour to a page filled with bright colours. The light blue was chosen
  to highlight monthly and user picks in the modals. 

## Wireframes

These wireframes were created using [Balsamiq](https://balsamiq.com/) during the design and planning process for this project. 

- [Who we are](/static/images/wireframes/wireframe-who-we-are.png)
- [Log in](/static/images/wireframes/wireframe-log-in.png)
- [Register](/static/images/wireframes/wireframe-register.png)
- [Club picks](/static/images/wireframes/wireframe-club-picks.png)
- [Your picks](/static/images/wireframes/wireframe-your-picks.png)
- [Add book](/static/images/wireframes/wireframe-add-book.png)
- [Log out](/static/images/wireframes/wireframe-log-out.png)

# Features
 
## Existing Features

### Elements on every page

#### Navbar

![Navbar](/static/images/navbar.png)

- The navbar features on every page. It is bright, with a mixture of two colours, creating an ombre effect. 

- **In desktop view**  The navigation bar features the website name ‘The’ Bookshelf' on the far left, and website pages on the far right.
  
- A user who is logged in will see the options of Who we are, Club picks, Your picks, Add book, and Log out. 

- A user or visitor who is not logged in will see the options of Who we are, Log in, and Register. 

- **In tablet and mobile view** 

#### Footer

![Footer](/static/images/footer.png)

- The footer features on every page. It is deliberatly large and bright to attract visitors to sign up and become members and/or visit 
  The Bookshelf's social media pages. 

- The footer includes a tag line 'Not a Bookshelf member? Sign up here' with a clickable link that takes the user to the register page. 
  This is located on the left hand side of the footer.  

- The footer features links to The Bookshelf's social media accounts for Facebook, Instagram, and Twitter. These icons are located
  on the right hand side of the footer. 

### Who we are

**About The Bookshelf**

![About The Bookshelf](/static/images/who-we-are.png)

- 'Who we are' includes a section about The Bookshelf. This includes a short blurb about The Bookshelf, the founder, and some of the
  different features it includes. 

- The blurb is positioned on the left hand side. 

- An image of the founder is located on the right hand side, shaped in an oval. 

- The blurb and image are encompassed in the same colour as the navbar. This creates a uniform background, blending the navbar with 
  the blurb and image. 

**Why The Bookshelf?**

![Why The Bookshelf?](/static/images/why-the-bookshelf.png)

- This section is located in the middle of the 'Who we are' page. It includes six blocks with verious shapes and colours. Each block 
  includes a unique shape with some information about The Bookshelf. 

- This section is used to create a fun way of telling visitors more about The Bookshelf. Short sentences make it easy for visitors
  to gain knowledge about the website, without having to read long paragraphs. 
  

**Donate Books**

![Donate Books](/static/images/donate-books.png)

### Log in

### Register


### Club picks

![Clubs picks](/assets/img/resume-website/resume.png)

**Modals**
- 

### Your picks

![Your picks](/assets/img/resume-website/project.png)

- 

**Modals**

### Add book

- 

### Log out

- 

## Features for Future Releases

1. **Chatbox for potential clients**
    - Having a chatbox on the Contact page, that allows people to chat with you and leave you messages. 
2. **More projects added to the project page**
    - Once more projects have been completed, adding those to the Projects page.
    - Each project having a link to the live project. 
3. **Review page for clients to add reviews**
    - A review page that allows previous clients to add review about the work done for them and how satisfied they are with the final product. 
    - Possibly a star rating. 
