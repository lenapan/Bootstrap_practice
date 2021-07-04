# Unit 4 Challenge: Code Bootstrap Portfolio

Last week you coded a portfolio using HTMl & CSS. This week your going to code a portfolio using Bootstrap's grid system along with HTML & CSS.

Bootstrap is a common front-end framework used by developers to speed up the prototyping and development process. When creatively customized bootstrap has almost unlimited potential!

## Instructions

1. To get inspired spend a few minutes googling: bootstrap portfolio websites.

  - Or check out [this link](https://colorlib.com/wp/free-bootstrap-4-portfolio-website-templates/)

2. Customize the provided Bootstrap Portfolio Template wireframe in Figma.

    - [Bootstrap Portfolio Template wireframes](https://www.figma.com/file/NMUebR5Dp2KAyc5Lqvbesv/Bootstrap-4-UI-Kit-Templates) 

  - Make sure to right-click then duplicate the file to your Figma account.

   - When you are creating a wireframe, you should begin to think about the grid system you will have to create. 

3. Create the folder structure for the webpage.

   - Create a folder structure.

     - Create a `index.html`.

     - Create a `css` folder.

       - Inside create a `style.css` file.

   - Create an `images` folder.

       - Place all your images in this folder.

4. Create the layout using Bootstrap's grid system and components. Include the following sections.

  - Create a website that matches the layout given.

  - Refer back to the content outline your created from Unit 3 challenge.

  - Use Bootstrap's Grid system, components, and utility classes as well as custom CSS to recreate the given webpage.

    - The website should include the following bootstrap components:

    - A Navigation bar
    
    - A navigation menu at the top. Feel free to use bootstrap's navbar or create your own.

    - Include links that are applicable to your portfolio.

    - A hero section

        - A jumbotron featuring your picture, your name, and any other information you'd like to include.

    - A work section

      - A section displaying your work in a 2x2 or 1x4 grid. 

        - If you need to use placeholder image use: https://placehold.co/ 

      - Use bootstrap cards for each project.

        - The description should give a brief overview of the work.

      - Each project will eventually link to your class project work!

    - A skills section

      - List out the skills you expect to learn from the bootcamp.

    - An about / contact section.

      - An "About Me" section in the same row.
    
    - A footer section (optional).

      - All hyperlinks should have a hover effect.

      - All buttons should display a box shadow upon hover.

5. Push files to GitHub and publish your site using GitHub Pages.

   - Create a new repo for your webpage.

   - Add the following files to the repo.

   - Publish your page using GitHub pages.

   - Visit your published page.

6. Make your website responsive (bonus). 

- Incorporate the following Bootstrap's responsive grid classes in order for the grid to match your wireframe at each screen size:

     - `col- `

    - *Bonus: Use the following responsive classes / breakpoints*

       - `col-sm-`

       - `col-md-`

       - `col-lg-`

- Incorporate media queries into the CSS for your portfolio site.

   - Use media queries to make further adjustments to your site at different screen sizes.

   - At a minimum, you must:

     - Adjust the font size in the jumbotron at each screen size.

     - Remove the navigation bar at a breakpoint of your choosing.

   - Feel free to add additional media queries as you desire.

7. Use Font Awesome to include icons on your portfolio site (bonus).

   - Include the CDN for Font Awesome in your HTML: https://cdn.fontawesome.com/ 

   - Add icons to the HTML to match your large wireframe design.


### Helpful Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/)

- [Responsive Web Design - How to Create Media Queries](https://www.youtube.com/watch?v=5xzaGSYd7jM)

- [Media Queries 101 by CSS Tricks](https://css-tricks.com/css-media-queries/)

- [Media Query Documentation](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

- [Github Pages Guide](https://pages.github.com/)

  - Choose "Project Site" and "Start from Scratch" to get correct instructions.

- [GitKracken Support](https://support.gitkraken.com/)

### Hints and Considerations

- You might want to change margin and padding for different screen sizes.

- The appearance of a new row can be forced by using `<div class="w-100"></div>`. Then, you can choose the screen size to display this element by changing the display property. For example, the code below will not display the `w-100` class until hitting a screen size above 992 px.

  
```CSS
  @media (max-width: 922px){
    display: none;
  }
```
  - You can read more about using the `w-100` class in the [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/layout/grid/#column-breaks).

---

## Copyright

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

