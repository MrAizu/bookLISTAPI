Prequtise:

+ npm
+ mongodb
+ express
+ nodemon

start the server
open terminal and type npm start

// To get all listed books

open postman and type: http://localhost:3000/books in the enter request URL section and hit enter.

// To add a book
type: http://localhost:3000/books in the enter request URL section,change the method POST,click body, 
and select “x-www-form-urlencoded”. Then, enter name as the key and a book name of your choice as a value, and hit send

// To find a book
change the method to GET type: http://localhost:3000/books/(specify book id) in the enter request URL section and hit enter

// To delete a book
change the method to DELETE type: http://localhost:3000/books/(specify book id) in the enter request URL section and hit enter