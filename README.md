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

*compile webpacker(compile not yet) ← where this error？<br>
:command to terminal(3ways)<br>
①rails assets:precompile←try it!<br>
②bin/webpack<br>
③bin/webpack-dev-server <br>

4*add value on render<br>
:<%= render 'form', book: @book %><br>

5*add column on table<br>
:command to terminal<br>
rails g migration add_title_to_books title:text<br>

6*define @books on BooksController-show<br>
:else  @books=Book.all  end<br>

7*change edit-link(UrlGenerationError) <br>
:<%=link_to "Edit",edit_book_path(book) %><br>

8*delete double-tag<br>
: form /form <br>

9*add argument<br>
:@book.update(book_params)<br>

