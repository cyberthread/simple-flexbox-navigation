# Flexbox Navigation
This exercise is a basic introduction to Flexbox layout. 

In this exercise you will:
- Implement features in code based on prototypes.
- Practice using Flexbox to layout the main navigation at larger screen sizes.
- Practice using media queries to implement a responsive design.
- Practice using positioning to make more sophisticated interactive elements.

## Tasks
- **Preview**: Make sure you know what your goals are! 
	- Review the prototypes in the screenshots folder. You should notice that the layout of the navigation changes between screensizes and that when the "skip to main content" anchor is in focus it is visible, but otherwise is not visible on the screen.
	- Review the HTML code so that you understand the structure of the document. You will not need to edit the HTML code.
	- Go through the CSS and make sure you understand what all of the existing code does. 
		- *Add comments to leave yourself notes about what particular properties do*. I recommend using your developer tools to explore what is already present. You can toggle properties on and off to see what they do.
- **Style header for screens larger than 38rems**: You'll notice that the narrow screen design has already been implemented. Your job is to implement the design change that occurs at 38rems. 
	- You'll first make a two column design that includes the site identifier on the left and the nav on the right. These columns will not be equal.
	- Next you'll make sure the navigational list items are in a single row. *Hint: you'll have a flexbox inside of a flexbox.*
- **Style Skip to Main Content Anchor**: Although you can definitely leave the "skip to main content" on the screen all of the time (it actually adds to the accessibility) you can make it visually hidden until the anchor is in focus and still meet WCAG 2.1 AA standards. We'll do this in this exercise so that you can learn more about positioning.
	- When the "skip to main content" anchor is in focus, you'll want to place it in the top left of the screen *using positioning*.
	- When the "skip to main content" is waiting for interaction (the :link state) place the anchor off screen *using positioning*.