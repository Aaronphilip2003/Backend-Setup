# Backend Setup
![[Pasted image 20220724221946.png]]

## Server Side
- set a connection url and connect it to the mogodb cluster 
- set a connection port `const PORT = process.env.PORT || 5000;`
- npm init -y ( to initialize a package.json)
- add `"type": "module"` and `"start" :"nodemon index.js"` under scripts

connect the connection_url using mongoose :

![[Pasted image 20220724223335.png]]

Make 3 folders in the server side :
![[Pasted image 20220724225120.png]]
