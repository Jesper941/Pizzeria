1. i started by making a base for an HTML document with a few added features such as metadata for "keywords" and "description". 
i also created the base for my header and navbar.

2. I finished my header and styled it to my liking. 
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


