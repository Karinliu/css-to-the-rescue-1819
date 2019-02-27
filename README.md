# My application
<img width="1280" alt="screenshot 2019-02-27 22 20 51" src="https://user-images.githubusercontent.com/32538678/53523794-04d92080-3ade-11e9-8a43-72bb4744ec1a.png">


## The assignment I used

The assignment that I have chosen is the Responsive restauraunt menu, see [here](https://github.com/Karinliu/css-to-the-rescue-1819/blob/master/assignments/menu.html)
 the raw link for starting my project.


## Two restrictions

The restrictions that I have chosen to use in my application are:
* Two colours
* No squares, no rectangles, no circles, no triangles


## How did I start?

Before I started with the assignment, I have made a design for the restaurant menu website. See below the design.
![first design-01](https://user-images.githubusercontent.com/32538678/53522678-37cde500-3adb-11e9-82d7-fd098d756b1d.png)


The interactions I wanted to use for in the design was: when the user click through the menu, the letters would fall in to the soup bowl.


#### Feedback
The feedback that I received on this design, was to look at more forms to use for in the design. I have also been told to look at the layout of the content. I had to make distinction between "important" and "less important" content. This would make the layout look like this:

| Element               | status of importance  |
| --------------------- |-----------------------|
| Restaurant name       | Important             |
| Navigation            | Important             |
| Titles of dishes      | Less important        |
| Price  of dishes      | Less important        |
| Description of dishes | Not important         |


## Making the application

### Main elements
Creating the application, I first started making the "main elements" which where the bowl and layout. Then I tried to apply a grid to the main element so the website will be responsive.

### Next step
The next step was to style the navigation. Because I could not use squares, rectangles, circles or triangles. I used the internet for inspiration.

I finally came up with the idea to create a rolling pin for the navigation.      
<img right="0" width="200" alt="screenshot 2019-02-27 22 22 04" src="https://user-images.githubusercontent.com/32538678/53523825-233f1c00-3ade-11e9-924d-c9106a58b0a2.png">

Because the navigation on mobile and tablet is a lot smaller, I have chosen to use a spoon as navigation.

After the navigation was made, I added a whisk (instead of chopsticks). To add interaction to the whisk and the text, I tried to add a scroll function on the text elements. *When text scrolls, move whisk and rotate text.*

##### It did not work...
To add this interaction, I tried to add a `class` to the body with `javascript`. But since the main of my design has a fixed position, the part that scrolled would never hit the top to fire class for the interaction. That's why I came up with the solution to add a click interaction.

### It works! What's next?
After that I have added the interaction in the navigation buttons, I wanted to use keyframes for in my application. since I have never worked with this before. In order to do that, I looked at keyframes on the internet. There I saw that the keyframes also can be applied on the stir. So I did that.

Thereafter I wanted to add an SVG animation. On the web there are many examples to create a SVG animation.

For in my own application I have chosen to create an angry chicken with a: `No mouse over me please!` bubble. See below the strip.
![chicken-01](https://user-images.githubusercontent.com/32538678/53525305-b9c10c80-3ae1-11e9-9759-e7472e653f23.png)



Here was also the problem  that mobile and tablet have less screen width to apply this design. For mobile and tablet I created a walking chicken. See here below:
![chicken-walk-01](https://user-images.githubusercontent.com/32538678/53525304-b9c10c80-3ae1-11e9-911e-d12f9d2e33e9.png)


## Feedback to add
The feedback I received, was to add a blob animation in the bowl. At first I tried to create a blob with javascript, and after that, I  tried to move a block back and forth for creating a wave. Since both cases were still quite difficult to work out, I tried something else. In the end I chose to make a block with different borders that keeps running 360 degrees continuously. :)

### More interaction to add
The last interaction what is added in the application, is a mouse move tracker. When the user moves with his mouse, the whole application becomes a bit darker and the navigation will give a glow effect. Because of the glowing effect, I try to trigger the user to click on it.

## Whishlist to add
What I would like to add in to this application is to apply more interactions and to use a smoother flow like `cubic-bezier` or `transitions`.

## Browser support
An another feature to add into this application is browser support. Now I only tested and worked in the `chrome` broswer as result that the app does not work properly in other browsers... :(

## Download and use my application

To see the project you can download or clone this document with the following command:

```
git clone https://github.com/Karinliu/css-to-the-rescue-1819.git

cd css-to-the-rescue-1819/app
```

to see the application, it is best to use the `chrome` browser.
