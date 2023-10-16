# Table of Contents
1. [Introduction][introduction]
2. [Overview][Overview]
3. [Website][Website]
4. [Considerations and Decisions][consideration]
5. [Challenges][Challenges]
6. [Acknowledgments][Acknowledgments]
7. [Improvements]
8. [Code Snippets][Code]
9. [Screenshots][Screenshots]

# Arthub
 Arthub is an innovative online art gallery that serves as a platform for artists worldwide to showcase their artwork. 
 It offers a curated collection of diverse art pieces, ranging from contemporary paintings to digital masterpieces. 
 The platform allows art enthusiasts and collectors to explore and acquire remarkable artworks directly from the artists themselves.

## Overview

As a team, we created Arthub as our final project for the Introduction to Web Development course to apply the knowledge and skills we acquired. 
I specifically contributed by making the header, footer, and the about page to ensure a cohesive and well-structured user interface. 
Arthub was designed for a broad audience, including both established art collectors and those new to the art scene.

## Website
You can access the website hosted on Github Pages at [Arthub](https://wellfc.github.io/Arthub/).

## Considerations and Decisions

As a team, we faced a range of considerations and made important decisions during the development of Arthub:

- **Learning and Application:** Our primary consideration was applying the web development skills learned in the course to create a functional website. We made decisions regarding the use of HTML, CSS and web technologies.
- **Design Consistency:** Ensuring a consistent design throughout the website was a primary consideration. We made design decisions that matched the overall look and feel of Arthub.
- **User Navigation:** The header and footer were designed to facilitate easy navigation for users, with clear links and options.
- **About Page Content:** The about page aimed to provide a concise yet comprehensive description of Arthub's mission and purpose. I made content decisions to convey this effectively.

## Challenges

Developing Arthub as a team project was both challenging and interesting. We found it challenging to coordinate our efforts, but it was also rewarding to see how different components came together. Contributing to the header, footer, and about page presented both challenges and interesting aspects. It was challenging to ensure that these components integrated seamlessly with the rest of the website and maintained design consistency. However, I found it interesting to work on the user interface aspects, ensuring that users could easily navigate and learn about the platform's mission.

## Acknowledgments

I would like to acknowledge the following individuals for their contributions:

- Andre Murilo Cantuaria Muniz:

  Created the home and the gallery page. Contributed to the overall visual design of the website.
- Rosa Maria Nunez Rivera:

  Created the contact page.

## Improvements

In the future, we plan to introduce several improvements to Arthub:

- **Enhanced Search and Discovery:** Implement advanced search and discovery features to help users find artworks more easily based on their preferences.
- **User Feedback:** Implement user feedback mechanisms to collect input and suggestions for enhancing the platform.
- **Header and Footer Customization:** Enhance the header and footer to provide more flexibility for future additions and changes to the website.

## Code Snippets

**Navigation Menu**

_HTML_

```html
<nav>
    <ul>
        <li><a href="./index.html">Home</a></li>
        <li><a href="./discover.html">Discover Arts</a></li>
        <li><a href="./about.html">About us</a></li>
        <li><a href="./contact.html">Contact us</a></li>
    </ul>
</nav>
```

_CSS_

```css
nav {
    flex: 5;
}

nav ul {
    list-style-type: none;
    font-size: 0;
}

nav ul li {
    display: inline;
}

nav a {
    display: inline-block;
    line-height: 60px;
    padding: 0 15px;
    font-size: 16px;
    color: var(--app-dark-gray-bg);
    text-decoration: none;
    transition: background-color 0.2s ease-in-out;
}

nav a:hover {
    color: var(--app-white);
    background-color: var(--app-blue-bg);
    line-height: 60px;
}
```

**Search Bar**

_HTML_

```html
<form class="search-bar">
    <input type="text" placeholder="Search">
</form>
```

_CSS_

```css
.search-bar {
    line-height: 60px;
    flex: 1;
}

.search-bar input[type=text] {
    width: 250px;
    padding: 10px 0 10px 32px;
    border: 1px rgb(255 255 255 / 0.15);
    background: rgb(0 0 0 / 0.1) url(../img/search.png) no-repeat 10px 10px;
    background-size: 18px;
    font-size: 14px;
    border-radius: 50px;
}

.search-bar input[type=text]:focus {
    border: 1px solid var(--app-blue-bg);
}
```

## Screenshots

[_Header and footer_](#header-and-footer)

![Arthub Header and Footer.jpg](https://github.com/Wellfc/Arthub/blob/main/assets/img/Arthub%20Header%20and%20Footer.jpg)

[_About page_](#about-page)

![Arthub About Page.jpg](https://github.com/Wellfc/Arthub/blob/main/assets/img/Arthub%20About%20Page.jpg)


[introduction]: https://github.com/Wellfc/Arthub#arthub
[Overview]: https://github.com/Wellfc/Arthub#overview
[Website]: https://github.com/Wellfc/Arthub#website
[consideration]: https://github.com/Wellfc/Arthub#considerations-and-decisions
[Challenges]: https://github.com/Wellfc/Arthub#challenges
[Acknowledgments]: https://github.com/Wellfc/Arthub#acknowledgments
[Improvements]: https://github.com/Wellfc/Arthub#improvements
[Code]: https://github.com/Wellfc/Arthub#code-snippets
[Screenshots]: https://github.com/Wellfc/Arthub#screenshots
