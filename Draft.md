# Rapid scalable Stylesheet Architecture // RSSA

###The problem
Every Web project has specific needs, but there are a few that are common across all applications.

Every application must be:

- Easy to maintain or scale
- Light
- Efficient

On top of been compliant with these requirements, some applications needs to even been cross 
browser compatible and very often needs to be designed, coded and deployed on a time record. 

When it comes to coding a page and setting your CSS properties you will face a few situations. 

- you want the CSS properties to inherith from eachother, but at the same time you want to avoid conflicts (undesired inheritance). 

- You want it to look the same across different browsers, but you don't want to use vendor prefix. 

- You want your CSS file to be light, but you don't want to use shorthand notation. 

- You want your code to be easy to read and organized but you don't want to use long tail specification. 

The solution relies in the way we structure our projects. Breaking our files into modules will help us to 
get separation of concern between our UI elements.
