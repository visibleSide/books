# Project 1

Web Programming with Python and JavaScript
DATABASE_URL=postgres://bsnhdofwdlpyjl:c81db565a194dc4618130dc8398efd6dc59cf449088dcd5337c66b4b3e88bd22@ec2-54-243-193-59.compute-1.amazonaws.com:5432/d50hn9hnukbrra

In the project you will see the following words:
    Los libros --> "Books"
    Reseñas de libros --> "World of Books"

In project we have:
    templates --> contains the the html files of the projects
    import.py --> contains the code to import books.cvs to the database
    create.sql --> contains the database design
    application.py --> contains the routes of the project
                        



In templates folder we have:
    base.html -->  contains common layout and links
    index.html --> shows the homepage
    login.html --> shows the login form
    profile.html --> shows the profile page
    signup.html --> shows the signup page
    error.html --> to handle all errors, to not let the website crash
    search.html --> to handle searches, isbn, title, author
    results.html --> to display the search that was made
    book.html --> to display about the book from the search results, "http://covers.openlibrary.org/a/          $key/               $value-$size.jpg" used this api to get cover of the books for their             isbn


You have to intall the following modules: look into the 
    Flask-Login --> to handle the user sessions after authentication
    Flask-SQLAlchemy --> to represent the user model and interface with our database
