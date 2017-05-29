# _Eliot, Say "Bookstore"_

#### _A bookstore website, 5/26/17_

#### By _**Eliot Carlsen**_

## Description
_Drupal Site using PHP and Drupal features and themes_
_Project has 2 basic pages - an "About" page, and a "Locations" page_
_Project has a Contact module. Includes a Contact form with a "Contact" link in the main menu. Anyone, regardless of their user role, can use the form to send me website feedback_
_Project uses Views module, the Features module and the Strongarm module, and all their dependencies._
_Project has a feature called "Site Configuration". The feature tracks the strongarm variables site_name, site_slogan, theme_default and site_frontpage (The URL for the page displayed as your frontpage)._
_Project has a "Book Review" custom content type. The title field is labelled "Book Title". It also includes fields for "Book Author", "Rating", and "Review Body"._
_The "Book Title", "Book Author", "Rating", and "Review Body" fields are required._
_The is chosen with either a menu or radio buttons._
_The fields are in the order "Book Title", "Book Author", "Rating", then "Review Body" when you fill out the form to add an instance of the book review content type._
_Project has a feature called "Book Review" for the content type._
Project has a view for the Book Review content type called "New Books". This block displays the 3 newest book reviews as an unformatted list of linked titles, so that users can click on the title of a new book to go read the review of it._
_Project has a custom "Reviewer" role. The Reviewer role has all the same permissions as an authenticated user, and also is able to create new book reviews. They are able to edit and delete their own book reviews, but not anyone else's._
_Project displays  a special coupon as a block on the front page which is visible to authenticated users and not anonymous users. It says "This week: use this coupon code to get 25% off on all Science Fiction!"_

## Setup/Installation Requirements

* _git clone this project to your desktop_
* _open MAMP or LAMP on your computer and point the server to the top level of the project folder_
* _start the server and open up the localhost page_
* _export zip database file to the mySQL server_
* _create the database user using the name and password settings in the settings.php file_


## Known Bugs

_None_

## Support and contact details

_eliot.carlsen@gmail.com_

## Technologies Used

_Drupal_
_PHP_

### License

*MIT License*

Copyright (c) 2016 **_Eliot Carlsen_**
