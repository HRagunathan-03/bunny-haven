
# Bunny Haven

The primary goal of this website is to find a new home for rabbits that have been abandoned, rabbits that have been rescued, and rabbits that need to be rehomed.

Creating an informative, clear, and easy to navigate website will suppport the primary goal.

## User Stories

- As someone who is thinking of adopting a rabbit, I would like to be able to navigate the website intuitively, on any device, so that I am able to find the information I need quickly.

- As a rabbit lover that is looking to adopt, I would like a dedicated page for rabbits that are looking for a new home, so that I can find my forever bunny easily, and adopt it!

- Once I have found a rabbit to adopt, I would like to contact Bunny Haven to start the adoption process.

- As someone looking to rehome their rabbits, I would like to be able to find the location and contact information of Bunny Haven, so that I can get in touch or visit.

### Design Choices

- **Colours** The shade of pink across the website was chosen as it evokes a calm, loving feel which is the feeling that adopting a rabbit would give.   
The shades of green that were used, compliment the pink, while also tying in with the scenes of nature found in the images on the website.

- **Fonts** Sofadi One was used for the main headings as it has a soft and rounded feel, just like rabbits. Quicksand was chosen for the main text content as it was easy to read and inviting.

- **Styling** When making styling decisions, the main focus was on providing a clean, easy to navigate website for positive user experience.  
High-quality images were used throughout the website to improve user experience.
The image carousel and testimonial cards on the Homepage were used to draw the users attention.  
The cards for the Adopt page were chosen to display the available rabbits in a neat, concise layout.

## Testing

### Manual Testing

- Tested carousel on the Homepage. Autoplay is working. The previous/next controls and indicators are all working correctly.

- Tested responsiveness across different screen sizes and noriced that there were some alignment issues on the "Adopt a bunny" section. 
*Fixed this issue by targeting the carousel-adopt id in the media queries.*

- *Added fixed-top class to the navbar on all pages to improve the user experience.*

- Tested the links on the navbar. This showed that when pressing the Rehome link, the fixed navbar is hiding the "Rehome a bunny" section. 
*This was fixed by adding padding-top to .section style on CSS.*

- On smaller screens, clicking on the burger icon opens the dropdown, but hides the page content.
*This was fixed by using the Javascript code provided for the Boardwalk Games project, to close the navbar once the user has clicked the link.*

- Testing the Adopt page showed that the cards in the "Meet the bunnies" page are not centered on smaller screen. This issue is yet to be fixed.

- Checked "Get in touch" form to ensure that HTML validation is working.

### Automated Testing

- Testing with Lighthouse on DevTools showed the following scores:
1. Performance - 78 (Incognito mode shows a score of 90)
2. Accessibility - 100
3. Best Practices - 100    
      
- Any remaining performace issues are yet to be fixed. 

- Checking the HTML code with the W3C HTML validator showed no issues.

- Used the Autoprefixer tool to add prefixes to the CSS code.

- Checking the CSS code with the W3C CSS validator showed no issues.



### Sources

1. Code Institute Boardwalk Games Project - This project was used continuously as a template to build my project with. 
2. [Bootstrap](https://getbootstrap.com) for navbar, cards, carousel.
3. [Canva](https://canva.com) to generate all of the images and the logo using the AI generator.
4. W3C HTML and CSS validators, Autoprefixer tool, DevTools/Lighthouse for fixing any encountered issues.
5. [GitHub](https://github.com) and GitHub pages for creating the project and deployment.
6. [Markdown](https://markdownguide.org) for help with markdown syntax.
7. [Imagecolorpicker](https://imagecolorpicker.com/) for picking colours for the website.
8. [WebAim](https://webaim.org/resources/contrastchecker/) for checking the web accesibility of the chosen colours.

#### Project created by Hamshini Ragunathan
[Bunny Haven](https://hragunathan-03.github.io/bunny-haven/) - This is a link to the deployed project.


