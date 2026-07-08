# Restuarant Dashboard Project
<hr>
I built this project as i wanted to create a dashboard that had real world value for my current job. Working in a small farm shop kitchen, where the owners are loathe to embrace technology and rely heavily on pen and paper alternatives. This often leads to things being missed, paperwork being damaged or misplaced and zero accountability across the wider team. 

In addition the wider goal was to go back to my original motivation for persuing this in the first place, and that was as a vehicle to transition from the kitchen pass to a career in software development. My self imposed barrier i found was always struggling with hypothetical mini projects that while were meant to teach coding fundamentals, had no real world value for me, so this led to an overactive case of impostor syndrome. 

This is were this dashboard was borne from. Drawing on my battle tested experience in various venues, using a multitude of platforms that all had small parts of the systems required to run a busy kitchen.

## Goal
To build an interactive dashboard that can be accessed using either a mobile device, whether a phone or tablet or via a traditional desktop. A system that incorporates all the main aspects required to operate a modern food business at a high level. I want to build tabs for checklists which include daily, weekly and monthly cleaning tasks. Fridge temperature records, delivery logs, probe calibration records, raise maintenance issues and eventually work in a time and attendance module. I want to include a feature for stock control, orders & goods recieving. I want to have authentication, to identify the user so as to create accountability. I want to build in a reporting module so that everythng can be sent to a report/output that could either be printed for record keeping or emailed through to the owners for traceability.

I approached this project with mobile first design principles to create a responsive webpage that is intended to look good and and perform well on any size of device. I have also put good user experience at the front and center of all designs and have strived to create an intuitive, informative and enjoyable journey for my users.

## User Stories

* I identified 2 groups of user for this site, firstly, users that are new to kitchens and need an all-in-one solution to help record temps, control stock, create accountability for tasks and see all issues in an easy to access, simple one page view. Secondly, existing chefs, resturanteurs who are looking to dive deeper and gain a better understanding of their operation, have an EHO ready solution that can be implemented in a small single unit or across mulitple units.
    * ### New Users
        * Should be able to quickly gain an overview of what the app is about via the Dashboard landing page.
        * Should be able to access checklists, assign tasks, record deliveries, probe calibrations and fridge temps on the Checklist page.
        * Should be able to monitor and manage their current stock levels are via the Stock Control page
        * Should be able to create and track order on the Orders page
        * Should be able to get detailed information on rotas and schedules on the Time & Attendance page
        * Should be able to generate a report based off the information entered in all the various pages.
        <hr>
    * ### Existing Users
        * Should be able to do all the above.
        * Should be able to create users and set access permissions according to their level of seniority within the unit.
        * Should be able to assign shifts and breaks on the rota.
        * Should be able to validate leave assign holidays accordingly.
        <hr>
* From the above information I was able to determine what would be of considerable value when visiting the site and from that developed the following scope and goals:       

Restuarant Dashboard is an online portal offering an operations management system suited to the hospitality business. Specific goals for the business are to offer a platfrom that will allow users to monitor their operation at a glance through:
* A Dashboard overview listing the main issues and alerts in one concise page view
* A Checklist page, a page to manage all cleaning tasks, temperature checks and maintenance issues
* A Stock control page, a page to monitor and manage inventory
* An Orders page, a page to create and track supplier orders
* A Reports page, a place to generate and export operational reports
* _future goals are a Time & Attendance module to generate rotas, manage leave and shift patterns, an admin page to generate user information so as to be able to track who is accessing the site and what their access rights are_

The Dashboard will be useful to users looking to get away from pen and paper solutions, and combine all those various sytems within a kitchen, on a single platform. They will be able to see at a glance what is going on within their unit. Be able to stay on top of the various cleaning tasks and temperature recording as required by law, and create accountability through their unit.

Yoga Republic will be useful to users looking to find a specific yoga style suited to their fitness/ability level. Get detailed information on the various styles of yoga on offer and the teachers who lead the classes. See exactly when and where they need to be in order to join a class. Have access to an online form if they would like to be contacted directly by someone from the studio.

## Features

### Existing Features

* #### Header
    * This is the first section and contains the **Restuarant Dashboard** heading and the navigation elements.
    * This section introduces the user to Retuarant Dashboard with a welcoming message introducing them to the main aim of the site.
    * ![Home Page](/assets/images/readme-img/landing-page.png)
    <p>&nbsp;</p>
    <hr>

* #### Navigation Bar
    * The navigation bar consists of 6 links that run down the left hand side of the page, namely **Dashboard*, **Checklists**, **Stock Control**, **Orders**, **Reports** and **Time & Attendance**.
    * The **Dashboard** link directs the user to top of the *Dashboard Overview*.
    * The **Checklist** link directs the user to the *Checklists*. This opens a new page that utilizing a tabs system to navigate between the *Daily*, *Weekly*, and *Monthly* cleaning chekcs. It also has tabs for *Temps*, *Delivery* and *Probes* and finally *Maintenance*. The setup of the tabs sytem allows user to focus on each tab independantly without being overwhelmed with too much information.
    
    * ![Navigation bar](/assets/images/readme-img/nav-bar.png)
    * A further design element of the navbar is that it scrolls with the user as they navigate from the top down through a page, giving the user the flexibility to move on through the site without having to scroll back to the top.
    <p>&nbsp;</p>

    *  One of the key factors with the site is responsive design, and with the navbar this is carried through in the way in which it behaves on smaller screens, with it taking up 100% width and stacking for easier readability and an improved user experience that doesn't detract the focus away from the site.
    * ![Responsive Navigation](/assets/images/readme-img/nav-bar-responsive.png)
    <p>&nbsp;</p>
    <hr>

* #### Home Page
    
    <p>&nbsp</p>
    <hr>

* #### Dashboard Page
    * ![Dashboard page](/assets/images/readme-img/about-us-page.png)
    
    <p>&nbsp;</p>
    <hr>

* #### Checklists Page
    
    * ![Daily](/assets/images/readme-img/yoga-page.png)
    * ![Weekly](/assets/images/readme-img/yoga-flip-cards.png)
    * ![Monthly](/assets/images/readme-img/timetable.png)
    * ![Temps](/assets/images/readme-img/timetable.png)
    * ![Delivery](/assets/images/readme-img/timetable.png)
    * ![Probes](/assets/images/readme-img/timetable-responsive.png)
    * ![Maintenance](/assets/images/readme-img/timetable.png)
    <p>&nbsp;</p>
    <hr>

* #### Stock Control Page
    
    <p>&nbsp;</p>
    <hr>

* #### Orders Page
    
    <p>&nbsp;</p>
    <hr>

* #### Time & Attendance Page
    
    <p>&nbsp;</p>
    <hr>

* #### Reports Page
    
    <p>&nbsp;</p>
    <hr>

* #### Footer
    * The footer container social media links that open a new browser window to the studio's Facebook, Twitter and Instagram pages. There is also a floating "up" arrow to take users back to the top of the page without having to scroll up manually. The arrow was designed to incorporate the YR logo so as to help build brand awareness with the user as they navigate through the site, on a more subconscious level.
    * ![Footer](/assets/images/readme-img/footer.png)
    <hr>
<p>&nbsp;</p>

### Future Updates
* The use of an **User Admin Page** to help control site access, accountability across the various tasks, limit access to higher sections of the business' information. 
* The addition of an interactive calender to be able to book leave requests, check employee availablity at any given time.
* The addition of a blog section, to interact more actively with the community.

<hr>
<p>&nbsp;</p>

## Testing 1.0


My first round of testing was functionality testing in which I performed the following actions.
### Testing the Links
 * Checking the External Links
 * Checking the External Links all Open in the new Tab
 * Testing Internal Links, as well as the sub links such as tabs
 <hr>

### Testing the Forms
 * Testing to see if the required fields are required
 * Testing the Submit Button
 <hr>

### Validator Testing
* Validating the HTML in the site
    * Validation results - [W3C Validator](https://validator.w3.org/nu/)
    <hr>
 
* Validating the CSS in the site
    * Validation results - [CSS Validator](https://jigsaw.w3.org/css-validator/)
    <hr>

### Site fluidity 
Grammarly was also used to test the various pages for any spelling and grammar errors.
 <hr>

### Browser Compatibility
I tested the compatibility of my site first by by emulating different devices using the Dev tools in **Chrome** as well as using the variable responsive setting to check at different breakpoints. 
* The various tests that were run were:
    * checking to see if the all images and cards scaled and maintained aspect ratio as the display shrunk and grew.
    * checking to see if responsive elements within my layout changed at the correct breakpoints, such as the navbar and cards.
    * checking to see if my media queries behaved as expected with regards to cards displaying in columns or rows, navigation.  

I then tested it on different browsers. I have tested in **Chrome**, **Firefox** and **Edge**. Once I was sure my project worked on windows 10, I then opened it on my phone running **Safari** on **IOS 15**. 
 <hr>

## Testing 2.0
My second round of testing involved accessibility and readability, checking the live site against various industry standards such as Eightshapes and Webaim to ensure a well thought out UX and UI.

### Contrast Checker
* The first port of call with regards to contrast was [Eightshapes Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23FFFFFF%2C%20White%0D%0A%23FFEFCA%0D%0A%23888888%0D%0A%23402E32%0D%0A%23000000%2C%20Black%0D%0A%2303011e%0D%0A%23303149%0D%0A%23CEA716%0D%0A%235F634F%0D%0A&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18) so as to best understand the contrast between all the elements of the site, ensure fonts were readable against backgrounds and that font sizing was consistent to maintain accessibility.
    
*   The site was tested using A11y colour contrast accessibility checker [Contrast Checker](https://color.a11y.com/Contrast/) to ensure maximum readability and accesibility.
    
* The site was tested using WAVE, web accessibility evaluation tool [Webaim](https://wave.webaim.org/report#/https://iainknox.github) to ensure accessibility criterea were met.
 <hr>

### Lighthouse Scores
*   The site was tested for both mobile and desktop scores via [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) with multiple tests being conducted. 
    
* For the most part pages consistently scored 100 for accessibility and SEO and high 90's for performance and best practices.

### AmIResponsive

* The site was tested with the amireponsive tool to determine how well it would look on various outputs. ![AmIReponsive](/assets/images/readme-img/amiresponsive.png)
    
<hr>
<p>&nbsp;</p>

## Deployment
I have hosted my site on github pages, it can be accessed from the following url:

https://iainknox.github.io/(site-name)

<hr>
<p>&nbsp;</p>


## Credits

<hr>
<p>&nbsp;</p>

### Content

* The color was inspired by running various searches through google with the keyword **Yoga** and then further refined with the help of sites such as [Color Space](https://mycolor.space/) and [Coolors](https://coolors.co/cea716-03011e-5f634f-303149-ffefca)

* The fonts were acquired via [Google Fonts](https://fonts.google.com/)
<hr>
<p>&nbsp;</p>

### Media
* Icons used throughout the site for social media and card graphics were sourced from the free kit made available on [Font Awesome](https://fontawesome.com/v5.15/icons?d=gallery&p=2&q=social)
<hr>
<p>&nbsp;</p>

### Other Resources
* To better add to my understanding, markdown syntax was reseached from [Markdown Syntax](https://dotcms.com/docs/latest/markdown-syntax) to aid in compiling and styiling this README document :)

* While most programming happened at unsocialable hours, when I really got stuck the web is an invaluable resource too, I did a fair amount of review on [W3 Schools](https://www.w3schools.com/) Concepts such as the **flip cards, sticky navigation** and **grid** all came from here.
<hr>
<p>&nbsp;</p>