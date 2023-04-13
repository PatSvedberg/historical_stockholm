# Historical Stockholm. Portfolio Project 1 by Patric Svedberg

### This project is my first portfolio piece. The goal was to create a webpage that aids in exploring Stockholm's history, catering to both residents and visitors. Google Maps were utilized to mark noteworthy locations and museums for visitors to explore. Additionally, a dedicated page was included for relevant museums with detailed information.

# [Deployed site ](https://patsvedberg.github.io/historical_stockholm/)
<br />
<br />

![Image of project on different devices](/assets/images/readme-top-image.jpg "Image of project on different devices")
## Table of Content:

* [Pages](#pages)
    * [About](#about)
    * [Map](#map)
    * [Museum](#museums)
* [User Experience](#UX)
    * [User Demographics](#Demographics)
* [Design](#Design)
    * [Color Scheme](#Color)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
* [Technologies Used](#Technologies-Used)
    * [Software Used](#software-used)
    * [Languages Used](#Languages-used)
* [Testing](#Testing)
    * [Notes](#Notes)
    * [Bugs](#Bugs)
    * [Lighthouse](#Lighthouse)
    * [Validators](#Validators)
* [Features](#Features)
    * [Header and Navigation](#Header-and-Navigation)
    * [Footer](#Footer)
    * [Index](#Index)
    * [Map](#Maps)
    * [Museums](#Museum)
    * [Features Left to Implement](#Features-Left-to-Implement)
* [Deployment](#Deployment)
    * [Deployment](#Deployment)
    * [Forking the GitHub Repository](#Forking)
    * [Making a local clone](#Clone)
* [Content](#Content)
    * [Content](#Inspirations)
    * [Media](#Media)
    * [Acknowledgments](#Acknowledgments)

    # Pages:
    ## About:
    The purpose of this page is to greet visitors and clarify the content of the site.

    ## Map:
    Embedded in this page is a Google map with personalized markers denoting sites of potential interest for visitors to explore. Additionally, a suggestion box is available for visitors to provide feedback about any missing locations.

    ## Museums:
    This page has a great collection of relevant museums, complete with informative details about each one.

    # UX
    ## Demographics:
    * People who is visiting or local to Stockholm and want to find places to explore the history of the city
    <br />
    <br />
    # Design

    ## Color:
    I opted for a yellowish hue in the design, inspired by the architecture of Stockholm, particularly the old town, which prominently features yellow tones. Additionally, yellow is often associated with a cheerful and upbeat mood.

    I only used two colors while coding. But I use the colors of the images to give it more colors.
    Color code:

    Image made using [Coolers](https://coolors.co/)
    ![Alt text](/assets/images/colors.PNG "Pictures of my colors")

    ## Typography:
    This site uses the fonts: <br /> 
    **[Pragati Narrow - Bold 700](https://fonts.google.com/specimen/Pragati+Narrow?query=praga) <br />**
    **[Martel Light 300](https://fonts.google.com/specimen/Martel?query=martel) <br />**
    **[Average Sans Regular 400](https://fonts.google.com/specimen/Average+Sans?query=Average+Sans) <br />**

    ## Imagery:
    I use images of Stockholm's old town and images from the museums.

    # Technologies Used:

    ## Software Used
    * Gitpod
    * Github
    * Google Chrome Dev Tool

    ## Languages Used:
    * HTML
    * CSS
    <br />
    <br />

    # Testing:

    ## Notes:

    * I've noticed that the round maps are not optimal for mobile use. So they will most likely be a regular square shape for smaller screen sizes. Will investigate the smallest optimal size for round shapes.

    * Managed to make the circle images and maps fit even with smaller sized screens.

    ## Bugs:

    ### About page:

    * **Expected**: Hero image does not scale and look the same on every screen size:
        * **Testing**: In the Chrome Developer Tool, I changed the screen size up and down.
        * **FIX**: In the CSS I added a height: 100% to the image.
        * **Resault**: Now the image scales the same on every screen size.
    <br>
    <br>

    ## Validators:

    * The HTML validator did not like that I didn't have a H2-H6 in the "< section >". So I changed to a "< div >" to make the validator warning go away.

    ![HTML validator error image](/assets/images/htmlerror.PNG "Image of HTML validator error")
    <br>

    ### HTML validator:
    <br>

    ![HTML validator image](/assets/images/html-valid.PNG "Image of HTML validator")
    <br>

    ### CSS validator
    <br>

    ![CSS validator image](/assets/images/css-valid.PNG "Image of CSS validator")
    <br>

    ## Lighthouse

    ![Image of Lighthouse score](/assets/images/lighthouse.PNG "Image of Lighthouse score")
    <br />
    <br />

    # Features

    ## Header and Navigation:

    * The header has links to the different pages and a logo made from a < h1 > that also links to the index page.
    ![Image of Header](/assets/images/header-img-min.PNG "Image of Header")
    ## Footer
    * The footer has links to four different social media platforms (**Facebook**, **Twitter**, **Youtube** and **Instagram**)
    ![Image of Footer](/assets/images/footer-img-min.PNG "Image of Footer")
    ## Index
    * The index page greets the user with a welcome text and picture of Stockholm inside a circular border. This design is consistent throughout the project. At the bottom of the page above the footer the contact information is located with a **Google Map** with the location.
    ![Image of Index Page](/assets/images/index.PNG "Image of Index Page")
    **Contacts:** <br />
    ![Image of Header](/assets/images/contacts-img-min.PNG "Image of Header")
    ## Maps
    * Here the user can see places of interests around the city. They can also suggest new pins to be added to the map.
    ![Image of Index Page](/assets/images/maps-img-min.PNG "Image of Index Page")
    ## Museum
    * Here there is a collection of museums to visit with a picture and a small text describing the museum.
    ![Image of Index Page](/assets/images/museums-img-min.PNG "Image of Index Page")
    <br>

    ## Features Left to Implement:

    * More interaction for the Google maps.
    * For the form on the Map page. Being able to send input to an email.
    * More info for the museums. Adresses, phone, email etc.
    * Make a custom look for the scrolls.
    <br>
    <br>

    # Deployment:

    ## Deployment

    The project was deployed to GitHub Pages using the following steps...
    * Log in to GitHub and locate the GitHub Repository.
    * Find the "Settings" button on the menu at the top of the repository
    * Scroll down the Settings page until you reach the "Pages" section.
    * In the "Source" section, click the dropdown labeled "None" and choose "Main Branch".
    * The page will refresh automatically.
    * Wait for the deployment process to complete.
    <br>
    <br>

    ## Forking

    To create a copy of an existing GitHub repository without affecting the original, we can fork the repository using these steps:
    * Log in to your [GitHub](https://github.com/) account and navigate to the repository you want to fork.
    * Click the "Fork" button at the top right of the repository page.
    * You should now have a copy of the original repository in your GitHub account that you can view and make changes to without affecting the original.
    <br>
    <br>

    ## Clone
    Here are the steps to clone a GitHub repository:
    * Log in to your [GitHub](https://github.com/) account and locate the repository you want to clone.
    * Click the "Clone" button.
    * Copy the HTTPS link shown under "Clone with HTTPS".
    * Open Git Bash or another command-line interface.
    * Navigate to the directory where you want to store the cloned repository.
    * Type git clone and paste the URL you copied in Step 3. The command should look like this: git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.
    * Press Enter to run the command.
    * Wait for the cloning process to complete. A message like the following should appear in the console:
     * 
    ```
        $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
        > Cloning into `CI-Clone`...
        > remote: Counting objects: 10, done.
        > remote: Compressing objects: 100% (8/8), done.
        > remove: Total 10 (delta 1), reused 10 (delta 1)
        > Unpacking objects: 100% (10/10), done.
    ```

    # Content
    ## Media:
    **NOTE! This page is for educational purposes only!**

    * [Nordiska museet Image](https://www.nordiskamuseet.se/sites/default/files/public/subject/nordiskamuseet-vackra-trad-host-insta_alexander_assal_low_webb.jpg)

    * [Background image](https://paraplytours.com/wp-content/uploads/2019/03/stockholm-under-kastanjen-cafe-1-1300x0.jpg)

    * [Hero image](https://www.kihousing.se/our-accommodation-areas/)

    * [Livrustkammaren Image](https://melkerlarsson.files.wordpress.com/2015/01/livrustkammaren-rustningar.jpg?w=700)

    * [Medeltidsmuseet Image](https://upload.wikimedia.org/wikipedia/commons/4/48/S%C3%B6_274%2C_Medeltidsmuseet.JPG)

    * [Vasamuseum Image](https://sv.wikipedia.org/wiki/Regalskeppet_Vasa#/media/Fil:Djurg%C3%A5rden,_%C3%96stermalm,_Stockholm,_Sweden_-_panoramio_(8).jpg)
    * Favicon using [Favicon Generator](https://favicon.io/favicon-generator/)
    * The social media icons were taken from [Font Awesome](https://fontawesome.com/)
    
    ## Inspirations:
    * The footer HTML-code was inspired from Code Institutes ”Love Running” project.
    <br />
    <br />
    # Acknowledgments:

    ## Thanks to:
    ### Lauren-Nicole Popich
    * My mentor. For helpt end encouragement!

    


