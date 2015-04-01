##GR8WORKSHOPS: A GUIDED DISCUSSION ABOUT TEACHING AND DIVERSITY IN THE GROOVY COMMUNITY

###Presentation for [Greach](http://www.greachconf.com)
####Madrid, Spain 
#####10 April 2015 15:00

As the demand for skilled developers continues to increase worldwide, many alternative education models are trying to step up to fill these positions. Some of these new programs including code schools, dev boot camps, and weekend training courses. Some programs are available to individuals looking to enhance or build skills outside of their own workplace and others programs even cater to individuals with no programming experience at all. Are these initiatives the right approach for teaching Groovy? Let’s discuss.
The approximately 20 minute talk portion of this session will explore the findings from various Gr8Ladies and Gr8Workshops programs as well as provide insight into the recruitment of diverse groups in education and the workforce. The remainder of the session is a guided discussion with questions related to various models of programming education.

Follow along at [http://jlstrater.github.io/gr8workshops-discussion](http://jlstrater.github.io/gr8workshops-discussion)

===============
## Slides

Based on the [opi-reveal-template](http://github.com/objectpartners/opi-reveal-template)

## Dependencies
* Node
* Bower
* Grunt Cli

##Getting Started
* Run `npm install` to install node dependencies
* Run `bower install` to install client-side dependencies

##Grunt Commands
* `grunt assemble`
  * Minify/uglify the javascript source and css
  * Compiles jade
  * Stages everything in the dist folder
* `grunt run`
  * Starts a server running on port 8000
  * watches for changes on project files
  * When files change, the assemble task is re-run and
  * Livereload triggers browser update on assemble task completion
* `grunt publish`
  * Publishes slides to GitHub pages
  * Uses git subtree merge to merge the contents of dist into the gh-pages branch
