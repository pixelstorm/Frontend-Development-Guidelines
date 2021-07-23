# Frontend-Development-Guidelines
### SCSS & CSS
1. Use REMS for units and set the responsive scale on the html element.
2. Dont use @extend - it makes a mess in the css
3. Use CSS Grid and Flexbox for layout
4. Use a BEM CSS metholodgy - we use BEM to keep our html markup simple.
5. We dont use bootstrap or tailwind unless specified in the brief.
6. Dont use id's for css selectors. Only use ids for js
7. When deploying to production, compress your css files into one minified file
8. Avoid using inline css.
9. Create and use mixins to remain DRY and Modular. Use mixins to "separate the concerns". ie: A mixin to handle all "titles".
10. add helpful comments to your css for yourself and others 
11. Keep code organised by using Sass Maps for brand elements like typography and color. Use camelCasing for your sass map declarations.
12. Each Gutenberg block scss lives in its own self contained file. The scss file is named the same as the block name. This includes existing gutenberg blocks ie: paragraph, heading etc 
13. Dont use !important if its not 100% nessary. When using BEM your css is modulized and therefore no need to use !important


### js
1. When deploying to production, Compress your js files into one minified file
2. Dont use javascript to match height of boxes use flexbox for this

### slideshows
1. Use slick slicker https://kenwheeler.github.io/slick/ we use this as the team is familiar with it.
 

## Responsiveness
This is the most critcal part of the developement. The problem can be that the design is often delivered to you in only one size, 
The design needs to look the same at 1920 and 1440 resolutions.

### 1. Fluid typography mixin
One approach is to use: https://codepen.io/MadeByMike/pen/vNrvdZ 
Use https://codepen.io/MadeByMike/pen/vNrvdZ on more the just typography to archive a scalable design.

### 2. Using REMS for scalable typography
https://www.youtube.com/watch?v=RKQ-Z-__3P4

Obviously, Your a skilled developer and you have your own methods. the important thing is that the website remains in scale accross different desktop Monitor / laptop resolutions


1. Our points breaks, with mobile first standard:
   - 480px
   - 768px
   - 1024px
   - 1280px
   - 1440px
   - 1600px
   - 1920px
