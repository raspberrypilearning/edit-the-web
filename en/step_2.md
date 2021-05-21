## Make a website your own with HTML

In this project you're going to take a webpage that looks really boring and contains no interesting information, then change the HTML and CSS to make it way cooler. 

Before we start, pick a notable figure from computer science history you'll create your site about. 

We have provided some information on a few people here, or you are welcome to research another person who inspires you:
+ [Ajay Bhatt](https://en.wikipedia.org/wiki/Ajay_Bhatt) - Inventor of the USB standard (India)
+ [Alan Emtage](https://en.wikipedia.org/wiki/Alan_Emtage) - Inventor of internet search (Barbados)
+ [Radia Perlman](https://en.wikipedia.org/wiki/Radia_Perlman) - a.k.a. the 'Mother of the Internet', invented STP networking (USA)
+ [Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper) - Inventor of the compiler, US Navy programmer since WWII (USA)
+ [Katherine Johnson](https://en.wikipedia.org/wiki/Katherine_Johnson) - NASA Mathematician and programmer, subject of the film *Hidden Figures*. (USA)

--- task ---

If working **online**, open the [starter project](https://trinket.io/library/trinkets/609451ca1d){:target="_blank"} in Trinket.
 
If working **offline**, open the project [starter file](http://rpf.io/p/en/edit-the-web-get){:target="_blank"} in an offline text editor or coding IDE. 

You should see...
 
![starter project](images/starter-project.png)

--- /task ---

The two main languages used to create websites are HTML (which stands for **H**yper**T**ext **M**arkup **L**anguage) and CSS (**C**ascading **S**tyle **S**heets). In this project, we're going to look at what both of them do and how they work together to make interesting websites.

You'll notice that in the code window, there are lots of angular brackets: <> These denote the different **elements** that make up a website. 

HTML elements are made up of a **start tag**, some content you want to display and an **end tag**.

--- task ---

Take a look now at the code in the website **header** and see if you can identify the following elements:

+ The ```<!DOCTYPE html>``` declaration defines that this document is an HTML5 document
+ The ```<html>``` element is the root element of an HTML page, and ends at the end of the page with ```</html>```
+ The```<head>``` element contains meta information about the HTML page and ends at the ```</head>``` end tag
+ The ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab) and ends with the ```</title>``` end tag

--- /task ---

If you take a close look, you'll notice that the information contained within the ```<head>``` element isn't displayed on the page. It is mostly filled with information for your browser, to give it specific instructions on how to understand your code. 

We will include this information in every website we make. In this project, we'll only be looking at the **Title** from the information in the site header.

--- task ---
Change the title of your website now by editing the text between the two ```<title>``` tags.

You *could* write anything you want here, but we suggest you make it something about your chosen figure, so the browser tab shows what the page is about.
--- /task ---

### Website Body
Inside the ```<body>``` element under the header, we put all the other elements we want to be displayed. 

+ The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc. and ends at the ```</body>``` tag.
+ The ```<h1>``` element defines a large heading, with higher numbers making smaller sized headings, all the way down to ```<h6>```. It ends in a ```</h1>``` tag.
+ The ```<p>``` element defines a paragraph - what end tag do you think it has?

--- task ---
Change the **heading** of your site to be indicative of the information you're about to include. 

It might be the name if the figure you've chosen, or something more exciting about them that would draw your reader in.
--- /task ---

The main body of your website will be in paragraph text marked by ```<p>``` and ```</p>``` tags. 

In the main body of your website, you can see some text in the paragraph is grey.

If there is text within your paragraph that you would like to style differently, you can set some ```<span>``` tags around it and then change the CSS. 

--- task ---
Create a first paragraph introducing your inspiring figure, using ```<span>``` tags to highlight important information. 

Leave it ```DarkGray``` for now, we'll change the colour in the next step.
--- /task ---

### Lists 

Lists allow developers to group related information together. Lists can be unordered (like bullet points) or ordered (sequenced with numbers or letters). The tags for unordered lists are ```<ul> and </ul>``` and the tags for ordered lists are ```<ol> and </ol>```.


--- task ---
Put some of the interesting bullet points from your biography in a list on your website. You can use ```<span>``` tags inside lists to highlight specific text, which we can style in the next step. (We can also change the style and look of the bullets later, using CSS.)

--- /task ---
The last tag we're going to look at is the ```<img>``` tag. This tag allows us to add images to a webpage. 

Images are not actually 'inserted' into a web page as they would be in a document on your computer; images are *linked* to web pages using a URL. The <img> tag creates a holding space for the image you reference.

The <img> tag has two attributes that you *must* include:

```src=``` - Specifies the path to the image. This can be the URL of an image you search on the internet! (Right click the image and choose 'copy image address', then paste it in here)
```alt=``` - Specifies an alternate text for the image, if the image for some reason cannot be displayed.

---collapse---
---
title: Width and Height of images
---

You can also specify the ```width``` and ```height``` of an image in pixels inside your ```<img>``` tag like this:

```<img src="image.jpg" alt="My image" width="500" height="600"```>

You can also use CSS to change the size of your images in the next step.

---/collapse---

--- task ---
Add an image of your inspiring figure to your web page. You can use one of the included images above, or search for a new one and use the address you copy (using the method in the hint above).

--- /task ---

In the next step, we're going to look at the CSS stylesheet to make your website more exciting and colourful!

--- save ---