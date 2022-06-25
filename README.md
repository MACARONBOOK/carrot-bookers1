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


# carrot-bookers1
Template is missing programs.<br>

1*root-path<br>
:add routes.rb  root to: 'homes#top'<br>

2*undefined controller-name<br>
:change cotrollers/homes  class HomesController<br>

3*add path to start
:<%=link_to start,book_path %>

*compile webpacker<br>????????????
=>compile not yet<br>
:command to terminal(3ways)  <br> 
1. rails assets:precompile←try it!  2. bin/webpack  3. bin/webpack-dev-server <br>

4*add value on render<br>
:<%= render 'form', book: @book %><br>

5*add column on table<br>
:command to terminal<br>
rails g migration add_title_to_books title:text<br>

6*
:

7*
:

8*
:

9*
:
