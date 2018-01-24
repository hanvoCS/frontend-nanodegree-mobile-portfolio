# Mobile Portfolio 

In this project I need to optimize speed for this online portfolio website!
In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).


### Optimize PageSpeed Insight to become 90+ by : 
- Inline CSS.
- Insert `async` attribute to script source. 
- Append `media` attribute to the `print.css` link 
- Replace script code to the bottom.
- Delete the google font style. 

![Optimization speed for Mobile ](https://www.dropbox.com/s/gd350biqtmugwwq/pageSpeed1.png?dl=0)![Optimization speed for Desktop ](https://www.dropbox.com/s/ngvjp5pdv5gxzql/pageSpeed2.png?dl=0)



### Optimize pizza.html in terms of :  

#### 1. Frame Rate

Optimize the code in  `views/js/main.js`  to make  `views/pizza.html` render with a consistent frame-rate at 60fps when scrolling.

#### 2. Computational Efficiency

Time to resize pizzas is less than 5 ms using the pizza size slider on the `views/pizza.html` page
