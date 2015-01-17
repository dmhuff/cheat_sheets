Rails Cheat Sheet
=================

Basics
------
- `$ rails new foo`: Generate a new project called "foo".
- `$ rails s`: Start the Rails web server.
- `$ rake db:migrate`: Run all unapplied migrations.
- `$ rake db:rollback`: Rollback the last migration.
- `$ rake db:migrate:redo`: Rollback and reapply the last migration.


Models
------
- `$ rails g model Foo chunky:string bacon:text`: Generate the model, migration, tests, etc. for a table "foos" with two columns.

Views
-----

Controllers
-----------
- `$ rails g controller foo bar`: Generate a new controller called "foo", with action "bar".

- Standard CRUD action methods, in conventional order:
    - index
    - show
    - new
    - edit
    - create
    - update
    - destroy

- Helper Methods:
    - `params`: Returns a hash containing form and query parameters submitted.
    - `render`: Instructs the view to render the specified content.
    - `redirect_to`: Redirect the user to a particular action.


