<img src="assets/images/logo.jpg" style="margin: 0;">

# Anya Karin singer song writer

This project aims to promote the identity and work of Anya Karin as a singer and song writer. The current music market understands that to achieve popularity, the songs should reach the consumer repeatedly in order to create familiarity as Duhigg explains in "The Power of Habit".  
At this moment in time, radio is losing its place as top gatekeeper between music and the audience, giving way to platforms such as spotify and apple play.  
As the trends favour the streaming market that had a rise from 76.8 million users in 2015 to 278 million users in 2019. Therefore, an online presence is vital in order to reach listeners. A website that contains enough information to convey the artist's identity and work would become the home of the digital image and the link to different social and streaming platforms used by the artist.</p>


## UX

Anya Karin is a singer / song writer with base in Lisbon singing pop music both in Portuguese and English.

### Ideal consumer:
  * The ideal consumer will be part of the population of music streaming subscribers and youtube listeners that chooses pop playlist
  * The ideal uses daily youtube and streaming platforms to listen to music and costumises their playlists playing favourit artists repeatedly.   

 ### Project aims: 
  * The website aims to provide a clean, professional image to the fans and future fans that wish to find out more about the artist.  
  * The artist has youtube presence and presence on streaming platforms, as well as on social media. However the current website lacks creative design. This project aims to correct that problem so it becomes user friendly.
  * The end aim on the website is to promote a professional image, increase number of listeners, followers and sales.

 ### Strategy:  
  The strategy includes to promote the visualization of youtube videos and purchase of the songs. It also includes the oportunity of the consumer to contact the artist to hire for gigs and events.

### Structure:  
  The webstite contains 5 pages (initially thought of 4: Home, Music, About, Contact, but soon realised that needed to separate videos and song lists on music page).
(to include wireframes)


### Scope:
Content requirement:  
     - About page (consumer to find out about the artist)  
     - Store (maybe wwithin a music page - to enable sales)
     - links to social media pages
     - listen and play button and videos for access to the songs and increase familiarity


### Features
  * "carousel" - with artist photos, highlighting song name with link to page where the consumer can stream or buy the song.  
     This feature is found the on the home page.
  
  * Navigation bar - on the top of the page it is presented a navigation bar with logo and links to all pages.  
     This feature is presented in all pages and is responsive to all screen sizes;

  * Social media links - on every footer and presented with the social media icon.
     These links will offer the opportunity to links with the artist social media.
     
  * Youtube videos - the 5 videos with most views on youtube will be presented in the video page.

  * Songs list - A list of all the artist songs with the icon to buy and play a sample of the music.  
     This list wwill be on the music page and at this stage the icons to play sample and to buy will not be functional.

  * Submit form - with place to submit request to hire artist for events / gigs.  
     This form will be on the contact form and at this stage will not be submitting data to a recipient.
     In future would like to add a live chat where the consumer can be given the opportunity to message and have a reply instantly when the artist is online.

## technology used
The languages used in this project were HTML5 and CSS3, fundamentally. In addition to to HTML and CSS, it was used bootstrap 4 library throughout this project as it is a mobile first framework, very useful in building a responsive layout.  
It was also used fontawesome framework for the use of icons throughout the project.


## Testing
Pages of the website have been throughouly tested to ensure that all features are functional with the following exceptions:
  * music page - play and buy icons do not work yet - the functionality of both buttons will be the focus of the second stage of implementation.
  * contact page - submit button is not operational as it is also part of second stage of this project.


The tests conducted included visit the different webpages on all screen sizes, using the "inspect" element of google chrome browser. Additionally I visited the website in different browsers - microsoft edge and firefox.  
  * navigation bar - logo links to home page; page links are all operational, hover properties work as expected;
  * carousel - responsive to screen sizes, song titles with operational links; indicators working when clicked;
  * News container - bell icon with working link to youtube page, youtube video hidden in small screens;
  * cards on home page have responsive layout, last cad hidden for medium size screen;
  * footer - social media icons linking correctly to social media pages;
  * about page card - responsive layout;
  * music page - responsive layout - icons play and buy do not work;
  * video page - all youtube videos work as soon as pressing play on them;
  * video page - listen button has a hover timing that needs to be looked up on second stage of website as in mobile border when hovering is wider than expected;
  * contact page - required fields had been included and work, as it remindes me I cannot submit without Name and email and content of message, submit button is yet not operational;

Throughout the project was particularly difficult to resolve issue of carousel images responsive layout. Firstly I was required to change all the sizes of the photos and to experiment
different sizes to decide what was best.  
Footer also proved to be a challenge as in contact page and about page the footer would either not be at the bottom or would be hidding content. 



## Validation

Used [https://validator.w3.org](https://validator.w3.org) in order to validate website [https://veraleitaodev.github.io/Anya-Karin/](https://veraleitaodev.github.io/Anya-Karin/).

There was one error found and one warning. the error mentioned that *framerborder* on iframe element, in index.html line 151 was redundant, I removed the *frameborder* and error was resolved.  
The warning was regarding the excess use of hiphens disabling makability of the comment. Problem rectified by removing excessive hyphens.

## Deployment

This project was created using the master branch and then deployed as github pages from Git Hub repository:

  * selected _gh-pages_ from __branches__.
  * selected __settings__.
  * scroll down the page to __gh-pages__ section and selected from __source__ *gh-pages*.
  * changed master branch to *gh-pages* and the website is then deployed.
  * on this area is the link of the deployed website.

           [https://veraleitaodev.github.io/Anya-Karin/]
 
## Credits

### content
  * Cards with shadow were learnt from Giobanno at [https://bootsnipp.com/snippets/vN2mb] and adapted the content to website.
  * 

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for se--ction Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X

