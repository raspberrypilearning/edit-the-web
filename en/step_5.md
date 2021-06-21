
## Make it fancy with CSS

If HTML tells the browser how to set out the structure of the website and **what** you should see, CSS tells the browser **how it should look** when it comes to colours, sizes and other artistic choices. HTML was *never* designed to change the way a page looks, only what content was included on the page. 

Having stylesheets which you can save in different files means that you can quickly chop and change what **any** website looks like, simply by using a different stylesheet. 

In this step, you're going to edit the included CSS stylesheet, called ```style.css```.

### CSS Rules
Every **rule** in CSS is made up of two parts: the **selector** and the **declaration**.
![CSS Rule](images/css-rule.png)

The selector links to the HTML element you want to style. In this example, it's any first level header: h1

The declaration block contains one or more declarations separated by semicolons. In this example we are making the font blue, and 12 pixels in size. (In the stylesheet here, we've left lines between each declaration, but you don't need to - it just makes it a bit easier to read!) 

You should see some comments at the top of your CSS file and before each rule explaining what it is. Notice that instead of using ```<!--->``` to create comments like we do in HTML, in CSS we use ```/*``` and ```*/```.  

--- task ---
Open the ```style.css``` file in Trinket or your text editor and see if you can work out which **rule** belongs to which tag! (You can switch back and forward between your HTML and CSS files to compare.) How can you tell which is which?
--- /task ---

### CSS Colours
One of the main things CSS is used for when formatting websites is adding splashes of colour to different elements. Using the rules in your CSS stylesheet, you can change the colours which are applied to each different element, just by writing the name of the colour you want in the declaration.

You can use [this list](https://www.w3schools.com/cssref/css_colors.asp) to find colours for your website. When changing values in your stylesheet, you can use either the **colour name** or the **hex code** to define what colour you want. Remember to include the capital letters in the right places!  

![CSS colour examples PaleVioletRed, PapayaWhip and PeachPuff](images/sample-colours.png)

--- task ---
Pick a colour now and apply it to your ```body``` rule. This will make the background of your entire page change colour!
--- /task ---

You can also edit the **text** on your site using the CSS stylesheet. 

You can change the colour of the text itself using the  ```color``` declaration, and the background behind the text using ```background-color```.

You can use ```text-align``` to choose whether your text is ```left```, ```center``` or ```right``` aligned.

--- task ---
Go through your CSS stylesheet now changing the colours in the different rules until your page looks the way you would like it. 
--- /task ---

--- save ---
