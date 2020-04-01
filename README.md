Artrage
FIRST MILESTONE PROJECT:
Artrage, Music Producer
This is the official website for the music producer Artrage. It contains his music, lyrics and other texts, as well as merchandize, and a dedicated contact page. Thus, it meets the thematic requirements for the Milestone Project.

The Music page contains four of his albums. Two are available to listen to via Apple Music (Ocean Lips, 2016) and Bandcamp (Blackmilk, 2011). Broken Stars is to be released in 2020, thus the page only provides information about it. Without a Face, 2004, is not available online.
The Lyrics section contains the lyrics from two albums and a section entitled Quickies. Those are just short snippets of text.
The Merch section contains a selection of official Artrage merchandize available to purchase.
About tells the user who this music producer is.
Contact allows the user to get in touch with Artrage by filling out a contact form a typing out a message.
The footer contains social media links and PayPal donate button.
UX PROCESS
The website is for and about the music producer Artrage. Its purpose is to:

Showcase his albums and tracks to those who are interested in electronic and/or heavy music
Showcase his lyrics and quickies
Tell the user about him as producer and musician
Demonstrate his music portfolio to those wishing to collaborate
Provide his contact information for managers, agents and fans alike
Invite users to purchase his merchandize while also supporting a noble cause
USER STORIES
User story sketch pages, diagrams, sketches and other notes are contained on GitHub: https://github.com/Artrage/artrage/blob/master/assets/project-images/milestone-project-images.pdf

1. Music
As the user opens index.html, the links to four Artrage’s albums appear both in the left menu and in the main page.
The navy-to-burgundy hover is designed to invite the user to click on the link and listen to the album, while also reading about it in the right column.
The music menu link is highlighted in a darker shade of grey.
The text links with navy font change to burgundy on hover.
As the user clicks on an album link and the relevant page opens, it is highlighted in the same darker shade of grey as the menu at the top, thus giving the user their exact “location” on the site.
2. Lyrics
As the user clicks on the lyrics link, the page opens with three separate links: two albums and Quickies.
This is also accessible from the left menu.
The user is compelled to click on one of the links to read the lyrics or the short texts.
3. Merch
The merchandize page contains nice images of Artrage branded merchandize with custom “Buy now” buttons that take the user to PayPal.
The left column contains compelling info about the quality of the merchandize as well as the good cause Artrage is supporting with the sales.
The user is given additional reasons to make a purchase.
4. About
The left column contains snippets of information about Artrage’s music philosophy, while the main section features a few of his photos and more general info about him.
The user is encouraged to read about the man behind the music and the cause.
5. Contact
The link to the contact page is located in the footer.
The first thing the user sees is the email form in the central column. This is intentional.
The left column contains the description of Artrage’s approach and methods.
The right column contains the option to donate via PayPal.
FEATURES
Existing Features
1. The app in general
Sweep-to-bottom feature in the main menu – grey-to-burgundy
General layout and color scheme are the same in all pages for synergy and
Active section and subsection are highlighted a darker shade of grey
Active links in the left menu are highlighted burgundy
Custom made PayPal donate button changes from grey to burgundy on hover to match the top menu
Ease-in 3 second delay effect is used in the logo image
Ease-in 2 second delay effect is used in the social media icons
All external links open in a new tab
Images’ opacity changes on hover on all pages where images serve as links
Three Google fonts are used: Bebas Neue in the heading, Montserrat in titles, and Oxygen in other areas
Unique favicon is used throughout
2. Music
Each album is available to stream from an online service
The players are embedded as iframe
A background image with a music note and the word “Loading” appears in the center column before the iframe loads fully
The user is able to easily navigate from album to album, or listen to each and any track
3. Lyrics
The user can easily reach any lyrics section of any album and read them
All the color changes on hover make the page look dynamic
4. Merch
Custom made Buy Now button changes from grey to burgundy on hover to match the top menu
Images change opacity on hover to invite the user to click on it and for ease of navigation
Each image opens in a new tab for a closer look
Each button opens a PayPal Donate page in a new tab
5. About
Each image is in a 1px thick border with slightly rounded corners to achieve a smooth looking border
Small icons are introduced for ease of navigation between the section, which helps on smartphone screens
6. Contact
All fields are subject to default Bootstrap validation and have to be filled out before the message is sent
The user will receive respective prompts and warnings
The actual email account is yet to be connected
7. Footer
It’s dark navy color matches that of the Artrage logo
The sections are centrally aligned for aesthetic effect
The social and contact links are burgundy and go white on hover, while the Donate button is made to stand out with light grey to burgundy on hover
Features Left to Implement
PayPal and/or Stripe store checkout as links to PayPal Donate from Buy Now are temporary
The email account to receive message from the Contact Form
A selection of which platform to stream music from, e.g. Apple, Spotify, Soundcloud, etc.
Connect the social networks links to actual Artrage accounts
Test the footer float: bottom feature. Some pages don’t take up the entire screen in large resolution.
TECHNOLOGIES USED
Bootstrap, css, some advice from stackoverflow and w3 schools.

TESTING
Each link on the website has been tested, and leads exactly where it is supposed to lead
Social Links at the moment lead to Contact page
All highlighted sections highlight correctly to show the user where on the website they are
All the links supposed to open in a separate tab do so
The website is responsive and looks good on smartphone screens.
The horizontal look on the iPad is better than the vertical.
Utilized background-image feature in the header. Originally used a font for Artrage, and the word Artrage in the logo as well, but it looked too busy. Had to tweak the newly introduced background image to ensure it looked good on all screens.
The star logo disappears from smaller screens, thus the introduction of another background image was a necessary step.
Footer entries would not centrally align without the display: inline function in smartphone and iPad modes.
Code testing was carried out page by page on w3 validator. CSS - through Jigsaw validator. A few minor coding errors had been found in my code. What is left is something inherited from third parties such Apple Music, Soundcloud and Bandcamp, whose players I am using as iframe.
HTML beautification was carried in GitPod.
Contact form: Go to the "Contact Us" page Try to submit the empty form and verify that an error message about the required fields appears Try to submit the form with an invalid email address and verify that a relevant error message appears Try to submit the form with all inputs valid and verify that a success message appears
README was tested on dillinger.io and looks readable and in line with the convention
DEPLOYMENT
The project was committed and pushed to GitHub via Terminal app in GitPod.
Had to rename the repo to artrage-music as GitHub pages, as well as Code Institute, does not like it when username and repo name are the same.
As I am publishing this website from master, the gh-pages branch is not available in this repo.
Thus, I published in master branch.
I used the official CI template to generate the repo for this project.
Locally, I ran the code in GitPod. PyCharm was also an option in case of working offline, yet this was not necessary.
CREDITS
Two quotes marked as “stolen quotes” originally appear in the albums by Type O Negative.

CONTENT
All text for the website was written by Artrage.

MEDIA
All music is created and copyrighted by Art Balenok, registered with IMRO as Artrage. All photos, favicon, logos and artwork are by Art Balenok. The blank merchandise images were sourced as no-license-to-use. The logos and artwork used on them are by Art Balenok. All photographs were taken by Art Balenok, all album covers were created in Photoshop by Art Balenok.

Except:
The images for “Without A Face” as well as "Blackmilk" are by Sergei Balenok, who gave Art Balenok his express permission to use them without restrictions.
The photo for "Ocean Lips" was taken by Nick Balenok specifically for Art Balenok. Nick gave Art express permission to use it without restrictions.
ACKNOWLEDGEMENTS
Matt Rudge, a Code Institute lecturer, demonstrated a number features I used in this project. I did tweak them a bit though. In particular, those are:
Sweep-to-bottom features in the top menu
Ease-in-out in the header logo
Ease-in-out in the social links in the footer
Jonathan Munz, who acted as a mentor on this project and provided valuable advice.
My first README and the first website I submit for grading :) Good luck to me and thank you guys!