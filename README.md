# Book-Record-Management

// this is an  application for book management / API 

## Endpoints


## /users (done)
POST: Create a new user
GET: Get all list of users

## /users/{id} (done)
GET: Get a user by thier ID
PUT: Update a user by ID
DELETE: Delete a user by thier ID (Check if the user still has an issued book && is there any fine to be collected from the user)

## /users/subscription-details/{id}
GET: Get user subscription details
1. Date of Subscription
2. Valid till ??
3. Fine if any ??

## /books
GET: Get all books
POST: Add a new book

## /books/{id}
GET: Get a book by id
PUT: Update a book by Id

## /books/issued
GET: Get all issued books here

## /books/issued/withFine
GET: Get all issued books with fine

## Subscription Typs
Basic (3 months)
Standard (6  months)
Premium (12 months)

If user has an issued book and the issued book is to be returned at 09-12-22
If user missed the date to return, then user gets a fine of Rs. 100/-

If user has an issued book and the issued book is to be returned at 09-12-22
If user missed the date to return, and the users subscription also got expired, then user need to pay a fine of 200/- (200+100)



## database 

// CRUD operation // create read update delete all the operation is performed on the database
// mongoose is dependency is also included mongodb and also provide
// another special feature as compare to mongodb....
## for developer dependency
 npm i nodemon --save-dev

 ## server is start first then database 
 it also help to not lose the data 
 and it act as mediator between fronted and database that help to communication between fronted and database 

 ## MVC architecture  
 model/modal view controller architecture 
 model and controller is related to backend  and controller is the brain/logic  of your route
 and view is related to frontend 

 ## model:
  It speaks abt the structure of MongoDB Collection 

## timestamp 
it tell time when our database is created 