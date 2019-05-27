# Colette O'Beirne - Portfolio Website

This is a portfolio website for artist, Colette O'Beirne. The website highlights the two artistic media in which the artist works, music and sculpture. It also includes some biographical information, a contact form, and links to social media sites. 
 
## UX

My goal in the design was to create a very visual and accessible site, which emphasised the art, and maximized the aesthetic experience for the viewer. The pastel grey colour scheme was chosen to provide contrast to the aesthetic aspects of the site, to avoid drawing attention from those aspects, and to give the website a professional and modern feel. 

I did not use much text or headings in structuring the site because the content of the media is apparent, and the scroll structure of the website is simple for the user to navigate. There are thus fewer distractions for visitors to the website. 

I envsiage the following categories of users visiting this site:
- "Fan" As a user who has previously heard of the artist's work, I want to quickly view her portfolio, so that I can understand the range of her artistic repertoire. This is done with maximum simplicity, by visiting the site and scrolling down.
- "Newbie" As a user unfamiliar with the artist's work, I want to quickly understand who the artist is, and see examples of her work. The bio in the launch-pad section of the website, provides a concise account of the artist's background, and examples of her work can be viewed by scrolling. 
- "Potential Customer" As a user who has a query, or is interested in purchasing a piece, or commissioning the artist to produce artwork, or soliciting the artist to perform, I can either scroll down to the contact page at the bottom, or quickly click the hamburger menu icon in the top right hand of the page, and click on the contact button.  

The wireframes for this project are available here: <html href="https://github.com/kalkiboru111/new-milestone-project-1/blob/master/wireframes.pdf"> Wireframes </html>. The project diverged from the original design in the wireframes, and evolved into a more simple and intuitive design. The mobile design was represetnative of the design of the site for all scales of screen, except for larger screens where the media columns break to take advantage of the bigger screen sizes (two columns for embedded videos, four for embedded images). 


## Features

In keeping with this project's simple and intuitive deisgn, this project aimed to include only those features which complement and highlight the artwork (and exclude any which might distract or detract from the artwork). 
 
### Existing Features
- Launch-pad background image - immediately gives viewers a sense of the artist at work, and gives the site an industrious and rich texture. 
- Contact Form - allows all users to contact the artist, by having them fill out the contact fields and pressing submit.  
- Scroll-Spy - allows all users to easily identify which section of the webiste they are currently viewing, and gives the site a fluid feel. 
- image gallery - allows all users a synoptic view of the artist's artwork, with clickable thumbnails which expand for users seeking to view an image in greater detail. 
- video gallery - allows users to view a sample of the artist's songs and view her performances. 

### Features Left to Implement

In future, I plan to add further videos and images to give a more fulsome account of the artist's repertoire. 

I would also like to add a feature that expands the images upon hover, thereby reducing the friction to users who are seeking to view the images in greater detail. 

## Technologies Used

HTML
CSS
Bootstrap (3.3.7)

## Testing

The fan and newbie user story achieved the intended outcome of providing them with a showcase of the artist and her work. In the title section, they can about the artist's background. The background image provides them with an immediate visceral sense of the artist at work. The artist's work is then presented more full in the sculpture and music sections. They can view the artist's social media and works in progress by clicking on the font awesome icons. 

The contact form will not accept an invalid email address, and will provide the user as much. The 'required' attribute is added to the 'name,' 'email,' and 'message' fields. If those fields left blank, the form will not submit, and users will be notified as much. If a fan, newbie or potential customer is interested in contacting the artist, they must fill out all the fields in order for the form to submit. 

All links have been manually tested to ensure that they are pointing to the correct destination. All links will open in a new tab using 'target="_blank". 

By clicking on the submit button, the form redirects to a thankyou.html file, which thanks the user for submitting a message to the artist. Further, by clicking the links in the navbar, the scrollSpy effect works even if you're not viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested on Chrome, Safari, Internet Explorer, FireFox, and on multiple mobile devices (in each case, using Google Chromes developer tools) to ensure compatibility and responsiveness. While the background image and videos are not currently very high resolution and appear pixelated, I plan to include higher resolution images and videos in future versions. 

On a few occassions, the images failed to load due to typos in their file names. I verified that in the event an image fails to load, it's alt name will load in lieu of the image, and that these alt names will provide screen readers with the correct description of the image. 

## Deployment

The site is hosted using GitHub pages. It is deployed from the master branch. It updates automatically upon new commits to the master branch. For the site to deploy correctly on GitHub pages, the landing page must be named "index.html".

There were a number of differences between the deployed version and the development version:
- The nav-menu list items were not revealing a grey background, which was visible on the deveolpment version.  
- I needed to adjust the names of the image files so that they were all lower - an amendment which I had not made on the development version of the site. 

To run locally, you can clone this repository paste this git clone into your editor https://github.com/kalkiboru111/new-milestone-project-1.git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits
To my mother, for the artwork.  
 
## Content
All content in the "About" sections was written by me.

### Media
- The photos used in this site were obtained from the artist, Colette O'Beirne.

### Acknowledgements

- I received inspiration for this project from Haley Schafer's portfolio website. 
- Mentor Chris Zielinski assisted me with a number of issues I was having with the Bootstrap framework during development. 
