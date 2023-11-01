# dmit1530-lab-03

## Lab 03: Toggle Navigation With Drop-Down Menu

**Weight**: 5% of your final grade

---

## Instructions

Clone a copy of this repository to your device so that you can develop it locally. When you finish, make sure to push your latest commit to GitHub Classroom. 

For this Lab, you will create a website with a fully responsive navigation. In the smallest (mobile) view, the user should be able to show and hide (toggle) the navigation with the click of a button. In the largest (desktop) view, the user should be able to hover or tab over a dropdown menu. 

---

## The Build Methodology

Start by writing all of your HTML for ``index.html``. Remember to fill out all of your ``<meta>`` element information.

Next, you will need a ``<header>``. 

Inside of your ``<header>``, you'll need a first-level heading, your logo, and a ``<nav>`` with three drop-down menus. These menus should be structured as follows: 

   level one heading content: Adoptable Floofs &amp; Fur Babies

    1. Adopt
        - Kittens & Cats
        - Puppies & Dogs
        - Bunnies
        - Small Animals
        - Reptiles
        - Adoption Process & Fees
        - Adoption Application
    
    2. Foster
        - Why Foster
        - How Fostering Works
        - Foster Application
    
    3. Who We Are
        - The Team
        - Join Our Team
        - News & Blog
    4. FAQ

    5. Donate

Because of the different states and layouts of your navigation menu, you will need a number of wrappers and helper classes (ex. .inner-container, .wide-flex, and .flex-container).

The skeleton of your code should look something like this:

```HTML
	    <header>
        <div class="inner-container wide-flex">
            <div class="flex-container">
                <!-- First-Level Heading Here -->
                <div class="menu-icon">
                    <!-- Controller Icon Here -->
                </div> <!-- end of .menu-icon -->
            </div> <!-- end of .flex-container -->
            <nav>
                <ul class="main-menu">
                    <!--  -->
                </ul>
            </nav> 
        </div> <!-- end of .inner-container -->
    </header>
```

### CSS
Begin with universal styles and helper classes, your mobile view, any classes necessary for your toggle menu and JavaScript, and finally your media queries. Please note, that you only need 1 media query and your content should stop growing at some point on large (desktop) screens.   

## JS
Be mindful of your CSS and the class names that you gave to specific elements when using the toggle script that we learned during our hamburger menu demo. 

**Note**: please focus on functional styling first then aesthetics second.

## Marked on
1. 2 marks - On small screens, hide and show the menu smoothly by adding the Javascript and setting the special class in your CSS.
2. 1 marks - screen reader text is used to hide the logo heading.
3. 2 marks - Research at least two (2) new CSS properties on MDN. Please list the 2 researched CSS properties in a CSS comment and explain how they work/what they are doing. These properties should be ones that we have not covered in class. 

When you have chosen the properties you'd like to use, add them to your page. In order to make them work, you may add additional elements to the `<main>` area, including text and/or images.

Some ideas include:

* animation
* backdrop-filter
* filter
* mix-blend-mode
* transform
