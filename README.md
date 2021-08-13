# 02 Advanced CSS: Portfolio

## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```


## My solutions for the Acceptance Criteria:

## HTML File

In the head of the html file I set standards for the page using meta elements. 
In the body for the file, I created a header that includes my name as well as an unordered
list for nav bar items.
Outside of the header, the body is composed of three sections. Each section corresponds to  
one of the nav items which are about me, my work, and contact me. 
In the about me section, I inlcuded a self picture and a brief paragraph describing myself. 
The my work section is made up of place holder images that will eventually contain my work once created.
The contact me section has an image as well as a linked unordered list of my email, linked in, and GitHub. 
I included a footer with the message "Thank you for visiting!"

## CSS File

I included a :root tag atop my css file to indicate 3 colors I would be using throughout the code.
In the header, I used CSS to change the font family and style of my name and nav items. 
I also used CSS to create an effect when hovering the cursor above each item. Once clicked,
the nav items link you to the corresponding section on the page. 
CSS allowed me to format padding and borders around each image and section. A bottom border 
separates each section as well. I used a flexbox to help position items on my page.
The images in the my work section are different in size with the first image being larger.
The images in this section also have links imbeded. The links don't go anywhere at this time as this 
section is placeholders. 
I used a media query at the bottom of the css file that changes the aspect and layout of the page when 
viewed from a smaller screen. 

