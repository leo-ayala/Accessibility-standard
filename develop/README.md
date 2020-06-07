## Week 1 Challenge

This homework assignment was about altering or refactoring the code of a website for a marketing company in order to meet their accessibility standards. 

# Website
https://leo-ayala.github.io/Accessibility-standard/ 

# Alterations

In this file we needed to show our ability to change an HTML file to make the website more user friendly and to increase the accessinility to standard that is easy for everyone. First by adding 'alt' elements to the images allows a screen reader to be able to identify what the picuture is without acutally seeing the picture. 
There was also a linking error for the 'Search Engine Optimization' that was easily remedied by creating an 'id' element that matched the 'href' tag. 

**Before**
``` ruby
<div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
```
**After**
```ruby
<div id="search-engine-optimization" class="search-engine-optimization">
            <img src="../Images/search-engine-optimization.jpg" class="float-left" alt="search engine" />
            <h2>Search Engine Optimization</h2>
```
<img src="./Images/ScreenCapture.png" alt="Horiseon" style="max-width:100%;">
