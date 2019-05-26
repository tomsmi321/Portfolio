# Portfolio Project


## Links
- URL: https://thomas-smith.netlify.com
- GitHub: https://github.com/tomsmi321/Portfolio
- Figma: https://www.figma.com/file/Nz1V5rBLiaS4tMzStv7hEs23/Portfolio-design?node-id=0%3A1

## Description
### Purpose
This portfolio was designed as a personal online channel to market myself as a software developer to potential employers as well as providing a means to showcase content to anyone else I wish to connect with. It is designed to provide some simple information about myself, showcase projects I have completed, and give people a way to get in touch. It was completed as part of a project for the Coder Academy Diploma of IT over a two week period. The site is built entirely from scratch using HTML and CSS. This portfolio demonstrates my general approach to coding and design which is to keep it clean and simple.

### Functionality
My portfolio website was designed to be basic and straight forward, with space used  to carefully highlight important points. The minimal layout is intended to make navigation and use of the site easy for the user. I designed both a desktop and mobile version using CSS grid for responsive design whilst limiting the use of media queries. High contrast was used on many of the pages to make things pop visually. Color was generally used sparingly and to add interest on interaction with site, for example shapes changing color on hover, or for a call to action in the contact form. 

### Sitemap
My site consists of five pages all accessible from a single page scroll. The user can use the header or the up/down toggle navigation located in the bottom right of each respective page in order to transit to whichever page they wish. The following pages make up the site:
-Header: navigation
-Home: landing page with logo
-About: overview of myself
-Projects: a list of projects I have worked on
-Skills: a list of my software dev skills
-Contact: a form for people to get in touch and links to my Linkdin, GitHub and Codepen.

### Screenshots
![figma-board1 2019-05-26 at 15 45 26](https://user-images.githubusercontent.com/48931725/58377910-805b4880-7fcd-11e9-82b8-7ebb51f919b3.png)
![mobile 2019-05-26 at 16 55 53](https://user-images.githubusercontent.com/48931725/58378438-39725080-7fd7-11e9-80c0-507b66c21f60.png)



### Target Audience
The intended audience is anyone that wants to reach out to me and communicate regarding web development. The most likely people to view it would be future employers and clients.

### Tech Stack
The site was entirely coded in HTML5 and CSS3. No Javascript was used on the site as this was a requirement, though In the future I may use javascript to add some further animations. I often have decent design ideas in my head but I have never had any experience with the Adobe Suite or photo editing tools in general. Such tools often have a steep learning curve so I was pleased to find the online editing tool Figma which was a breeze to use and incredibly powerful in facilitating my design.
CSS grid was used to produce a responsive site and I found grid areas to be a great way to visually represent the site within the code itself as well as making adjustments and changes straight forward. The form section uses an API from formspree to forward contact information directly to my gmail account. Git and GitHub were used for version control and the site as a whole was deployed through Netlify. 

## Design Process and Brainstorming
## Concept formation 
I have always appreciated a minimal design aesthetic and how design itself translates to functionality and real value for the user, rather than merely an extra layer on top of the core features. Having said that, in my previous roles, my job has usually been figuring out how something should work on a high level not what it should look like. Having to get my hands dirty with the visual design was a real challenge especially for something as personal as my own site. Some of the Jen Simmons videos featured in class showed her reproducing an old piece from a 20th century German typographer named Jan Tschichold using CSS grid. The design really resonated with me and I used this as a starting point. I developed two pinterest boards shown below. One with minimalist 1920s and 1930s typography and other monochromatic shapes/tones and another with bright neon colors that I would use to add visual interest and make key elements pop. After looking at a multitude of sources I decided that I wanted to create something abstract, monochromatic with some splashes of color, high-contrast, typographic and line based with no photo content just svg. I felt this would suitable represent my personal brand.

![bold_types 2019-05-14 at 16 14 44](https://user-images.githubusercontent.com/48931725/58377939-cd3f1f00-7fcd-11e9-84d4-b7388fbfd6ef.png)
![color_flash 2019-05-14 at 16 13 41](https://user-images.githubusercontent.com/48931725/58377959-f65faf80-7fcd-11e9-982e-e640723947a9.png)


### Logo
I was initially going to use only rectangular shapes for the logo and for the site in general but decided that it was too bit harsh aesthetically. I started experimenting with circles and lines in different configurations drawing some inspiration from past typographers and visual artists. I settled on a desktop design in figma for the logo but then took some time to find a mobile version that still looked good and maintained the essential design features.


### Colour Scheme and Fonts
I began with just black and white but found that the contrast was too much and it looked too basic. I spend 2 hours just picking a shade of black and a shade of white that I thought would work. I was really happy with my picks on these colors despite the time it took. I also used the site coloors.com to auto generate some color combinations that would work using a color picking tool on some of my pinterest boards as a starting point. In Figma I assessed several fonts for all letters and characters. I ultimately settled on Raleway for the heading on the home page and Roboto for everything else. With the Roboto font I used a 3 different font weights to manage emphasis.
![color_pallet_1 2019-05-14 at 23 49 29](https://user-images.githubusercontent.com/48931725/58377981-5f472780-7fce-11e9-9bf8-2086d724971b.png)
![fonts 2019-05-26 at 15 54 54](https://user-images.githubusercontent.com/48931725/58377997-a503f000-7fce-11e9-905c-ea9ac64fd245.png)



### Wireframes
I mocked up both a desktop and mobile design in figma for the site which formed the basis of my design. Though constant tweaking caused some divergence from the final product the essential elements were maintained. The pages alternate from white to black for high contrast between content sections and are all accessible on a single scroll. I created the logo for the homepage and the background for the projects section in figma and then exported them as svgs to implement in my site. I also used lines on the figma wireframe to help me place elements in CSS grid.

### Usability Considerations
I really wanted a site that was easily navigable and each section clearly defined and readable. Since I was using high contrast colors and lots of empty space I think this helped. I initially has some issues with the mobile version as things were getting too crammed up and ruining the aesthetic. Using grid and media queries to move elements around as the screen resized helped me fix this.


### Project Plan and Timeline
We were given a little under two weeks to complete the project which was a reasonable amount of time. I laid out a basic plan to get to an MVP with lorem ipsum fill text within one week then spend the following week tweaking the site and writing the content. I spent an entire day on ideation and figuring out what my influences and idea sources were going to be. This included building my pinterest board, color pallet, and looking at other sites and visual artists. After this I spent one and a half days designing my wireframe in figma most of which was done in a single night. My idea was to keep it simple and have no photos and no color gradients. This saved me considerable time as elements were easy to place and alter in figma on each design iteration. From here I spend the next two days coding the site, starting with clearly working out my grid for each page and getting the basic structures in place using fill text. After the two days I had a basic site that worked pretty well for desktop but was a bit qwirky in mobile. I had several days where I had to do other work so I put it on the shelf for a while. The final two days I spent hours in Chrome's inspect element tool adjusting my grids and writing CSS media queries to get the mobile version right. Finally I was happy with it and I set to writing all the content which I completed in around half a day. By breaking the tasks down into sections and focusing on the MVP I was able to manage time effectively and get everything done with time to spare.
![Trello 2019-05-14 at 10 55 51](https://user-images.githubusercontent.com/48931725/58378009-cf55ad80-7fce-11e9-9c71-23664f8daffb.png)


### Challenges
Building a site from start to finish really brought together all things in HTML and CSS that I had not fully understood. The biggest challenge was just getting all the elements to line up correctly while simultaneously being responsive. Finding out why something is behaving unexpectedly can be a real time drain. A lot of it there is no write and wrong and they are simply design tradeoffs so it takes time to work through even though the task itself is straightforward. I would just like to say a big shout out to CSS Grid areas, I appreciate you even if others don't, you really made my life much easier.


### Further Enhancements
In the future I would like to add more animations. Also I am still on the fence about the projects page background art. I may go back and change this in the future.

## Short Answers
### Describe key events in the development of the internet from the 1980s to today (max. 150 words)


The internet is best described as a network of networks. Research organizations and government agencies initially saw the benefit of connecting their own computers to one another to facilitate the transfer of information and communication. The issue was that as these private networks grew and gradually became more interconnected it became apparent that standards were required to make these networks efficiently talk to one another. This problem was partially solved in 1982 with the introduction of TCP/IP for APRANET one of the largest networks at the time and gradually became the standard for all networks as it remains today. Engineers solved the communication problem through utilizing layers of abstraction to route packets on networks and ensure they get to where they need to go. In 1990 a scientist at CERN names Tim Berners-Lee developed HTML which enabled referencing between pages possible and forms the basis of web pages today. CERN later introduced the world wide web, which made an enormous amount of information accessible to the public for the first time. This created an unstoppable move as more people build on this structure. Web search engines emerged as a way for pages to be indexed and searchable which became increasingly necessary with the amount of content growing exponentially. Today it is questionable whether the original vision of the internet being an open and free information highway has really being fulfilled. With large private organizations centralizing data and acting as gatekeepers conversations around the trade offs between convenience and privacy along with issues such as net neutrality are at the forefront of debate in the 21st century.


### Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers (max. 150 words)

The basis of a webpage is HTML. Users will employ a web browser to retrieve and display information on their device via a unique address called a URL. The URL will be in human readable form on most occasions (eg. www.google.com). Every computer on a network has a unique address called an IP address. The URL is resolved to a IP address via the Domain Name Sever (DNS). A DNS maintains a log of a huge number of computer addresses and maps the URL to an IP. The advantage is that the individual computer does not need to maintain the vast and ever changing log of addresses required to rout information. Rather it will communicate with a DNS. A DNS may not always know where to send the packet to directly so it may forward it on to another DNS and so on and so forth until the packet arrives at its destination.


### Reflect on one aspect of the development of internet technologies and how it has contributed to the world today (max. 150 words)

One recent development in the web has been the proliferation of connected mobile devices. This has totally changed how people interact with each other. We can now communicate at a more rapid pace and in a more efficient manner than ever before. It affects how we live and how we work both for good and for bad. In this way its impact cannot be overstated. The internet and computers more generally started out as a tool for only those that could afford access. In many ways mobile has helped to democratize the internet by making information and the access to it truly affordable. This is rapidly rushing towards the interconnection of all our devices in an IOT of things world.




