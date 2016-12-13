# stacks

> Drupal 7 Starter Theme by NASA Goddard Library.

## To Use

- Copy files to new theme folder
	- do not copy the directory so we don't accidentally bring over the git repo
- Rename stacks.info
- Search and replace stacks with your theme name
- Rename the theme folder to your custom theme name
  - theme names should get a year suffix
    - For example: sitename2015

---

> This theme is meant to serve as a starting point to build from rather than a parent theme to be used in child or sub theme building

---

-  You will need Node (see installation instructions here: https://nodejs.org) and Gulp (see installation instructions here: http://gulpjs.com/)
-  From the command line, cd into your new theme folder
-  Run "npm install"
-  Run "npm update caniuse-db"
-  Run "gulp"
-  To stop watching, use Ctrl+C

## Notes

### History

Stacks was started as a Sass starter theme by Abby Milberg at RepEquity. It was made open source and placed on github under the title of "Boom". It was then expanded by Mitchell Shelton and brought to the NASA Goddard Library.

### To do

- Flexbox (IE11 fixes)
- SVG Icons
- Clean up gulp file
- Review/Update Mixins and Extendables