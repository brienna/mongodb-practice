
# MongoDB project

In this assignment, you will develop an application using MongoDB. The goal of the assignment is to develop a basic search application that can be used to search tweets or comparable data of your choice.

## Part 1: Backend application

For backend processing you must use the MongoDB database management system. You should use the twitter dataset with 11,000 documents and choose data from some source that allows you to download a large quantity of data. There should be thousands of documents and several property/value pairs for each document. Each document must contain at least one property having at least as much text as a standard tweet (140 chars). You must develop a small program that connects to either dataset to perform some query.

## Part 2: Frontend application

The user-facing portion of the application should have a web interface, e.g., an html document. The application should be developed in JavaScript or Python. The instructor should be able to run the application on the Ubuntu VM available on serenity. 

For this application you should perform the following functions:

1. Connect to the database and show the connection process at startup. Each step in the startup process should have a message sent to the console or GUI. This includes the connection to the server, database and collection.
2. Present the user with web-based display that asks the user for a query string. It must support partial words. Examples include but are not limited to "Foo" should find "Food" or "work" should find "piecework".
3. The response to the user's request should present the user with a selection list of documents answering the request, but not the content of the document.
4. Once presented with the selection list, by title, by date, or other identifying information, the user should be able to select the desired document to view the content. 
5. The user is presented with the option to search again and again until they exit the page. 
6. The user has the ability to add a separate annotation (e.g., a comment) to the selected document. Annotations are stored with the document and will show in subsequent retrievals of the document. 

Criteria:
- GUI solicits required information from the user.
- Literal word search works acceptably.
- Partial word search works acceptably.
- Document list is returned to user for selection.
- Document list includes date and author.
- User can select the document to view and entire selected document is displayed.
- User can exit the view to return to the list.
- User can exit the list to perform a new search.
- User comments can be added to the documents.
- User comments are retrieved with the documents.
- Source code style is readable.
- GUI appearance is acceptable.