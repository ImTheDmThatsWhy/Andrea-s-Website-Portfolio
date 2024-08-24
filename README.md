# Website
Andrea Sutton's Portfolio Website
<!-- note by preference of the designer css has been used instead of scss -->
## Key notes
For the purpose of this website the breakpoints have been designated as the following 
- extra small devices 600px and down
-medium devices tablets 768px and up
-extra large devices 1200px and up
As suggested on (W3 schools, 2024)
link= https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp
## Overview
This website is about the web developer in progress Andrea Sutton. The website will feature a home page, about page, project page, and contact page.
## Compenents 
### Header
At this stage the header consists of a profile photo which will later be stylised into an icon, and a heading. A nav bar, and additional css styling will be added later
Css styling has been added for header color and header image. Nav bar has also been added but needs additional Css styling. The Navbar has had additional styling done and now an underline will appear when a page link is hovered over.
    #### Nav bar
    To link multiple html documents together a nav bar was created to allow users an accesible user friendy way to access different pages. The html code is below 
    
```html
<nav>
        <a href="#" id="Home">Home</a>
        <a href="html files/About.html" id="About">About</a>
        <a href="html files/Projects.html" id="Projects">Projects</a>
        <a href="html files/Contact.html" id="Contact">Contact</a>
</nav> 
```
The css for the nav bar (mobile first design) the hover element is an animation that allows users to see which home page they are going to click on. The cursor also changes from a pointer to a grab hand to clearly show a link.
```css
nav {display: flex;
 justify-content:space-around;
 font-size: }1.5rem;

nav a{text-decoration: none;
    color: blue
}
#Home:hover{
    text-decoration: underline blue;
}
#About:hover{
    text-decoration: underline blue;
}
#Projects:hover
{
    text-decoration:underline blue;
}
#Contact:hover{
    text-decoration: underline blue;
}
```
#### Hand animation 
in addition to over animated elements including:

1 buttons changing colour when hovered over

2 input boxes changing colors

3 footer contact info becoming enlarged when hovered over

4 zooming in on images when hovering or clicking

5 facebook and linkeidn icons changing color when hovered over or clicked on

There is also a waving hand on the home page when users enter to convey a friendly welcome

The html and css coding is as follows:
```html 
 <div><p class="welcome-heading">Hello There</p><img class="wave container" src="https://img.icons8.com/emoji/144/waving-hand-light-skin-tone.png" alt="waving-hand-light-skin-tone"/></div>
```
```css
@keyframes wave{
0% {rotate: 0deg; }
20% {rotate: 15deg;}
30% { rotate: -5deg;}
40% { rotate: 15deg;}
50% {rotate: -5deg;}
60% { rotate: 15deg;}
70% {rotate: -5deg;}
80% {rotate: 15deg;}
90% {rotate: -5deg;}
100% {rotate: 0deg;}
}
.wave:hover{
    animation-name: wave-hover;
    animation-duration: 2s;
}
@keyframes wave-hover{
0% {rotate: 0deg; }
20% {rotate: 15deg;}
30% { rotate: -5deg;}
40% { rotate: 15deg;}
50% {rotate: -5deg;}
60% { rotate: 15deg;}
70% {rotate: -5deg;}
80% {rotate: 15deg;}
90% {rotate: -5deg;}
100% {rotate: 0deg;}
}
img.wave{
    height:14vw;
    width: auto;
```
### Footer
The footer contains a mobile contact number, an email address, and a business address, css styling will be added to the footer later. Footer background color has been added and phone,email,and business address. Additional css styling will be added later. Icons, have been added to the footer 
The phone, email, and business information now becomes enlarged when a user hovers over it for increased readibility 

## Home Body
Image has been added and styled using Css and introduction text and buttons have been added. Additional css styling will be performed though on the buttons and introduction text.
Additional styling has been formed to add links to the button, change the pointer to a hand symbol when the text is hovered over for the buttons, and change the color of the buttons when hovered over.
New css styling has been added to make the page responsive to large screens.
An animation has been added so that a hand waves when a user enters the site and when a user hovers over the hand.Css responsive design elements have been added 
## About Page
The about page has now been created and includes information about the page designer, programming skills, and job history, css will later be modified to make the information more user friendy on larger screen sizes.
Css responsive design elements have been added 
A button that downloads a resume with previous job history has also been added.
## Contact page
A contact page has been added complete with a contact form, icons with working facebook and linkedin links, and a message. Css has also been added so that when a user clicks on a box the input background changes for better visibility and so that the user can see which box they are using. The submit button when hovered over will also change color.
Css responsive design elements have been added 
## Project page
project page complete with css responsive design added to allow for responsiveness across different pages through the use of flex box.

 Scratch game:

 On the desktop screen a playable version of the game has been added with a go to website link appearing if the user wishes to go to the website

 On the tablet and mobile versions a picture of the game appears and if the user clicks on the image they can go to the website (this is the case as the game is not playable on the mobile and tablet versions)

## Placeholders
Placeholders is made up information for the sake of examples
the business address is a placeholder for a "real" address i could be contacted out

All resume information except for the education and the normal sentences the rest is placeholder information
 ## Reference
 1: W3Schools (2024) _How TO - Typical Device Breakpoints_. Available at :https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp (Accessed: 24 August 2024)