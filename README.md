# Reed Sutton Photography
## #landscape #nightscape #lighttrails 
## https://fotoreedus.github.io

### Photography links:
https://sites.google.com/site/marclevoylectures/home
https://www.reddit.com/r/photography/comments/5jrwbu/i_am_a_full_time_photographer_because_of/

### Plan:
Package up LR presets and sell  
Package up 500px bot (+others?) and sell  
Package up stock image bot and sell

## Product Page:
Options:
1. https://designmodo.com/create-product-page/
2. https://dev.solteq.com/2016/12/02/building-a-responsive-product-grid-with-css-flexbox/
3. https://tympanus.net/Blueprints/ProductGridLayout/
#### Final: https://github.com/CodyHouse/3d-items-quick-view

#### Product Box:  
https://www.photoshoptutorials.ws/photoshop-tutorials/drawing/how-to-create-your-own-product-mockup-box-in-photoshop/3/


## @HighCaptures Landing Page:
Options:
1. https://www.brutalist.design/brutal-design-1/
2. https://onepagelove.com/trumpet
3. https://d2zav2bjdlctd5.cloudfront.net/theme_preview/lucy_pro/home.html
4. https://designsmaz.com/demo/akad-free-digital-agencies-html-template/
5. https://freehtml5.co/demos/air/  ***
6. http://themeinthebox.com/demo/mountain-king-html/
7. https://markups.io/project/kindle/

Ideas:
1. Free book 1st - popup - follow social media - funny statement - "If you unfollow me later.. I have a special set of skills acquired over a very long career, I will find you... actually no I won't but just don't do it k." 
2. Paid book 2nd

Resource Compilation:
- http://www.altitude-university.com/resources
- http://dronelawjournal.com/

Content Strategy:
1. Aggregate and use ML to que up best drone shots week by week. 
2. Post 9 at a time, 4 from aerial/geometry, the rest not aerial.  

## Customizations:

Mobile Menu and Overlay Adapted from:  
[1] https://codepen.io/riogrande/pen/gbXxdx  
[2] https://www.w3schools.com/howto/howto_js_topnav_responsive.asp

Title for Product Page; options
- https://codepen.io/JbvGaming/pen/CwJHK
- https://codepen.io/selcukcura/pen/OmYKJm
- https://codepen.io/jpI/pen/ayNwvz


# Troubleshooting

## Resolving CSS conflicts for different frameworks and sections of website:

---
Option 1: https://github.com/vic/prefix-css

Option 2:

You can't apply different stylesheets to different parts of a page. You have a few options:

The best is to wrap the different parts of the page in divs with class names:

<div class='part1'>
    ....
</div>

<div class='part2'>
    ....
</div>
Then in your part1 CSS, prefix every CSS rule with ".part1 " and in your part2 CSS, prefix every CSS rule with ".part2 ". Note that by using classes, you can use a number of different "part1" or "part2" divs, to flexibly delimit which parts of the page are affected by which CSS rules.

---

An external stylesheet is applied to whole html page. In order to apply different stylesheets to different portions, Firstly, the html page has to be divided into different sections using the html tag ( with each html div to be assigned a unique id or class) Secondly, the external stylesheet to be applied to each div has to be designed according to the id/class assigned to it

Example as explained above by Gaby aka G. Petrioli...
