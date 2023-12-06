# chat-bot
my own chat bot, where I can start new conversations and revisit old ones. 

Assignment Description:

1) Initial Setup and Configuration (~30 mins)

Set up the development environment and configure the server of your choice.

2) Database (~30 mins)

Set up an appropriate database(-s) to persist chat conversations. Add mock data for a couple of conversations. Connect the database to the backend server.

3) API Implementation (~30 mins)

Develop a simplified version of the chat API with the endpoints for starting a new chat and for continuing an existing chat. Specifically, write the code for

routing of requests
basic data models for the chat object and further objects if needed
simple components for handling requests, which are primarily focused on routing and returning mock responses (e.g. views in Django)
Ensure that the endpoints can be tested locally or in the cloud using tools like Postman.

⚠️ Mock the data returned by the API; implementing business logic is not required at this stage.

4) Business Logic (~1 hour)

Implement the business logic for the “Continue an Existing Chat” API endpoint.

The endpoint should take a user message as input and use the OpenAI API to generate an assistant response.
Mock the OpenAI API to avoid incurring costs. Ensure that the mock simulates the format of OpenAI API requests and responses realistically. The openapi-mock project may be helpful for this purpose.
