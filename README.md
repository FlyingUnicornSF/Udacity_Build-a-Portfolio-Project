# Udacity_Build-a-Portfolio-Project
Build a Portfolio Project in Udacity FullStack Course 

It is based on the design mock up that was provided from the course. https://storage.googleapis.com/supplemental_media/udacityu/2655898586/design-mockup-portfolio.pdf

## Use of Flex in responsive web design 

The biggest challenge was using flex for this project for different size of windows. 

```
@media only screen and (max-width: 500px) {
  .project_container {
    flex-direction: column;
  }
  .project a {
    font-size: 2.5vw;
  }
}
```

The neatest thing I've learned was making colors into varilables and use that instead of putting font color or line color everywhere. this is much neater way to keep the color scheme. Of course when you want to adjust the color ever so slightly, you need come to only this code to change all of them. 
```
:root {
    --blue-color:#02b3e4;
    --dark-grey-color: #2d3c49;
    --light-grey-color: #7d97ad;
}
```
neat right? 

and using google fonts. They have so many fonts! I sent way too much time on looking through pretty fonts.
```
<link href="https://fonts.googleapis.com/css?family=Lato:100" rel="stylesheet">
```
This line goes into HTML file and not css.  The website has good instruction how to use it. 

## Why responsive web design?
We live in the world with different size of devices that can see our websites and it is important to deliver the content in user friendly manner. Besides, it looks just plain ugly when things don't fit right. 

## Installation

Download the entire project folder onto your machine keeping the folder structer. 

### License
still have to figure this out... 
