# tStyle
Python CSS injecter.



*tStyle* is a great css injecter.
It allows you do anything that you could do in normal css!
**NOT** just changing colo(u)rs, but also keyframes, web kit tools and everything!
It saves into a *.css* file so you don't have to write everything again.


# Creating a theme
You can create a theme easily due to tStyle's ease!
```python
import tStyle as ts

black = ts.Theme()
black.style()
black.description({
    "name": "Black",
    "author": "Your name",
    "date_made": "Date",
    "about": "Desc."
})
```
*That's it!*


# HOW TO INJECT
1. Go to website
2. Open inspect element
3. Make a new tStyle theme
4. Copy the css file contents and add to main css file
5. Enjoy!

# Before/After
![image](https://storage.googleapis.com/replit/images/1612141857411_bb4932e3a37ea06144b4ff096764af80.png)
<< This is the code.

**BEFORE**
![image](https://storage.googleapis.com/replit/images/1612141906045_72878d65fdf0c4a0699237bd3087ae7a.png)

**AFTER**
![image](https://storage.googleapis.com/replit/images/1612141951251_42f4f787748eed6ba5416b726bad3621.png)



# FUTRUE UPDATES
Add a **GUI**?
Auto inject using js
Save injections with js bookmarks
