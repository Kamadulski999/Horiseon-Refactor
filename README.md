# 01 HTML, CSS, and Git: Code Refactor

* In this assignment, the primary task is Search Engine Optimization and increasing accessibility of the Horiseon homepage. While refactoring the website, the code will be made more efficient as well as re-written for long term sustainability.

# HTML
* Added "Horizon Homepage" as page title
* Added Alt"" tags to all images. As all images are decorative, the Alt tags are empty
* In "content" section changed class="search-engine-optimization" to an id in order to restore page navigation
* Replaced <div> with <nav> and <section> tags where appropriate
* Removed extraneous classes in Content and Benefits sections as css formatting for each class will be combined into one style that applies across the entire section

# CSS
* re-arranged selectors to match flow of HTML 
* removed .header {list-style-type: none;}
* removed <p> font-size: 16px
* removed font-style from individual sections and added them as .primary-font{} and .secondary-font{} classes that apply across the entire page
* combined classes with similar formatting in content section to create a new selector .content div{} that maintains consistent formatting across all divs 
* combined classes in benefits to create .benefits div{}






