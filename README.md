# evote-movie-2019

## About
This is a sequence of progressive enhancements, taking a static HTML site into an authenticated modern MVC website

The website is about movies and user voted stars

## Progressive enhancement 

1. Starting point
    - a flat HTML website with hardcoded links
    
    - https://github.com/dr-matt-smith/evote-movie-2019-01-basic-html


2. Change HMTL to PHP
      - change all `.html` file extension to `.php` 
      - in every page change the navigtion links to files ending with `.php`
      
      - https://github.com/dr-matt-smith/evote-movie-2019-02-all-files-dot-php

3. Add Front Controller structure
      - move all display pages into folder `/templates`
      - move images and css into new folder `/public`
      - add Front Controller script `/public/index.php` to test for GET variable `action`
      - change all navigation links to the form `/index.php?action=<PAGE>`
         - e.g. `/index.php?action=about` for link to about page
         
      - https://github.com/dr-matt-smith/evote-movie-2019-03-front-controller

         
4. Header and Footer
      - remove common header and nav content to `_header.php`
      
      - remove common footer content to `_footer.php`
      
      - add `require_once` to all pages to read in common header and footer
      
      - NOTE: we have lost title page name and current page nav indicator - we'll fix this soon :-)
      
      - https://github.com/dr-matt-smith/evote-movie-2019-04-common-header-footers


5. Current page name in HTML title
        - controller functions to pass values

      - https://github.com/dr-matt-smith/evote-movie-2019-05-values-passed-to-templates

6. Current page indicated in nav bar CSS
        - controller functions to pass values

      - https://github.com/dr-matt-smith/evote-movie-2019-06-style-variables-passed-to-templates

7. List details from array

      - https://github.com/dr-matt-smith/evote-movie-2019-07-movie-list-from-array

8. Movies list from a Repository class

    - https://github.com/dr-matt-smith/evote-movie-2019-08-movie-repository

9. List details from array of objects

    - https://github.com/dr-matt-smith/evote-movie-2019-09-movie-objects

10. Move controller functions into a controller class

    - https://github.com/dr-matt-smith/evote-movie-2019-10-functions-into-controller-class

11. List details from array of objects from DB

    - https://github.com/dr-matt-smith/evote-movie-2019-11-database-movie-data

12. Page to insert new movies into the datbase

    - https://github.com/dr-matt-smith/evote-movie-2019-12-create-new-movies

13. Links to delete movies from the database

    - https://github.com/dr-matt-smith/evote-movie-2019-13-delete-from-database

14. Link and form to EDIT movies

    - https://github.com/dr-matt-smith/evote-movie-2019-14-edit-form

15. List CHEAP movies - custom SQL method in Repository class

    - https://github.com/dr-matt-smith/evote-movie-2019-15-custom-sql-in-repository
    
16. Login to protect the database CRUD

    - https://github.com/dr-matt-smith/evote-movie-2019-16-login-protect-crud
    
1. Twig templates

1. Admin login and CRUD

1. Sticky forms if validation error



## Testing

Examples of Unit and Acceptance testing using Codeception can be found in these repos:

1. Setup project for acceptance testing (login with db CRUD)

    - https://github.com/dr-matt-smith/evote-movie-2019-testing)

