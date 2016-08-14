
## Using Flask for blazing fast Rest API development
### Directory structure


    .
    |
    ├── utils
    ├── handlers
    |   └──  todo.py
    ├── models
    |   └──  todo.py
    └── main.py

* main.py - holds route and flask application initialization.
* handlers - This directory holds handlers for different routes.
* models - holds different data models.

### Quick Start
* python main.py
* server will start on port 5000

## Two routes defined in the sample

### /todo
##### metod (Post)
![Alt text](http://blog.roshanraj.com/images/post.png "Post")
##### metod (get)
![Alt text](http://blog.roshanraj.com/images/get.png "Get")


### /todo/<todo id>
##### metod (Get)
![Alt text](http://blog.roshanraj.com/images/withid.png "Get")
##### metod (Put)
![Alt text](http://blog.roshanraj.com/images/put.png "Put")
