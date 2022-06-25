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

* 1*root-path<br>
:add routes.rb  root to: 'homes#top'

* 2*undefined controller-name<br>
:change cotrollers/homes  class HomesController<br>

* 3*add path to start<br>
:<%=link_to start,book_path %>

* 4*add value on render<br>
:<%= render 'form', book: @book %>

* 5*add column on table<br>
:command to terminal<br>
 rails g migration add_title_to_books title:text<br>
 rails db:migrate

* 6*define @books on BooksController-show<br>
:else  @books=Book.all  end

* 7*change edit-link(UrlGenerationError) <br>
:<%=link_to "Edit",edit_book_path(book) %>

* 8*delete double-tag<br>
: form /form 

* 9*add argument<br>
:@book.update(book_params)

*compile webpacker(compile not yet) ← where this error？<br>
:command to terminal(3ways)<br>
①rails assets:precompile←try it!<br>
②bin/webpack<br>
③bin/webpack-dev-server <br>
