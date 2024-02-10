![natours homepage](https://github.com/MMattoss/Natours-project/assets/120864278/2873d94b-e83c-4d44-b3ed-13d1c1a07bff)
# Natours

This is a project from the course Advenced CSS & SASS taught by Jonas Schmedtman. The main goal here was to learn how to use SCSS and also a few (quite a lot actually) advanced CSS techniques.
[Live website](https://mmattoss.github.io/Natours-project/)

## Key characteristics and things I've learned:
- ### Project achitecture:
  - The SCSS files are organized using the CSS 7-1 architecture, wich consists of creating 7 folders for all the SCSS files and importing all of then to 1 main.scss file.
    
  - The main.scss file is the only file that will be compiled into pure CSS.
    
  - The 7 folders and what files goes inside of each one:
    - Base: Contains styles that define the basic styling of HTML elements, such as typography, resets, and global styles.
    - Components: Contains styles for reusable UI components, such as buttons, cards, navigation bars, etc. Each component should have its own partial file.
    - Layout: Contains styles for defining the layout structure of the website or application, such as grids, headers, footers, and navigation.
    - Pages: Contains styles specific to individual pages or views in the application. Each page or view should have its own partial file.
    - Abstracts: Contains Sass utility and helper files, such as variables, mixins, functions.
    - Vendors: Contains third-party CSS or Sass files, such as libraries or frameworks, but this one was not used in this project.
      
  - Semantic HTML was used to help organize and structure all the sections properly, helping reuse some components and making it match all the SCSS files.
    
  - Along with the HTML the BEM achitecture was also used to name all the elements classes, wich consists of naming the elements based on their parents name and their modifier(one of my favorite features), ex.: .navigation__item (parent __ child), .heading-primary--main (element -- modifier).

    
- ### The website:
  - The website itself uses a lot of transitions, animations, transforms, a grid system designed from scratch and a lot more. I'll talk about the main features and things I liked the most:

    - Font-size: Setting the global font-size to 62.5% makes it so every 1rem is equal to 10px. This change allows you to use rem units and write media queries A LOT easier since you just have to adjust this number up or down deppending on the devices width. Easily my favorite feature.
      
    - Responsiveness: the site uses a desktop first approach, it has 4 main breakpoints: phone (600px), tablets on portrait mode (900px), tablets on landscape mode (1200px) and big desktop screens ( > 1800px). Using these values in combination with the power of mixins it's possible to make an awesome media query mananger that can be included along the parts of the site that needed to be change.
   
    - Reusable components and mixins: by knowing what the final design is going to look like, we are able to make base components that can be used multiple times along the entire page and write mixins to position, size, and space everything correctly. I've struggled a lot with this in the past, very happy that I learned this technique.
   
    - Obscure CSS properties and selectores: there are SO many properties and selectors that were used in this project I would never know existed. They range from positioning and skewing properties to different filters, coloring and so much more. Really amazed to see how powerful CSS really is.


For sure there's a lot more to this project that I wasn't able to cover in this README like custom npm scripts, responsive images, cubic-bezier functions, etc. But hopefully I was able to give you a good insight about the overall project. It was a blast coding and learning everything used here. Thank you Jonas for the amazing lessons.
    - 
