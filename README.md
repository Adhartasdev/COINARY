# COINARY
The Online Fintech Payment Glossary

# COINARY - Milestone 3 Project

[Live link](INSERT LINK)

[GitHub Repository](INSTERT GITHUB REPO LINK)

Coinary is a community driven site that collects and stores definitions for the fintech/payment industry. The site allows fintech professionals to store and easily access definitions for terms in the Fintech industry. The final mission/goal of this initiative is to publish an official list of definitions in the fintech industry through an upvoting system. 
The site is built using HTML, CSS, Python, Flask and MongoDB. 

# Table of contents
1. [UX](#UX)
    1. [First Time Visitor Goals](#firsttime)
    2. [Returning Visitor Goals](#returning)
2. [Design](#design)
    1. [Colour Scheme](#colour)
    2. [Typography](#typo)
    3. [Layout](#layout)
    4. [Wireframes](#wireframes)
    5. [Database Schema](#schema)
3. [Features](#features)
    1. [Current Features](#current)
    2. [Future Features](#future)
4. [Technologies Used](#tech)
5. [Testing](#testing)
    1. [Manual Testing](#manual)
    2. [Automatic Testing](#auto)
    3. [Bugs](#bugs)
    4. [Known Issues](#issues)
6. [Deployment](#deployment)
    1. [Deployment Heroku](#heroku)
7. [Credits](#credits)

## UX <a name="UX"></a>

When it comes to UX, the first goal has been to create a good and modern looking site that rises to the standard of the industry. The importance during the development is to provide a clean and zen aspect, whilst maintaining the cold blueish finance/fintech look. The site is presented in a way that engages anyone from junior enthousiasts to senior bankers in using and sharing knowledge on terminology.

### First Time Visitor Goals: <a name="firsttime"></a>
- As a new visitor, I need to be able to clearly undestand the purpose, goal and functionalities of the site.  
- As a new visitor I want to be able to see boradly accepted definitions by the industry with correct descriptions
- I want to be able to search for a term
- I want to be able to see the top 10 definitions


### Returning Visitor Goals: <a name="returning"></a>
- I want to be able to enter my own fintech term through my account
- I want to be able to upvote or downvote a user-given definition
- I want to edit my definition should I need to

## Design: <a name="design"></a>

### Colour Scheme: <a name="colour"></a>
![](/workspace/COINARY/Assets/Images/COINARY.001.png)
- See above the primary site colours. These allow for a techy feeling based on dark blue and white. It provides a focused view ot users in a "cool" environment. 
- The pallet choice has been made based on a company I have worked with: https://apexx.global/

### Typography: <a name="typo"></a>
- I have decided to use two fonts that alternate through the sit. Lato and Roboto. 

### Layout: <a name="layout"></a>
- The site is laid out much like a search engine and lexicon. 
- To present the content of the site, I have used flask, along with flask forms for all forms on the COINARY site.

### Wireframes: <a name="wireframes"></a>

- Find below the different wireframes for the site. These are the initial designs and will vary a bit from the live deployments. 
![](static/images/wireframe.png)

### Database Schema: <a name="schema"></a>

There are 3 collections in the database titled "KeyTerms", "TermRating" and "Users". 

#### KeyTerms:
    KeyTerms: string
    path: string
    KeyTerm_definition: string

#### TermRating:
    KeyTerms_name: string
    author: string
    rating: integer
    reason_text: string

#### Users:
    username: string
    email: string
    password: string
    admin: boolean


## Features <a name="features"></a>

### Current Features <a name="current"></a>
- comment
- comment
- comment 5 more
- Search Function
 

### Future Features <a name="future"></a>


## Technologies Used <a name="tech"></a>

1. [HTML:](https://www.w3.org/html/)
    - HTML was used for structuring and showing the content. 
1. [CSS:](https://www.w3.org/Style/CSS/)
    - CSS and in particular powered by bootstrap 5 was used to style the website to the liking of the user.
1. [Python:](https://www.python.org/)
    - All backend was developed using Python.
1. [Heroku:](https://www.heroku.com/)
    - I used Heroku for the live environment deployment, hosting and testing of the site. was used to host the site and test it in a live environment.
1. [MongoDB:](https://www.mongodb.com/)
    - Database service for the site.
1. [Balsamiq:](https://balsamiq.com/)
    - The Balsamiq free trial was used to create the wireframes seen above.   
1. [Gitpod:](https://www.gitpod.io/)
    - Gitpod was the IDE used for the site developement
1. [Bootstrap 5:](https://getbootstrap.com/)
    - Bootstrap was used for the styling of the website and the rapid development of the front end. The basic design was a great help for the rapid design. 
1. [Font Awesome:](https://fontawesome.com/)
    - Used for all icons seen on the site. 
1. [Flask:](https://flask.palletsprojects.com/en/1.1.x/)
    - Flask was used as a structure fundamental for the site.
1. [Git](https://git-scm.com/)
    - Git was the version control to commit and push to Github.
1. [GitHub:](https://github.com/)





## Testing <a name="testing"></a>

Find below the testing procedures that were performed for the project. 

### Manual Testing: <a name="manual"></a>


My manual testing process was as follows:

#### For each page I performed the following checks:
    * Desktop and mobile
        - comment 
        - comment
       
    * Mobile only        
        - commment   

   

      
### Bugs: <a name="bugs"></a>

#### Bug 1:

### Known issues: <a name="issues"></a>

### Automatic Testing: <a name="auto"></a>

[W3C Validator HTML result](assets/readme/w3chtml.png) 

[W3C Validator CSS result](assets/readme/w3ccss.png) 


## Deployment <a name="deployment"></a>

### Deployment Heroku: <a name="heroku"></a>



## Credits <a name="credits"></a>
-