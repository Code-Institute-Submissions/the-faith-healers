# User Centric Frontend Development Milestone Project

#### Create a website for a band

Build a static (front-end only) website for a band. As a starting point, you may want to use wireframes, as we did in the UX lesson (you can use Balsamiq or any other tool, including just pen and paper). You can use either your assets or the assets within the following [GitHub repo](https://github.com/Code-Institute-Org/project-assets).

The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. You have been given the following requirements after interviews with the client’s representatives:

Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

Also, the band would like to use the site to showcase their music and publicise their availability to perform at events such as weddings and Christmas parties.

The band has provided you, the developer, with the following assets that they would like to showcase on their website:
* Photos of the band members
* A video clip
* Audio clips

Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.

***

# The Faith Healers
The Faith Healers are a local band, who's aim is 'to do exactly what it says on the tin: blues, funk, a bit of soul and rock'. They love to see people getting up to dance at their shows.
## UX
### Strategy
The band needs a new website to showcase their music in order to make new bookings at pubs, local events and festivals.
I have permission to use any media content from the band's original website and any of their social media sites, including Facebook and YouTube. 
The target audiences for the band's website are event organisers, pub landlords and fans. The audience will need to be able to view and listen to the band's material, easily find their social media pages as well as contacting the band directly for booking.
#### Strategy Tradeoffs
|Opportunity/Problem |Importance |Visability/Feasibility |
|:------------------ |:---------:|:---------------------:|
|Increase bookings |5 |5 |
|Showcase music |5 |5 |
|Promote social media |3 |4 |
|Extensive media content for fans |2 |1 |



### Scope
A pub landlord or an event organiser will want to easily find out what type of music the band plays, what type of space they'll need for set-up, as well as some sample music and video clips to make sure they know exactly what they're booking. With this in mind, a user will want easy navigation on a mobile device; for example a band member should be able to take their phone out of their pocket and show the booker a video or play a song in as little as three clicks from the homepage.
Fans will want more in depth information about the band members as well as access to pictures, music and videos. They will also want to know to when and where the band is next playing. Pages on mobile and desktop views should load fast with intuitive media content, for example a slideshow of images or a playlist of songs. All content should be available on the website, not linking to an external website. From mobile view to desktop view, fans should be easily directed to the band's social media pages. 
#### Key Functions
* quick/easy navigation throughout the site: max. 3 clicks to find the desired content
* view/listen to the band's music
* contact the band for bookings or enquiries
* links to the band's external social media

#### Page Requirements
Each page will contain clear navigation to the other pages including the homepage, contact page and social media links.
### Structure/Skeleton
#### Site Map

![site map](/assets/readme-images/readmeinfoarchitecture.png)

The Home page is the landing page for the website. It will contain a brief description of the band with a slideshow of pictures.
The Band page will feature a picture of each band member with a short description of their role within the band.
The Watch page will have embedded YouTube videos for users to watch.
The Listen page will have an iframe from the band's Soundcloud page for users to listen to their songs.
The Live page will list the band's gig dates and feature a countdown until the next gig.
The Contact us page will allow users to complete a form with their name, email address and message to contact the band for any enquiries including bookings.
The navbar will feature at the top of each page, along with the social media links in desktop view. The footer on each page will contain the copyright declaration and a link to the contact us page (which will feature the social links on mobile and tablet views).
#### Wireframes
View the project wireframes [here](https://projects.invisionapp.com/freehand/document/oZqbPe0Iy)

#### Interaction Design
To ensure a consistent design throughout the site, I will use a colour board to create a theme. All links will have the same styling, and when hovered over. All headings will have the same styling. All images will be edited in shape and size to fit the theme. 

#### Information Architecture
The project will use the following standard tree structure:

![Site Map](/assets/readme-images/readmeinfoarchitecture.png)

![Information Architecture](/assets/readme-images/readmesitemap.png)

*A visual guide to the project's file structure.*


#### Features
* the Home page will feature a slideshow of photos of the band, using a Bootstrap carousel. The caption on each photo will link to the corresponding page of the website
* the Watch page will feature three videos embedded from YouTube
* the Listen page will feature an iframe from Soundcloud which will allow the user to play a selection of the band's songs
* the Contact page will feature a form for the user to populate with their name, email and a message or enquiry to send to the band
* the Live page will feature a countdown timer, set to the time and date of the next gig

#### Features left to implement
* the form on the Contact page will eventually have the back-end technology to send and process the data 
* in the future the site could host an online store allowing users to purchase the band's merchandise

### Surface
#### Colour board

|HEX |Colour |
|:------- |:------ |
| #3e4444 |Slate grey |
| #82b74b |Light green |
| #405d27 |Moss green |
| #c1946a |Beige |


After the midpoint meeting during this project I decided to change some of the styles for the website to really enforce the 'design' side of things. My original colour choices were very safe, trying to cater to a more 'masculine' taste. I have decided to experiment with a black base and splashes of bold and bright colours to highlight the features on my site. I will keep a theme throughout.
#### Revised Colour Board

|HEX |Colour |
|:------- |:------ |
| #1bd37a |Mint green |
| #00bcbc |Bright blue |
| #ff0066 |Bright pink |
| #ffcc00 |Mustard yellow |
| #849191 |Dark grey |
	

#### Typography
The fonts Abel and Roboto Condensed from Google Fonts will be used throughout to compliment and contrast headings, links and other text. All links will have a ':hover' property that corresponds to the colour board. Font Awesome will be used for the icons for each social media link.
## Technologies Used
The overall structure of the site is created using semantic HTML5 alongside the Bootstrap 3 CSS framework used for elements such as the nav bar. I have used CSS3 to create custom styles to enhance the design of each page. Bootstrap 3 has also been used to support elements that use Javascript, for example the carousel on the homepage. All styles can be found in assets directory.
## Testing
Testing has been consistent throughout the development of this site; with every new feature, style or new content being run via the IDE Cloud9, as well as using Chrome Developer Tools to isolate certain elements of my code.  Chrome Developer Tools have also been used to view each page on responsive screen sizes as well as the predetermined sizes such as the iPhone 6, a Galaxy S5 and an iPad pro. 
This testing highlighted a recurring problem with the nav bar wrapping the social media links onto two rows on smaller screen sizes before the media query activated to collapse the nav bar into the hamburger button. I tried many solutions, including adding a max-width to the social media links as well as altering the media query to collapse the nav bar at a larger screen size but feedback from users was that this didn't work as expected. An alternative solution was made to hide the social links from the nav bar at certain screen sizes, and to show the links on the contact page instead. This is a compromise on my original design, however the predetermined Bootstrap 3 styles do not allow for the UX I had planned. The same bug has been discussed on a Slack Overview channel and has also been tackled in a more recent release of Bootstrap.
After every commit to Git I have validated all HTML and CSS through an online validation service. 

* For the HTML I used: https://validator.w3.org/
    * One outstanding error in my HTML is highlighted is the target="_blank" attribute on the external links on the site. I have not removed this error as it is good UX to open external links such as social media pages in a new tab

* For the CSS I used: https://jigsaw.w3.org/css-validator/
    * There is one remaining error in a custom CSS style for the .carousel class, the height is set to '300' which should require a unit for the height..

Any other errors in my code highlighted by the validators were found, edited, and run again until correct.
I have personally tested all links on the site, including all page-to-page navigation, the arrows for each slide on the carousel as well as each link to the Band's social media pages.

## Deployment
All code for this website is written and edited in the Cloud9 IDE. A GitHub repository has been created for this project, called the-faith-healers. 
Each phase of work has been committed to Git and pushed to this repository. The final site is being hosted by GitHub pages using this URL: 

https://elliegmawer.github.io/the-faith-healers/ 

## Content
All media and content from the band (photos, music, videos and bios) has been used with permission from The Faith Healers. 
 The following free sources have been used for certain elements and features on the website:


* [Bootstrap 3.3.7 styles and Javascript](https://getbootstrap.com/docs/3.3/components/)

* [Background colour gradients](https://www.w3schools.com/colors/colors_gradient.asp)

* [Live Countdown timer](https://www.w3schools.com/howto/howto_js_countdown.asp)

## Acknowledgements
The inspiration for this project has come from my Father, a member of the Band, who has no idea how to market his talent! Developing a site that is to be used by a real client rather than for a fictional project specification has allowed me to challenge my knowledge and ability as well as providing experience of working across the UXD planes.
