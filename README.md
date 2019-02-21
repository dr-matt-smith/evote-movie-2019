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
  - change all navigation links tothe form `/index.php?action=<PAGE>`
    - e.g. `/index.php?action=about` for link to about page


## Links to completed verions


1. https://github.com/dr-matt-smith/evote-movie-2019-01-basic-html
2. https://github.com/dr-matt-smith/evote-movie-2019-02-all-files-dot-php
3. https://github.com/dr-matt-smith/evote-movie-2019-03-front-controller


