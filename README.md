# Portfolio

1. [Audience](#Audience)
2. [Tools](#Tools)
3. [Inspiration](#Inspiration)
4. [Design](#Design)
5. [Styling](#Styling)
6. [Responsive Design](#Responsive-Design)
7. [User experience](#User-experience)
8. [Problems](#Problems)

### <a id="#Audience"></a>Audience
The target audience are prospective employers and for this reason the website has to showcase personality and skills while being professional and concise.
For this purpose I decided to implent a pleasant casual working environment background with my picture and a short description as well as a greeting.

### <a id="#Tools"></a>Tools
To achieve my goal I made use of the following tools:
* VsCode
* Figma
* Optimizilla
* Github
* Netlify

And the following resources:
* Codepen
* Google
* Stack Overflow
* Css-tricks
* W3schools.com

### <a id="#Inspiration"></a>Inspiration
To get started and get an idea of how my portfolio would look like I googled other web developers websites and selected a few that I liked either for design or features. I also made a moodboard and build a color palette. Finally I picked a background for the home page from "unsplash".

[Matt Farley][1]

[Devin Walker][2]

![alt text][moodboard]

### <a id="Design"></a>Design
I decided to use a background image as the homepage for my portfolio website. I modified the background in figma and added a profile picture and a short description and greeting. 

![alt text][background]

I divided the website in 4 section:
* Home
* Projects
* Cv
* Contact me
##### Navbar
I decided to implement a fixed hidden navbar at the top for easy mobile access and switch to a hoverable side hidden navbar for larger devices.
##### Projects
This section includes a list of my projects with a screenshot and a brief description as well as a link to the github repository
##### Cv
I decided to include a interactive cv so that the prospective employers would be able to have a quick glance before downloading the pdf format provided.
##### Contact me
At the end of the website I included a contact form as well as the links to my Github, Linkedin, Codepen and Twitter profiles.

![alt text][figma]
[Figma][3]

### <a id="Responsive-Design"></a>Responsive Design
This is a mobile first website, with easy navigation through scrolling and top navbar. I used a wrapper to make sure the main content is centered at all times and doesn't expand too much when the page is resized. In fact I also included a maximum width to avoid breaking the design on bigger desktop devices. I used flexbox on the projects section to manage the positioning of the projects across different devices.
The navbar, is fixed on top for smaller devices and is moved to the left for bigger ones. In both case is not visible, but can be slid open when clicked on the menu bar.

### <a id="Style"></a>Style
I utilized a 4 colors palette throughout the design and styled the sections accordingly, alternating the colors and maintaing consistency thourghout the design. I used Googlefont Lato as a main font as well as Kalam for the text in the notebook. As for the animation/navbar animation I decided to follow a pure Css approach. I found different resources to build a hidden navbar and I have been through diffent ones, from hidden checkboxes or radio to my own implementation using anchor and button to simulate the click event.

### <a id="User-Experience"></a>User Experience
The design is simple and straightforward. The user can scroll through the website or use the navbar to navigate to the desired section.
The home is a simple background with a brief presentation.
Next section showcases the project providing a screenshot and description as well as a github link for a more in depth experience.
The cv section is intended to offer an easy and quick navigation through professional information and give the option to download a pdf document. Last section is a simple contact form followed by a few more personal links.

### <a id="#Problem"></a>Problems
I encountered several problems during the process:
#### Design Problems
Finding the right colour palette that would match the background I chose. Deciding what kind of navbar to use and whether a navbar for the mobile version was needed. The use of the colours with the different sections and controls. 
#### Technical problems
Trying to find a way to implement a pure css navbar hasn't been easy, and I had to fix a lot of bugs and try to build my own solution from different sources.
[css navbar][4]

[moodboard]: https://github.com/alessio-palumbo/my-portfolio/blob/master/assets/moodboard.png
[background]: https://github.com/alessio-palumbo/my-portfolio/blob/master/assets/background-min.jpg
[figma]: https://github.com/alessio-palumbo/my-portfolio/blob/master/assets/figma.png
[1]: http://mattfarley.ca/
[2]: https://imdev.in/
[3]: https://www.figma.com/file/BLuitzqbxPz0GFZoilBZrrgu/Portfolio
[4]: https://codepen.io/AlessioP/pen/VzoQVm