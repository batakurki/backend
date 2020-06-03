How to test in postman

Create a Post
POST method
http://localhost:4000/posts
body {
"title" : "post one"
}
List all Posts
GET method
http://localhost:4000/posts

Create a comment on perticular post
POST method
http://localhost:4001/posts/${postId}/comments
body {
"content" : "comment one"
}

List all comments 
GET method
http://localhost:4001/posts/${postId}/comments
