# Poll

API to operate over questions, their options and the answers

## Access Points:
### Idea
	- GET /questions - list all the questions (and probably the options)
	- GET /questions/{id} - gets the question with the given {id} (and probably the options)
	- GET /questions/{id}/options - gets the options to the question with the given {id} 
	- POST /questions - adds new question
	- POST /questions/{id}/options - adds new option to the question with the given {id} 
	- PUT /questions/{id} - edits the question with the given {id}
	- PUT /questions/{qid}/options/{id} - edits the option with the given {id}
### Available