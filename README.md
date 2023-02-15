Assignment 8

How to REQUEST data: Data is requested via an HTML form on the web app. This form takes in input from the user and uses it to send a SQL query to the MySQl database for data. If the user is looking for information regarding an image, they can search for that information by the name of the image, the first name of the image's artist, or the last name of the image's artist. If the user is looking for information regarding a user, they can search for that information by the first name of the user, the last name of the user, or the email address of the user.

How to RECEIVE data: The results of the SQL query (specifically a SELECT query) are converted to JSON and printed to the web page. If the search was successful and the user was looking for information regarding an image, they will receive the image ID, the image name, the first name of the image's artist and the last name of the image's artist. If the search is successful and the user was looking for information regarding a user, they will receive the user ID, the first name of the user, the last name of the user, and the email address of the user.

<img width="809" alt="Screenshot 2023-02-14 at 9 09 53 PM" src="https://user-images.githubusercontent.com/97123932/218916735-bef8b1ed-7636-4e89-aa72-85e80929ce07.png">
