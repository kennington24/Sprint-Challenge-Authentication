<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    Middleware: like a mini app that allows different apps to pass data to one another
    Sessions: A middle ware that supplies user logins with cookies to keep track of their login time
    Bcrypt: Middleware that hashes passwords an amount of time set by the developer
    JWT: Json web tokens, basically another form of sessions

2.  What does bcrypt do in order to prevent attacks?
    Hashes passwords so that attackers can't decode it without the set secret/key

3.  What are the three parts of the JSON Web Token?
    Header, payload and a signature
