# Rest endpoints of moonshard system
### Both on local network and cloud

##### /user/register
###### POST
	```javascript
	{
		"email":"",
		"phone_number":"",
		"name":"",
		"last_name":"",
		"password:""
	}
	```
	```javascript
	{
		above except password
	}
	```

##### /user/login
gives a token
###### POST

	```javascript
	{
	"phone_number":"",
	"password":""
	}
	```
	```javascript
		{
		"user_id":""
		token : ""
		}
		```


##### /module/all
list of all modules connected to an account
###### POST 

       ```javascript
       {
       "user_id:"",
       "token":"",
       }
       ```

##### /module/send


##### /module/news
