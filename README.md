# Bad & Boogie

This project is made to present a dance event in Stockholm, Sweden. It is made to create interest and be informing about the most important details of the event (such as date and time).
Navigation is made easy to avoid users having to dig for information, and basic hover animations have been added to make the site feel more interactive without adding unnecessary features.
 
## UX
 
This website is for people interested in the dance competition Bad & Boogie. The website focuses mainly on three types: Audience, Competitors, and Sponsors. 
The design is aiming to be simple and informative, as well as eye-catching. 

Below you can see the user stories for this project. 

### User Stories
- As John, I want to find out when and where the event is so I can go and watch the competition
- As Eva, I want to know what categories there are, and when the sign up deadline is, so I can participate in the competition
- As Kim, I want to know if the event is family friendly 
- As a sponsor, I want to know who is behind the event, what the values it represents are, and how to get in touch with the organisers 


Here below you can see the wireframe that this project is based on. Some changes were made later in the design process to better suit a responsive site.

![Bad&BoogieWireframe](/assets/images/wireframe.jpeg)

## Features

This project is faily simple and consists of 5 pages that are all linked together (mainly through the navbar).  
The top of each page is the navbar the links together all the pages. 

On the contact page there is a contact form that should send an email to the organiser
. 
On the tickets page are four different cards that have a button which should add them to cart. 
There should also be a check out system. 
 
### Existing Features
- Navbar - It allows the users to navigate through the pages of the site by clicking the anchor tags on the top of each page. 

### Features Left to Implement
- Properly set up the contact sheet on contact.html
- The add to cart system 
- Add the check-out system

## Technologies Used
- [Bootstrap 4.4.1](https://getbootstrap.com/)
    - Bootstrap was for used the grid system and for components (forms etc.) to speed up the design process. 

- [JQuery](https://jquery.com)
    - The project uses the **JQuery** included in Bootstrap 4.4.1 

- [FontAwesome](https://fontawesome.com/)
    - FontAwesome was used in this project for icons (specifically on the index page).

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

The testing of this site was focused on the links, buttons, and responsiveness. Since all pages are similar enough the process for all pages can be summarized the the same way:
1. Responsiveness
    1. Open up the Chrome Developer tools
    2. Scroll through all the content on the page and note any issues
    3. Change the device setting to a smaller device, scroll through and inspect the content taking note of any issues
    4. Repeat step 3 until you've reached the smallest screen size possible. 

2. Links and buttons
    1. Start by hovering over any and all buttons and links to check the hover effects 
    2. Click any links direvting to outside sites to ensure it opens on another tab
    3. Click on any link directing to another page and ensure it links correctly 
    4. Return to the page you started at 
    5. Repeat step 3 and 4 until you have tested all the links on the page 
    6. Click on any and all buttons on the page, nothing should happen in this version 
    7. Move to the next page and start over from step 1

This site is built from how it would look in two types of devices and then adapted to the devices in between. 
It had mobile as the smallest device (mainly an iPhone screen) and desktop as the largest, the breaking point landed on being the iPad as the last device with the mobile view.
Here below are screenshots of the two views:  

![Bad&BoogieDesktop](/assets/images/b&b_desktop.jpg)


![Bad&BoogieMobile](/assets/images/b&b_mobile.jpg)


## Deployment

This site was deployed through github pages. The method is listed below. 
1. Go into the github repository 
2. Click on the settings button 
3. Scroll down until you see the Github Pages heading 
4. Select the master branch on the drop down menu
5. Press deploy, it will be up after about 10 minutes 


## Credits
The pictures on this site was very kindly approved to be used by Emma Dewita Öberg, you can find her portfolio on https://www.emmadewita.com/ .


### Content

- The text for every section of this website are merely conceptual and ficticious. 

### Media

- The photos used in this site were obtained from https://www.emmadewita.com/

### Acknowledgements

- The initial design of this design was heavily inspired by the hover.css project, although this did not each the final version. 

- The navbar and contact form are based on the default bootstrap components. 
