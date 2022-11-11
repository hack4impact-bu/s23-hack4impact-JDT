------------ Workshop 1 Starts Here ------------
Workshop 1 CheckList

## FrontEnd

[ ] Create client folder
[ ] Setup index.html
[ ] Bring in Skeleton CSS
[ ] http://getskeleton.com/
[ ] https://cdnjs.cloudflare.com/ajax/libs/skeleton/2.0.4/skeleton.min.css
[ ] Create Header
[ ] Create form
* [ ] Name
* [ ] Content
* [ ] u-full-width to both inputs
[ ] Listen for form submit
[ ] Hide the form
[ ] Show loading spinner
[ ] Get data from form and log it
✅ Get user input on the Client
✅ Hide/Show elements on the client

## BackEnd

[ ] Create server folder

[ ] npm init -y (in your server folder)
[ ] npm install express morgan
[ ] Setup index.js
[ ] npm i --save-dev nodemon (automatically refresh when changing server)
[ ] Add GET / route
------------ Workshop 1 Ends Here ------------

------------ Workshop 2 Starts Here ------------
Workshop 2 CheckList

## BackEnd

[ ] Add POST /mews route
[ ] log out req.body

## FrontEnd

[ ] fetch POST /mews with form data
[ ] See the CORS error and revel in this moment
✅ Send user input from the client with fetch to the server

## BackEnd

[ ] npm i cors
[ ] log out req.body
[ ] Make sure the server is recieving the data
[ ] Add JSON body parser middleware
[ ] Validate name and content
- [ ] Must be a string
- [ ] Cannot be empty
[ ] If not valid
 - [ ] Error code 422
 - [ ] Invalid mew, must contain name and content
[ ] Setup DB Connection
- [ ] install mongoDB
- [ ] npm install monk
- [ ] connect to db
- [ ] create document collection (mews)
[ ] If Valid
- [ ] Create mew object with
- [ ] name, content, created_date
- [ ]  Insert into DB
- [ ] Respond with created mew object
✅ Store data in a database

------------ Workshop 2 Ends Here ------------
