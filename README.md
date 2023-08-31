# PIZZERIA PALERMO

"Welcome to Palermo Pizzeria, your go-to destination for authentic Italian-style pizzas in the heart of Montreal. 
This project aims to provide customers with a taste of Italy through a variety of classical, meat, vegetarian, and seafood pizzas. 
I built this website so that the whole world could take part of this wonderful pizzeria.


Add an image of the finished site here. I like to use [amiresponsive](https://ui.dev/amiresponsive) to get an image of my site on all device sizes, and amiresponsive allows you to click links on the page and scroll, so each device can show a different element of your site.

Add a link to the live site here, for Milestone 1 this will be the GitHub Pages Link from when you deployed the site.

GITHUB PAGES

[You can view the GitHub code pages here.]<https://github.com/Jesper941/Pizzeria>

## CONTENTS

- [PIZZERIA PALERMO](#pizzeria-palermo)
  - [CONTENTS](#contents)
  - [User Experience (UX)](#user-experience-ux)
    - [User Stories](#user-stories)
      - [Client Goals](#client-goals)
      - [First Time Visitor Goals](#first-time-visitor-goals)
      - [Returning Visitor Goals](#returning-visitor-goals)
      - [Frequent Visitor Goals](#frequent-visitor-goals)
  - [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
  - [Features](#features)
    - [Home Page](#home-page)
    - [Menu Page](#menu-page)
    - [Contact Page](#contact-page)
    - [Future Implementations](#future-implementations)
    - [Accessibility](#accessibility)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Local Development](#local-development)
      - [How to Fork](#how-to-fork)
      - [How to Clone](#how-to-clone)
  - [Testing](#testing)

## User Experience (UX)

### User Stories

Here are different kinds of user stories.

#### Client Goals

* The client's primary goal is to showcase their authentic Italian-style pizzas and convey their passion for delivering high-quality and delicious pizzas to their customers.
* The client may want to provide an easily accessible and well-organized online menu to help customers explore their wide range of pizza offerings, ingredients, and flavors.
* The website aims to attract more customers to the physical pizzeria by providing essential information, such as location, contact details, and a reservation option.
* To allow visitors to communicate with Palermo Pizzeria with an enquiry or to reserve a table at the restaurant
*  The website's design, color scheme, and content can reflect the pizzeria's brand identity and convey a sense of warmth, tradition, and authenticity.
* To be able to see and do all of the above on any device, whether a mobile phone or a desktop computer.

#### First Time Visitor Goals

* I want to see what pizzas they have.
* I want to see what kind of vegetarian options they have.
* I want to get in touch with the pizzeria about reservations or questions.
* I want to navigate the site with ease.
* I want to find out where the pizzeria is located so that i can visit it.

#### Returning Visitor Goals

* I want to try different pizzas with different toppings.
* I want to see if they have added anything new to their menu.

#### Frequent Visitor Goals

* I want to find the number to the pizzeria easily so i can call and order my favorite pizza right away.
* I want to be able to recommend Palermo Pizzeria to all my friends.

---

## Design

### Colour Scheme

The colour scheme for the website came with inspiration from the colors of the italian flag. The cream colors fit in well with the theme and they kind of came to me right away as i was imagining the completed website in my head. 

![Palermo Pizzeria colour palette](assets/images/colorpalette.png)

### Typography

I used the standard font style for the majority of the site.

For the footer i chose the "Arial" font family, specifically for the text next to the social media links.

Font Awesome was used to make the icons for the social medias in the footer.

---

## Features

The website is built up by 3 pages in total. The home menu that holds some history of the start of Palermo Pizzeria and it's owner Guiseppe Fontana. The menu page where all the pizzas and their respective toppings are showcased. And lasty a contact and find us page where you can book a reservation, ask questions and get directions to the pizzeria.

Each page has the phone number for the pizzeria in it's header.
Each page also has a nav bar that's easily useable.

### Home Page

The home page has a text container where all the history about the restaurant and it's owner is contained.
The page is responsive and adapts after screen size.

### Menu Page

The menu page is built up of four different div blocks that are responsive to the screen size. It starts with 2 menus per row and as the screen size shrinks, it goes down to showing only 1 menu and it stacks in columns instead.
It has four ordered lists, one in each div, with all the different options in them. 
Each list item has a paragraph nested inside them where the toppings are added.
There is a "Back to the top" button at the bottom that is nested inside an anchor with the #top href.

### Contact Page

The contact page consists of two different div blocks with a container nested inside them.
The first container one holds a table with the opening hours and also a form where you can send reservation requests and questions.
The second container holds the iframe with the location of the restaurant.
There is a "Back to the top" button at the bottom that is nested inside an anchor with the #top href.

### Future Implementations

- Adding prices to the pizzas
- Adding images of the pizzas
- Making the home page a bit more welcoming. Add some photos of the restaurant and of Guiseppe.
- Implement a order feature for pickups.
- Create logins with order histories.

---

### Accessibility

I have tried to ensure the site has been made as accessible as possible by:

- Using semantic HTML such as section, header, footer, main, etc.
- Using alt attributes on images where available.
- Using colours that are easy on the eye and fits in well together.

---

## Technologies Used

### Languages Used

I used HTML and CSS to build this website.


### Local Development

Instructions on how to fork and clone the project.

#### How to Fork

1. Log in (or sign up) to Github.
2. Go to the repository for this project, <https://github.com/Jesper941/Pizzeria>
3. Click the Fork button in the top right corner.


#### How to Clone

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, kera-cudmore/TheQuizArms
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

You can find all of the testing done in the <https://github.com/Jesper941/Pizzeria/blob/main/TESTING.md>

















1. i started by making a base for an HTML document with a few added features such as metadata for "keywords" and "description". 
i also created the base for my header and navbar.

1. I finished my header and styled it to my liking. 
I used "https://www.w3schools.com/" for help when styling the .text-container part so that the transparent container with my header text would look great.


3. i did some inline styling on the navbar to give the different links different colors.
I used this website to learn how to do it properly: https://stackoverflow.com/questions/10143357/how-to-make-these-buttons-not-appear-as-blue-links

4. i added some text-stroke to the paragraph to give it some more depth
i learned it here: https://css-tricks.com/adding-stroke-to-web-text/

5. i fixed the styling in style.css due to a problem with the text container piling up on the navbar because i was using an absoute position on the text container. Problem is now solved

6. I added lists to the "menus.html" file and i have started filling in the lists with pizzas.
I also added CSS styling for the menu blocks for more accessability.

"https://fontawesome.com/icons"

changed button CSS to be more responsive to the screen size

i've been sitting for over 2 hours revamping the CSS styling to make everything more responsive to screen sizes by adjusting width &, margins and i even added different stylings for smaller screen sizes using the @media screen and max(width) element.

<!--<ol type="1">
    <li>Margherita<p style="font-style: italic;">Mozzaerlla, Tomato Sauce, Basil</p></li>
    <li>Vesuvio<p style="font-style: italic;">Smoked Italian Ham, Tomato Sauce, Mozzarella, Oregano</p></li>
    <li>Calzone (baked)<p style="font-style: italic;">Smoked Italian Ham, Tomato Sauce, Mozzarella, Oregano</p></li>
    <li>Gondola (baked)<p style="font-style: italic;">Minced Meat Ragout (Minced Beef with Vegetables), Tomato Sauce, Mozzaerlla, Parmesan, Oregano</p></li>
    <li>Hawaii<p style="font-style: italic;">Smoked Italian Ham, Pineapple, Tomato Sauce, Mozzarella</p></li>
    <li>Bolognese<p style="font-style: italic;">Minced Beef, Onion, Garlic Cloves, Tomato Sauce, Mozarella</p></li>
    <li>Capricciosa<p style="font-style: italic;">Smoked Italian Ham, Mushrooms, Hard-boiled Egg, Tomato Sauce, Mozzarella</p></li>
    <li>Quattro Stagioni<p style="font-style: italic;">Divided into quadrants: Artichokes, Olives, Ham, Mushrooms with Tomato Sauce and Mozzarella.</p></li>
    <li>Pepperoni<p style="font-style: italic;">Pepperoni, Onion, Bell Peppers, Jalapeno, Tomato Sauce, Mozzarella</p></li>
    <li>Africana<p style="font-style: italic;">Pineapple, Banana, Curry, Smoked Italian Ham</p></li>
</ol>

<div class="menu-block" style="background-color: rgba(255, 253, 238, 0.823);">
    <h2 style="color: green">Meat Pizzas</h2>
    <hr>
    <ol start="11">
        <li>Diavolo<p style="font-style: italic;">Spicy salami, Red onion, Mozzarella, Tomato sauce, Oregano, Parmesan</p></li>
        <li>Ciao Ciao<p style="font-style: italic;">Pork Fillet, Onion, Fresh Garlic, Béarnaise Sauce, Mozzarella</p></li>
        <li>Amante Della Carne<p style="font-style: italic;">Smoked Italiam Ham, Italian Sausage, Bacon, Oregano, Tomato sauce, Mozarella</p></li>
        <li>BBQ Chicken<p style="font-style: italic;">Grilled chicken, Red Onion, BBQ Sauce, Mozarella, Cilantro</p></li>
        <li>Spicy Sausage<p style="font-style: italic;">Tomato sauce, Mozzarella, Spicy Italian sausage, Bell peppers, Onions, Jalapeños</p></li>
        <li>Mediterranea Carne<p style="font-style: italic;">Mozzarella, Lamb, Red onion, Tomato, Feta cheese, Tomato Sauce.</p></li>
        <li>Italian Sausage and Peppers<p style="font-style: italic;">Tomato Sauce, Mozzarella, Italian Sausage, Bell Peppers, Red Onion</p></li>
        <li>Pepperoni and Jalapeño Burst<p style="font-style: italic;">Tomato sauce, Mozzarella, Smoked Italian Ham, Pepperoni, Jalapeño</p></li>
        <li>Hawaiian BBQ Bacon<p style="font-style: italic;">BBQ sauce, Mozzarella, Smoked Italian Ham, Bacon, Pineapple</p></li>
        <li>Meatball Mania<p style="font-style: italic;">Tomato sauce, Mozzarella, Meatballs, Roasted Garlic, Basil</p></li>
    </ol>
</div>

<div class="menu-block">
    <h2 style="color: green; text-decoration: underline black;">Vegetarian Pizzas</h2>
    <hr>
    <ol start="21">
        <li>Margarhita<p style="font-style: italic;">Cheese, Tomato Sauce, Basil</p></li>
        <li>Quattro Formaggio<p style="font-style: italic;">Gorgonzola, Taleggio, Pecorino, Mozzarella, Tomato Sauce, Oregano</p></li>
        <li>Florenzi<p style="font-style: italic;">Zucchini, Mushrooms, Broccoli, Asparagus, Cherry Tomatoes, Mozzarella, Tomato Sauce, Oregano, Parmesan</p></li>
        <li>Tartufone<p style="font-style: italic;">Tomato Sauce, Mozzarella, Artichoke, Olive Oil With Truffle, Taleggio, Parmesan, Oregano</p></li>
        <li>Verde<p style="font-style: italic;">Creme Fraiche, Mozzarella, Zucchini, Pesto, Roasted Pine Nuts, Arugula, Parmesan</p></li>
        <li>Karl-Johan<p style="font-style: italic;">Karl-Johans Mushroom, Mushrooms, Mozzarella, Tomato Sauce, Oregano</p></li>
        <li>Fungo Medley<p style="font-style: italic;">Sautéed Portobello, Cremini, Shiitake Mushrooms, Caramelized Onions, Fresh Thyme, Mozzarella Cheese</p></li>
        <li>Caprese Classico<p style="font-style: italic;">Sliced Tomatoes, Fresh Basil Leaves, Arugula, Balsamic Reduction, Mozzarella, Tomato Sauce</p></li>
        <li>Spinaci Ricotta<p style="font-style: italic;">Sautéed Spinach, Dollops of Ricotta Cheese, Roasted Garlic, Sun-Dried Tomatoes, Mozzarella Cheese</p></li>
        <li>Fungo Al Tartufo<p style="font-style: italic;">Truffle Oil-Infused Mushrooms (Portobello, Shiitake, Truffle), Caramelized Onions, Fresh Thyme, Fontina Cheese</p></li>
        <li>Nutella<p style="font-style: italic;">A dessert pizza with the classic Nutella filling</p></li>
    </ol>
</div>-->


