Quick UI for the payphone. This is intented to be used with some sort of API on the backend that handles the command.

The backend root get route should return a json element with a "data" tag that has an array of function names. These function names will be the buttons.
The app will sent post requests with the function name back to the root post route. Handle accordingly.

PS. The app also utilizes a /gif get route, supply giphy embed links from the backend here.
