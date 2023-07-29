### node js

## local module --> exports & require
## fs (file system) module -> node js personal module
1) writeFile() --> create file and what data i want to send to the file which one is created using async method.
2) appendFile() --> add data to existing file data.
3) rename() --> rename the exixting file
4) readFile() --> read the data which are exists in the file
5) unlink() --> Delete File
6) exists() --> the file really exists ?? using this method you can assure that the file or path is really exist on you project directory, if the value return true the file exist on your directory folder and if return false the file doesn't exist on your project directory.

## os and path module
# os module --> very much important methods of this module
1) userInfo()
2) hostname()
3) homedir()
4) totalmem()
5) freemem()
6) __dirname // return the name of the root director folder
7) __filename // return the file name 
# path module -->
1) extname --> // find the path of the file
2) join

## http module --> create http server

## http, req, res model & status code -->
http status code -->
1) Information response - (100-199)
2) Successful response - (200-299)
3) Redirects - (300-399)
4) Client Errors - (400-499)
5) Server Errors - (500-599)

## npm --> external modules (node package manager which is managed by nodejs)
1) individually create package.json file

______________________________________
### create Express server
## Express router
## postman (Testing API)

## http response- json file, html file, text
## http request with - query parameters, route parameter & header, make post request with json or form data
## send and receive form data--(post method and request body)
## regular expression
## environment variables -->
### .env file means environment file, secret/hidden file only you can access it
### why .env file?
1) to store private environment variables for your application. Like- Database URL, API Keys, http PORT to listen the server.
2) Gitlab or Heroku support the usages of env. variables
3) for comment --> using # ( # server port )
### expressjs middleware function : -->
  1) Third party middleware - body-parser, cookie-parser etc.
  2) Application-level middleware - app.use(), app.METHOD()
  3) Router-level middleware - router.use(), router.METHOD()
  4) Error handling middleware
  5) Built in middleware - expressjs, express.json, express.urlencoded
### Static middleware
