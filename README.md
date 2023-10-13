# API Name
Sample Name API.

A list of names that allows users to perform actions such as inserting, updating, deleting names in a database.


## API Description
This API allows users to perform the following operations:
Insert a new name into the database.
Retrieve a list of names from the database.
Update a name in the database.
Delete a name from the database.


## API Endpoints
'POST. /postName: Endpoint to insert data into the database. It expects a JSON request payload with fname and lname fields.
'GET' /getName: Endpoint to extract data from the database. It doesn't require any parameters.
'POST' /updateName: Endpoint to update data in the database. It expects a JSON request payload with id, fname, and lname fields.
'POST' /deleteName: Endpoint to delete data from the database. It expects a JSON request payload with an id field.

## Request Payload
{
	“lname”: “hortizuela”,
	“fname”:”manny”
}

 
## Response
{“status”:”success”,”data”:{{“lname”; “hortizuela”, “fname”:”manny”}}}
 


## Usage
Inserting a New Name
To add a new name to your database, use the "Insert Name" endpoint. As an example, let's add the name "Manny Hortizuela."
Endpoint: POST http://127.0.0.1/api/publi/postName

Retrieving a List of Names
To retrieve a list of names from the database, use the "Get Names" endpoint.
Endpoint: GET http://127.0.0.1/api/publi/getName

Updating Name
If you need to update a name in the database, use the "Update Name" endpoint. For example, let's change "Manny Hortizuela" to "Manuel Hortizuela."
Endpoint: POST http://127.0.0.1/api/publi/updateName

Deleting a Name
To remove a name from the database, use the "Delete Name" endpoint. Let's say you want to delete "Manuel Hortizuela."
Endpoint: POST http://127.0.0.1/api/publi/deleteName

## License
No license


## Contributors
Sir Manny Hortizuela
Group members for capstone


## Contact Information
Contact me here: johnalisandaga@gmail.com
