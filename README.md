# evote-movie-2019

## About
This is a sequence of progressive enhancements, taking a static HTML site into an authenticated modern MVC website

The website is about movies and user voted stars

## Progressive enhancement 

1. Starting point
    - a flat HTML website with hardcoded links

2. Change HMTL to PHP
      - change all `.html` file extension to `.php` 
      - in every page change the navigtion links to files ending with `.php`

3. Add Front Controller structure
      - move all display pages into folder `/templates`
      - move images and css into new folder `/public`
      - add Front Controller script `/public/index.php` to test for GET variable `action`
      - change all navigation links to the form `/index.php?action=<PAGE>`
         - e.g. `/index.php?action=about` for link to about page

4. Header and Footer
      - remove common header and nav content to `_header.php`
      
      - remove common footer content to `_footer.php`
      
      - add `require_once` to all pages to read in common header and footer
      
      - NOTE: we have lost title page name and current page nav indicator - we'll fix this soon :-)

5. Current page name in HTML title
        - controller functions to pass values
        
6. Current page indicated in nav bar CSS
        - controller functions to pass values
        
1. List details from array

1. List details from array of objects

1. List details from array of objects from DB

1. Form for comments (into DB)

1. OO front controller and controllers

1. Twig templates

1. Admin login and CRUD

1. Sticky forms if validation error

## Links to completed verions


1. https://github.com/dr-matt-smith/evote-movie-2019-01-basic-html
2. https://github.com/dr-matt-smith/evote-movie-2019-02-all-files-dot-php
3. https://github.com/dr-matt-smith/evote-movie-2019-03-front-controller
4. https://github.com/dr-matt-smith/evote-movie-2019-04-common-header-footers
5. https://github.com/dr-matt-smith/evote-movie-2019-05-values-passed-to-templates




