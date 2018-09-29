# Rest endpoints of moonshard system
### Both on local network and cloud

##### /user/register
###### POST
	```json
	{
		"email":"",
		"phone_number":"",
		"name":"",
		"last_name":"",
		"password:""
	}```
	```json
	{
		above except password
	}``

##### /user/login
gives a token
###### POST

	```json
	{
	"phone_number":"",
	"password":""
	}```
	```json
		{
		"user_id":""
		token : ""
		}


##### /module/all
list of all modules connected to an account
###### POST 

       ```json 
       {
       "user_id:"",
       "token":"",
       }

