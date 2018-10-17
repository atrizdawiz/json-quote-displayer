json-quote-displayer
=======
Make beautiful prints of json formated quotes, possibly with animation in the future.

The aim is to present quotes in a beautiful way from a URL pointing to a Json file.

## Usage 
1. Create a .json file (plain text) with the following format:
`{"book":"Put the title of the book here","chapter":"Some chapter number","verse":"Some verse number","body":"The quote text itself here"}`.
2. Upload your json file to a web server that supports XMLHttpRequests (the easiest way is to use http://myjson.com/).
3. Edit the index.html file and change the variable `yourUrl` to your own.
4. Sit back and enjoy the pleasent rendering of your quote.
