# Weather_Api
a Laravel based API in PHP
Weather API Documentation
Base URL	: http://127.0.0.1:8000/api 

Register URL	: http://127.0.0.1:8000/api/register
		Method	: POST
		Params: 
•	name:String
•	email:String
•	password:String
Response: 
Type	: JSON
Values	:
•	status:String
•	message:String
_____________________________________________________________________________________
Login URL	: http://120.0.0.1:8000/login
		Method	: POST
		Params:
•	email:String
•	password:String
Response: 
Type	: JSON 
Params	: 
•	status:String
•	access_token:String
•	token_type:String
•	expires_in:int
•	message
_____________________________________________________________________________________
Get Weather	: http://127.0.0.1:8000/get_weather
		Method	: POST
		Params:
•	location:String
Authorization:
•	Bearer Token
	
		

