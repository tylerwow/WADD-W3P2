# Week 3 Practical 2 - Flexbox and Grid

In this practical you will gain hands on experience with the CSS flexbox and grid modules.

## Stage 1: Implementing Flexbox

In VS Code, open the starter code folder called “stage1” and run index.html in Chrome using the Live Server.

For each of the exercises in this stage, you will write flexbox CSS to recreate the layouts shown below. The HTML files and global CSS (main.css) is provided in the starter code. 

index.html shows the default layout with the basic styling provided by main.css. The other HTML files are identical except for links to additional stylesheets. **You should only edit the stylesheet associated with each exercise and only use flexbox (no inline-block, no float, no position etc).**

These exercises go beyond what was covered in class. You can find all the information you need here:[https://css-tricks.com/snippets/css/a-guide-to-flexbox/ ](https://css-tricks.com/snippets/css/a-guide-to-flexbox/ )

### Exercise 1.1: Put the squares on one line
Edit **stage1/styles/exercise1_1.css** to make the green squares appear side by side with no gap between them. 
Check your edits by viewing stage1/exercise1_1.html in Chrome (you should be able to just click the link from stage1/index.html).

![Screenshot for Ex1.1](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise1-1.png)

You should only need to set `display` to `flex`. Your job is to figure out which element(s) need the property.

### Exercise 1.2: Reverse the squares
Edit **stage1/styles/exercise1_2.css** to make the green squares appear side by side in _reverse order_ with no gap between them. Square 9 should be against the left edge of the window.

![Screenshot for Ex1.2](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise1-2.png)

### Exercise 1.3: Put the squares in a grid
Edit **stage1/styles/exercise1_3.css** to put the squares in a 3 x 3 grid as pictured. The grid should be in the horizontal centre of the window. You can set the dimensions of the container element if needed. There is a particular flexbox property that allows you to set the wrapping of items in a container element.

![Screenshot for Ex1.3](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise1-3.png)

### Exercise 1.4: Put the squares in a grid 2
Edit **stage1/styles/exercise1_4.css** to put the squares in a 3 x 3 grid as pictured. The grid should be in the horizontal centre of the window. The key difference between this exercise and the previous one is the order of squares 4-6. You can set the dimensions of the container if needed. The `order` property will be helpful.

![Screenshot for Ex1.4](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise1-4.png)

### Exercise 1.5: Make a step layout
Edit **stage1/styles/exercise1_5.css** to put the squares in a stepped layout as pictured. The key flexbox property is `align-self`. You will also need to give the container element a height and change the margin of some of the items in the container.

![Screenshot for Ex1.5](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise1-5.png)

## Stage 2: Implementing Grid

In VS Code, open the starter code folder called “stage2” and run index.html in Chrome using the Live Server.

Similar to stage 1, you'll write CSS to recreate the layouts shown below but this time you will use the CSS Grid module. The HTML files and global CSS (main.css) is provided in the starter code. 

index.html shows the default layout with the basic styling provided by main.css. The other HTML files are identical except for links to additional stylesheets. **You should only edit the stylesheet associated with each exercise and only use grid (no flexbox, no inline-block, no float, no position etc).**

All of these exercises are focused on putting elements in specific places in a grid so you should only need to use properties we covered in class. Don't worry about making the proportions of each element match those in the screenshots--proportions will vary depending on your browser window size. You may find this reference handy:[https://css-tricks.com/snippets/css/complete-guide-grid/ ](https://css-tricks.com/snippets/css/complete-guide-grid/ )

### Exercise 2.1: Put the rectangles in a grid
CSS Grid is for making grids! Edit **stage2/styles/exercise2_1.css** to put the blue rectangles in a 3 column by 2 row grid. 
Check your edits by viewing stage2/exercise2_1.html in Chrome (you should be able to just click the link from stage1/index.html).

![Screenshot for Ex1.1](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise2-1.png)

You should only need to set `display` to `grid` and specify the rows and columns. Your job is to figure out which element(s) need the property and choose the best units for the rows and column sizes.

### Exercise 2.2: Make the rows different sizes
Use the same grid you created for 2.1 in **stage2/styles/exercise2_2.css** but this time make the rows different sizes. 

![Screenshot for Ex2.2](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise2-2.png)

### Exercise 2.3: Create a header and footer-style grid
Edit **stage2/styles/exercise2_3.css** so that elements 1 and 6 span the full width of the grid, while the other elements are distributed equally. 

![Screenshot for Ex2.3](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise2-3.png)

### Exercise 2.4: Spanning rows and columns
Edit **stage2/styles/exercise2_4.css** to recreate the layout below. Try to add additional CSS to as few elements as possible!

![Screenshot for Ex2.4](https://github.com/IM-WADD/Week3Practical2/blob/main/assets/exercise2-4.png)

## Optional Stage 3: Creating a Responsive Layout Using, Grid, Flexbox, and Media Queries
The York University Press webiste that you've worked on for a few practicals is exactly the sort of layout that could benefit from a combination of flexbox and grid alongside media queries. Make a new copy of the York University Press website you created in last week's practical. It is OK if you didn’t quite finish the last practical yet; start with what you have. 

The goal of this stage is to replace any use of the inline-block approach with flexbox and/or grid while maintaining the same visual appearance. There is no detailed guidance for this stage because it's about applying what you've learned to a realistic scenario. A sample solution will be provided after the practical.

## Optional Stage 4: Update Your Portfolio Layout
Open up the portfolio site that you last worked on in previous practicals. Use either or both layout approaches we have covered this week to create the layout of your site. Be sure to check how your portfolio looks on small devices and use media queries to make your site responsive. 
