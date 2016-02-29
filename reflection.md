###What did you learn about CSS padding, borders, and margin by doing this challenge?
-I learned a lot about padding, borders and margin. Padding is useful for moving elements in a more specific way than I thought, and I ended up using it a lot when trying to get things to line up correctly.

I used a bottom-border and top-border on my header and footer, respectively, to create a line between them and the body text. I also used a border-radius to alter what the edges of the header, footer, and image on my index page looked like, which is something I hadn't used much before but will keep in mind as a way to alter the shapes of objects non-permanently. 

Margin was very necessary to determine the 1000px diameter of my page. Using margin: auto was helpful in making sure it stayed centered. I otherwise mostly used padding to move things around, but plan to use margins as I add more images to my index page to make sure they sit correctly relative to one another.

###What did you learn about CSS positioning?
-Positioning was one of my more difficult areas to deal with. I had a lot of trouble getting things to go where I wanted to go and, ultimately, realized I was using the absolute position incorrectly. Absolute positioning will only work to move elements if the parent element is absolute or relative, and I didn't realize that my body wasn't absolute or relative. If the parent isn't one of these positions the object will be absolute in relation to the HTML and end up sticking to the left top corner of the page.

Ultimately I realized that I could let elements remain static with little changes in their positioning style more than I thought I could.

Fixed positioning with my headers and footers was one of my earliest decisions in wireframing, so I'm glad that it worked out easily.

###What aspects of your design did you find easiest to implement? What was most difficult?
-I think the easiest aspect to implement was getting the header and footer to stay on the bottom and the top of the page. I had an issue for a while where the body HTML was not emcompassing the entirty of the page but didn't notice this CSS was messed up, so a lot of my positioning of elements within the body ended up being more difficult than necessary until I realized this problem and fixed it.

###What did you learn about adding and formatting elements with CSS in this challenge?
-I ended up adding a lot of classes and ids to make sure I was very specifically targeting what I wanted to target in the HTML. I thought this was important since it was the default stylesheet- I didn't want to have similar elements on pages in the future that may be accidentally targeted because I used the same tags. I felt this was particula

A few other thoughts: I definitely spent more that four hours working on mostly the index page, and ended up feeling a bit burnt out and tired when formatting the blog index, so I plan on revisiting that in the future. I think at this point the structure of the page is much more solid, though, so it will be easier to position things where I want them to be.