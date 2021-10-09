# Apointy
##Task  Instagram Backend API

Users shave the following attributes :
Id
Name
Email
Password

Posts have the following Attributes. All fields are mandatory unless marked optional:
Id
Caption
Image URL
Posted Timestamp

The API developed using Golang.
MongoDB used for storage.


Create an User
Should be a POST request
Use JSON request body
URL should be ‘/users'


Get a user using id
Should be a GET request
Id should be in the url parameter
URL should be ‘/users/<id here>’
  
  
Create a Post
Should be a POST request
Use JSON request body
URL should be ‘/posts'
  
  
Get a post using id
Should be a GET request
Id should be in the url parameter
URL should be ‘/posts/<id here>’
  
  
  
List all posts of a user
Should be a GET request
URL should be ‘/posts/users/<Id here>'
