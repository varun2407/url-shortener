# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

 * Submit a url in a form on the homepage
 * Url is saved to the database
 * The URL can be viewed by accessing a Base62 encoded primary key ID(short code) of the URL
 * When visiting the short code, a view is recorded so we can keep track of how many views per day a link gets
  * This should run in the background to keep the application fast
* This should paginate the list of URLs