# MS1-Portfolio

Milestone Project 1 - My Portfolio

I have developed this pagewebsite to showcase my work to potential employers. The website has been created using HTML, CSS and Bootstragh 
highlight my skills and experience without going into too much detail.

I have however provided a link to download and view my CV for those wanting to know more about me and my previous experiences. 

Screenshot of final website on different screens:
[Websitemockup](assets/images/Final-website-mockup.png)


---

## User Experience (UX)

User stories

The website is designed for potential employers to be able to quickly see what my main skills are. They will also be able to quickly see my area of 
experties and have an option to download my CV for deeper overview. 
I have made the website easy to navigate from the landing page with 'View my Work' button which will take the user to the 'About' page and from there 
I have used the navigation bar on top of each page. 
The color pallete used is minimal and I have made sure is repeated across the site so the user experience doesn't change between pages.

## Features

The website consists of four pages. The homepage as the landing page. It consists on my name and my title and a button to take the user to the next page. 
A about page, which contains a brief introduction of my self, my skills set and my Teck stack. A projects page to shows the prjects I have worked on to show 
my skills in actions and a contact page with a contact from for the user to get in contact if they need to. 

### Existing features

- Feature 1 - The nav-bar was fixed to the top of the screen to allow users to easily navigate through the site. 
- Feature 2 - The links to Contact form allows people to send me message directly Does not contain a mailto action, 
so will refresh when the submit button is pressed.
- Feature 3 - Link to CV to allow potential employers to download a word document copy of my CV.
- Feature 4 - Link to my LinkedIn and Github pages.

### Features for future implementation

If I was to continue the development of this website, I would look to add:

- Keep site updated with future work experience.
- Put site up on a custom domain.
- Add mailto action to contact form, so potential employers can contact me directly.

---

## Wireframes & Mockups

- The wireframes and mockups were created using Balsamiq wireframes. The layout of the site didn't change too much from the original design. 
The main design difference between the mockups and the finished site was to the projects page. I did not feel it was a good idea to 
to just add the card and link the project,so I add a brief discription of the project and the technologies used to create the project.

Basic Wireframes:

- [Tablet Wireframe](https://github.com/Hkitimana/MS1-Portfolio/blob/master/Documentation/wireframes%201.png)
- [Desktop and mobile Wireframe](https://github.com/Hkitimana/MS1-Portfolio/blob/master/Documentation/Wireframes%202.png)

---

## Technologies

- [HTML5](https://github.com/liigalized/MS1_boredom_guide):  
HTML was used to define the basic structure of the site. Utilising standard HTML elements such as Divs, Unordered and Ordered lists and Paragraphs.

- [CSS3](https://en.wikipedia.org/wiki/CSS):  
Cascading Style Sheets were used to style the pages of the sites by using user created and existing HTML and Bootstrap classes.

- [Bootstrap 4](https://getbootstrap.com):  
Bootstrap v4.5.0 was used to help structure the rows and columns for the Bootstrap grid on the Skills page. It was also utilised for the Contact form 
on the contacts page, to allow the form fields to stack on top of each other at smaller screen sizes. It was also used to create cards for projects on the projects page.

- [Google Fonts](https://fonts.google.com/):  
Was used for the fonts used in the website for the body and headings.

- [Font Awesome](https://fontawesome.com/):  
FA was used to add icons on the footer utilised for the Github and LinkedIn social links in the footer.

- [Balsamiq](https://balsamiq.com/):  
I used Balsamiq wireframes to create the wireframes and mockups for the project.

- [Git](https://git-scm.com/):  
Git was used for version control and tracking of changes made to the code.

- [Github](https://github.com/):  
Github was used to host the project repository, while Github pages was utilised to publish the site.

- [Github Desktop](https://github.com/desktop/desktop):  
I used Github Desktop to push and fetch files to and from the Projects online repository.

- [W3C Markup Validation Service](https://validator.w3.org/):  
Used to validate my HTML code and alert me to any errors.

- [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/#validate_by_uri):  
Used to validate my CSS code and alert me to any errors.

---

## Testing

### Navigation Bar / Footer:

- Navigation bar is fixed to the top of the screen on all screen sizes, and all links to other pages on the site. This has been tested on desktop, laptop, tablet and mobile devices.

- The footer is located at the bottom of the screen but is not fixed, so will only show once the user has scrolled to the bottom of the page. This was done to make sure that the user could maximise the available screen estate when reading through the page.

- The social links open on new tabs with the currently used browser. Again this was tested across all devices.

- With the CV download link, this will download the CV as a word document at te bottom on a laptop screen, and above it will give you the option to open or save cv locally depending on the device.

### Homepage:

- On the homepage the landing text and animation works well when viewed on the big device and this has been tested on the smaller devices too and it was works perfectly

- The 'View my work' button is responsive and it has been tested on all devices. When viewed it will take the user to the about page.

### About Page:
- The goal of the testing on the about page was to make sure that the image and progress bars appear evenly next to each and they appear evenly on the smaller devices. 
On big screen the image should appear on the left side of the page and the progress bars to appear on the right.

### projects page:
- The projects page was tested to make sure that the cards created appear in three columns on big screens and they appear stack up on smaller screens.

### Contact:
- On the contacts page I have tested to make sure that all fields need to be filled in before you can submit the form. This was done by adding the required option on the input elements in the code.

---

## Code Validation

### CSS Validation:
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p> - PASSED

### HTML validation: (Add LINKS)

- Home page: Warning
- About page: Warning
- Projects Page: PASSED
- Contact page: PASSED

### CSS validation:

Passed (https://github.com/Hkitimana/MS1-Portfolio/blob/master/Documentation/css%20validation%20.png)

### Browsers tested

The site was tested on the below browsers, using the dev tools of each browser to check the responsiveness. This was achieved using the various device sizes available within each browsers tools.

- Firefox - Passed
- Chrome - Passed
- Safari - Passed
- Microsoft Edge - Passed

- Responsiveness was tested on MacBook Pro, iPhone and iPad. Desktop/Mobile OS compatibility was tested on macOS 10.14/15, iOS 13 and Windows 7.

The site URL was shared with friends and family and they were asked to test usability and to report back with any issues they may have experienced. No problems were reported back.

---

## Deployment

I uploaded the project files to Github and deployed the site using Github pages.

To upload the project to Github I used the process below:

1. Downloaded and installed the Github Desktop application. Logged into my Github account.
2. Installed the Github package into Atom, and connected to my Github account.
3. Staged the changes to the sites pages using the Atom Github package and added the Commit message.
4. Pushed the changes to the online repository using Github Desktop.

To deploy the project using Github Pages  I used the process below:

1. Logged into my GitHub account
2. Clicked on the link to the project repository.
3. Clicked on the Settings link in the project repository.
4. Scrolled down until I found the Github Pages section.
5. Selected Master from the Branch dropdown menu under Source and clicked Save.
6. After a few minutes the link for the published page appeared, which is:

https://hkitimana.github.io/MS1-Portfolio/.

---

## Credits

### Content

Where code has been copied from an external source, I have referenced this in the code through comments.  In many cases, the copied snippet has been amended from the source in order to achieve the desired result for this project.  I have listed the various sources below as well.

**Head**
- All CDN links copied from the respective sources - see links above in the **"Technologies Used"** section.
- The FavIcon code snippet was generated and copied across from the [FavIcon website](https://www.favicon.io/).

**Header**
- In the header, the nav element code used to create a toggle menu on small screen sizes was copied from [Bootstrap](https://getbootstrap.com/docs/4.5/components/navbar/#nav).

### Media
- The images used in this site  throughout the projects are from the [Usplash website] (https://unsplash.com/)

### Acknowledgements

- I received inspiration for this project from the CV project in the User Centric Front End Development module.

- I have also used inspiration for my project from (https://www.mockplus.com/blog/post/web-developer-portfolio) specifically used (http://findmatthew.com/)
to get inspiration and a better understanding of how to code a timeline correctly by looking at the code examples to see how they were put together.

- I received help and feedback from my mentor Felipe Souza Alarcon



