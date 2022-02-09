Bookmark Manager Challenge

User Story #1
-------------------------------------------------
As a user
So that I can access important web pages faster 
I would like to see a list of my bookmarks 
-------------------------------------------------
Domain Model: 
<blockquote class="imgur-embed-pub" lang="en" data-id="a/4MWFE0e" data-context="false" ><a href="//imgur.com/a/4MWFE0e"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

How to use 
To set up the project

Clone this repository and then run:
-bundle

To set up the database:

Connect to psql and create the bookmark_manager database:

CREATE DATABASE bookmark_manager;
To set up the appropriate tables, connect to the database in psql and run the SQL scripts in the db/migrations folder in the given order.

To set up a test database, let's run psql and create a database, and use the SQL query saved in db/migrations/01_create_bookmarks_table.sql to create a bookmarks table.

To view bookmarks, navigate to localhost:9292/bookmarks.

To run the Bookmark Manager app:
-rackup -p 3000

To view bookmarks, navigate to localhost:9292/bookmarks.

To run tests:
-rspec

To run linting:
-rubocop