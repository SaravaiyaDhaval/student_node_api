 
 Node-API for Students data using MongoDB

1) Requirment Specification
⦁	Database      =>  MongoDB.
⦁	Backend API => Node.
⦁	Editor           = > VS Code. 

2) Project Specification
⦁	Database Name   => student_db
⦁	Project Name       =>  Students Data.

3) required node dependency
⦁	npm i async
⦁	npm i body-parser
⦁	npm i boom
⦁	npm i connect-busboy
⦁	npm i  express
⦁	npm i  express-fileupload
⦁	npm i  form-data
⦁	npm i  http-proxy
⦁	npm i  jsonwebtoken
⦁	npm i mongo-cursor-pagination
⦁	npm i mongodb
⦁	npm i multer
⦁	npm i nodemailer
⦁	npm i nodemailer-mandrill-transport
⦁	npm i validator

4) Project File Structure
 

5) API structure
  #) GET 
⦁	localhost:8000/student
⦁	localhost:8000/student : id
⦁	localhost:8000/sendMail
⦁	localhost:8000/getImge
⦁	localhost:8000/ 
		=>  Sends HTTP status code 200 back to browser
⦁	localhost:8000/ *
		=>  this will set the status to 404
#) POST
⦁	localhost:8000/student
⦁	localhost:8000/uploadProfile
⦁	localhost:8000/uploadImage
⦁	localhost:8000/authentication

#) PUT
⦁	localhost:8000/student : id

#) Delete
⦁	localhost:8000/student : id

6) project implementation
⦁	get, put, post, delete students  record in  student_db database in m-lab
⦁	apply JWT tochen authentication.
⦁	single and multiple file upload from server  and display using api
⦁	file upload validation when user upload profile picture (file size and images max sizes)
⦁	server side data base  field validation
⦁	login authentication when user login (user not found  password not match etc..)
⦁	display various  types of http  staus code 
⦁	send mail to user mail accounts with muliple files attechment 
⦁	apply server side pagination  when display mutiple records  as a responce

7) Project Run Guide
⦁	npm install
⦁	npm run dev
