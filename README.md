# Using Zillow to Estimate Damages from Natural Disasters
## Project for General Assembly's Data Science Immersive
By:  José Cacho (),  Chuck Dye (), Zach Morris (), Julian Oquendo ()

## Objectives
Develop a formula, using existing pricing databases, to calculate property damage caused by natural phenomena within a specific zip code or area. 

## Code Walkthrough (What's Under the Hood)
As described in the attached notebook, the project operates with little and fairly simple code:
- The initial function determines the impact zone, in kilometers, of a specific natural disaster (hurricane, flood, fire), while also measuring the impact area of the specific disaster. 
- This function additionally receives a specific zip code determine the impact location. 
- A secondary function calculates the average value of properties within this zipcode. The function also determines the type of natural disaster.
- Finally, the function returns the expected value of the areas affected by the natural disaster. 
- Code build and maintenance by Chuck Dye, as of April 24, 2019. 

## Product
asl;dfkasodfjas; App in dev adsfkl;jadsflfdksa;

## Conclusions
Although the product works, the source where we are receiving the information for zip code pricing structures last updated its unit pricing in 2012. We can commit additional, and true to life information with additional resources, as receiving API and individual values from sites like Zillow or housing sets were limited. 

## Links and Sources
- Templates from Corey Schafer's github page and code were used in building web apps. https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Flask_Blog
- The 'uszipcode' python library from DC-based programmer Sanhe Hu: https://pypi.org/project/uszipcode/ served as the project's main library to determine the code. 
- 
