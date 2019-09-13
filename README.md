# get user
## method - get
### url - http://host:port/api/user/{userId}

## response status:200 ok
## response body: {
	"firstname": "simon",
		"lastname": "dsouza",
		"email": "simon@gmail.com",
		"address": "Merode",
		"age": 25
}
## response status : 404 not found


# get all user
## method - get
### url - http://host:port/api/user
## response status:200 ok
## response body:
[{
	"firstname": "simon",
	"lastname": "dsouza",
	"email": "simon@gmail.com",
	"address": "Merode",
	"age": 25
}, 
{
	"firstname": "daniel",
	"lastname": "dsouza",
	"email": "dd@gmail.com",
	"address": "WSL",
	"age": 27
}, {
	"firstname": "fedrik",
	"lastname": "cowell",
	"email": "fed@gmail.com",
	"address": "Merode",
	"age": 30

}]


# create an user
# method post
### url - http://host:port/api/user
## request body:{
	        "firstname": "simon",
		"lastname": "dsouza",
		"email": "simon@gmail.com",
		"address": "Merode",
		"age":25
	}

# status: 200 ok

# update an user
# method put
### url - http://host:port/api/user/{userId}
## request body:{
                  "email":"sd@gmail.com"
		  }
## response status: 200 ok

# delete an user
# method delete
### url - http://host:port/api/user/{userId}
## response status: 200 ok
		  
		  







