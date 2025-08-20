# Personal Website - Arianna 
This is my personal website, originally made through the Girls Who Code (GWC) Pathways program, and this was the first website I ever made! It is essentially an introduction to who I am and what I have done, coding & outside, in terms of my projects. I built this site because I am learning how to code, developing as a programmer, and building new things, and I wanted to have a platform to showcase them and show who I am to the world. I used HTML and CSS for this website, and learned how to code in both languages while building. The initial project requirements for my page are below and were completed with the help of GWC video instruction and structured assignments, and the rest I did on my own, teaching myself via Google searches. 

### Initial Project Requirements
- Include one home HTML page that's all about you!
- Include a navigation bar that is included on all your website's pages.
- Include one portfolio HTML page to showcase your projects.
- Have all text, image(s), links, and/or videos on the page contained within appropriate HTML elements.
- Include alt text for every image in your website.
- Apply styles to text, image, and navigation bar elements using CSS rules.
- Use classes and/or IDs to style CSS elements.

### Things I Added
- The header image and overlay text (I learned how to use divs for this! And in CSS, I used absolute positioning and transform: translate() for the first time when building this feature)
- Positioning the nav bar up top (I found a tutorial that showed me what the z-index was)
- Creating a gradient background (learned this had to be done through the background-image tag and learned how to use linear-gradient() for this via YouTube tutorial)
- Housing text and images within a box (more divs!)
- Creating a gradient border for said box (had to stack two background images, one with a gradient and one white, on each other and clip them to specific parts of my box; I learned very quickly that gradient borders are not compatible with rounded corners)
- Stacking images on each other and positioning them in a box (I learned what flexbox was here, and the tags associated with it to align my images to flex-end and keep them on the other side of my text)
- Not really an addition, but definitely something I worked a lot on: positioning all my elements (no new knowledge needed, but I definitely had to understand and apply margin & padding, as well as the float tag and transform: translate())

### What I Struggled With & What I Learned
I struggled with A LOT. Some of these features, although they look super simple, took me ages to work out and debug. 
  For the header image, it took me a while to figure out how to make it look visually appeasing given my image had different dimensions than would fit in the space I wanted. I figured I wanted to crop the image bottom to fit my height, but it took me a while to figure out that object-fit: cover was the tag that would give me the effect I wanted. 
  Creating the gradient border for my box took ages, because at first I was using border-image: linear-gradient() which was not compatible with border-radius and meant my border kept disappearing! I kept decomposing this element (taking out all the text, deleting border-radius and other tags, and building back up) before figuring out I had to stack two background images instead and clip them to the border-box and content-box to get the effect I was looking for. 
  When placing my flex images in the box, they wouldn't go into the box space provided and would instead stick out towards the bottom of the webpage. Moreover, the images wouldn't be aligned vertically, instead being placed diagonally. After a while, I found that there were two issues, 1) my container had a fixed height which the flex-container exceeded, and I needed to change this to min-height to fit everything, and 2) I had to align the flex images using align-items. 
  Even after these larger elements were placed, it took me ages to figure out how to space everything: the main box on the portfolio page would stick to the header and leave no space, but when I added a margin, the background gradient got deleted (it turned out I needed to add padding to the background gradient itself); the text would stick outside the box and be positioned oddly, so I changed the parameters of the text classes; and the images themselves in the flex-container were sized oddly, one small and the other large, needing me to adjust the height and width parameters and change them from px to % when necessary. 
  But I learned SO MUCH from this!! I learned what works and what doesn't, and when it works (see above), I learned how to use so many elements in HTML & CSS for this, I learned how elements are positioned on a webpage and how to adjust them ti fit my vision, and I learned how to persevere even when my website preview looks visually terrible. 

This project is one I am submitting to the Athena Award!

[![Athena Award Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Faward.athena.hackclub.com%2Fapi%2Fbadge)](https://award.athena.hackclub.com?utm_source=readme)
