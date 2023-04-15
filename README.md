# polling System API

### how to run file

* download zip file
* extract zip file in your sytem
* open file in VS code
* open terminal in Vs code
* run command npm i
* run command nodemon index.js


## How to call API

#### open PostMan Application and try running these commands

* for creating question  __localhost:8000/question/create__  method: POST , here you have to give key as title and value as question
* for deleting question  __localhost:8000/question/:id/delete__ method: GET , here you have to give _id of that question
* for creating option to question __localhost:8000/question/:id/options/create__ method: POST, here you have to give key as text value as option, also you need to give _id
* for showing full question with option __localhost:8000/question/:id__ method: GET, here you have to give _id of that question
* for deleting a particular option __localhost:8000/option/:id/delete__ method: GET, here you have to give _id of that particular option
* for adding vote to option __localhost:8000/option/:id/add_vote__ method: POST, here you have to give _id of that option 



