# Fantasy Premier League - Assistant Manager

Fantasy Premier League - Assistant Manager is the front end piece of what I hope to be able to build on in the future to provide a full set of tools to FPL (Fantasy Premier League) players in order to assist them to maximise their weekly points total to give them a significantly better chance of winning their mini-league and also push them up the global leaderboard. 

FPL - AM is designed to provide a central location FPL news and data so they can make the most informed picks for each gameweek. This is done in 3 main sections:

1. News: Provides the latest news that will affect player availability, injuries, suspensions, double gameweeks and also some analysis into top FPL Players

2. Form Center: A quick view into which FPL assets are currently the highest performing and therefore potential good picks for future gameweeks 

3. Feature: This is a currently undeveloped section where I plan in the future to build in backend integration with the FPL API in order to provide detailed analysis & predictions for FPL asset returns (scores) and price fluctuations


## UX & FEATURES

This website was designed specifically for Fantasy Premier League users, keeping this in mind I knew with an already large amount of resources available to these users I had to keep the design of the site simplistic and to the point as many similar sites can be instantly overlooked when information is too cluttered. 

My setup on this initially was to have a multi-page experience for the user, when each section (of current scrolling format) having its own page that would then have far more information, but upon trying to build it this way it became apparent that in order to fill out those pages more I would be using filler information that would distract from the core value of the site and thus work in line with what I said above regarding clutter.

Once I had switched the project to a single scrolling page I had to determine an efficient design that took inspiration from a number of FPL websites (sites in credits below). 

**Jumbotron:** To make the website name front and center and provide and instantly focus point where a call to action button to sign is used.

**Navbar:** Most modern websites appear to use some form of navbar a constant point of navigation reference, seemed appropriate to follow suit, especially for a single scrolling page.

**Social Media Bar:** Responsive bar that appears on the left for mid to large screens and docked to the bottom on small screens to allow for easily connecting with the pages hypothetical social media accounts

**Sections:** The three sections were specifically ordered as to no overwhelm the user with too much information initially, starting with a basic introductory news section, proceeding to more data-centric form center, and finally to the more complex features.

**Footer:** Generic footer design with some basic links, 2 dead (purely for visual purpose), and one to jump back to the top of the page.

**Font:** Exo/Roboto - used in a previous project and looked appropriate for this type of information/data based website.

**Modals:** There are two modals, one for signing up and one for signing in. both are access from each other as well as a button on the webpage, the reason for using modals for these functions was to keep them out of the way visually as the content of the site itself should be the core of the offering but to make them easily accessed if a user need/wanted to use them (i.e. launch without leaving the main page).

**Colour:** The main colour team of the site is Purple/Green/White, this was a conscious decision to keep the theme in line with the official Fantasy Premier League website and therefore potential creating a link of association in users minds between the two.

**Animations:**
* Scrollspy -  added to navbar to make it obvious which section of the page a user was on
* Hover - most hover animations on the page are color inversions (font color becomes background color and background color become font color), I did this as I felt it made the items for interaction very obvious. These animations are included in the navbar, buttons, social media bar & Sign up/Sign in modals. Another hover based animation used was shadowing with borders, this is used on the news section and help distinguish each article on hover.


### Features Left to Implement
- Another feature idea

## TECHNOLOGIES USED

### Languages
* [HTML](https://en.wikipedia.org/wiki/HTML)  - Struture of the page.
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Style of the page.

### Libraries
* [Bootstrap 4](https://getbootstrap.com/)
* [Font Awesome 4.7](https://fontawesome.com/v4.7.0/)

### Tools
* [Github](https://github.com/) - Repository Hosting.
* [Gitpod](https://www.gitpod.io/) - IDE.
* [Google Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools) - UX Testing.
* [W3C - HTML Validator](https://validator.w3.org/) - Validate HTML.
* [W3C - CSS Validator](https://jigsaw.w3.org/css-validator/) - Validate CSS.
* [PurifyCSS](https://purifycss.online/) - Remove unused CSS.
* [CSS-beautify](https://www.cleancss.com/css-beautify/) - Format CSS.
* [EzGif.com](https://ezgif.com/webp-to-png) - Convert Image to more useable formats.
* [Vecteezy.com](https://www.vecteezy.com/) - Images to fill site sections.

## TESTING

As a base building block I believe evidence of my testing is contained within my commits and commit comments, so along with that the below is generally what I have been testing and how.

1. Jumbotron:

2. Navbar:

3. Social Media bar:

4. News Section:

5. Form Center:

6. Features:

7. Footer:

8. Sign up / Sign In Modals:


In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## DEPLOYMENT

### Deploy to Github Pages

1. Open GitHub and go to the projects **'Repository'**
2. Click **'Settings'**
3. Scroll down to the **'GitHub Pages'** section
4. Click on the dropdown under **'Source'** and select the **'Master Branch'** option
5. A green box should appear with the following message **'Your site is published at.../'**


### Cloning a Repository 

1. Go to the main page of the GitHub repository and click on the dropdown menu **'Clone or download'**
2. Copy the URL and go to your local IDE (Integrated Development Environment)
3. In the terminal of your IDE type in **'git clone'** and the paste the URL copied from step 2 
4. Press **Enter** and the clone will be created


## CREDITS

### Media
- The photos used in this site were obtained from [Fantasy Premier League](https://fantasy.premierleague.com/) & [Vecteezy.com](https://www.vecteezy.com/) (See Fair Use Disclaimer)

### Acknowledgements

I received inspiration for this project from the below websites:

1. [Fantasy Premier League](https://fantasy.premierleague.com/)
2. [Fantasy Football Fix](https://www.fantasyfootballfix.com/)
3. [Fantasy Football Scout](https://www.fantasyfootballscout.co.uk/)

### Code Snips
Below links helped me in various parts of the project to overcome issues:
* https://bootsnipp.com/snippets/z8699
* https://www.w3schools.com/bootstrap/bootstrap_modal.asp
* https://www.codeply.com/go/qhaBrcWp3v
* https://www.w3schools.com/css/css3_gradients.asp
* https://stackoverflow.com/questions/6457406/can-i-apply-multiple-background-colors-with-css3
* https://stackoverflow.com/questions/486563/overflowhidden-dots-at-the-end/52195530
* https://stackoverflow.com/questions/21343659/bootstrap-3-horizontal-and-vertical-divider
* https://stackoverflow.com/questions/22162560/button-at-the-center-and-bottom-of-div
* https://stackoverflow.com/questions/2147303/how-can-i-send-an-inner-div-to-the-bottom-of-its-parent-div
* https://www.w3schools.com/cssref/func_calc.asp
* https://www.flaticon.com/free-icon/tactics_1286371?term=soccer%20tactics&page=1&position=25
* https://stackoverflow.com/questions/19528173/bootstrap-open-another-modal-in-modal

## FAIR USE DISCLAIMER
 - The images used in this project are not owned by me and I have not been given permission to use these, the purpose of their inclusion is purely for visuals within the project and the entire project is for nonprofit educational purposes. If this site was to ever go outside the remit of "nonprofit educational" then these images would be removed prior to such action.