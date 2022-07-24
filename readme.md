# Backend Setup
![image](https://user-images.githubusercontent.com/69317200/180659326-24d9cfb4-48a0-43a6-9e1e-f6001b32043b.png)

## Server Side
- set a connection url and connect it to the mogodb cluster 
- set a connection port `const PORT = process.env.PORT || 5000;`
- npm init -y ( to initialize a package.json)
- add `"type": "module"` and `"start" :"nodemon index.js"` under scripts

connect the connection_url using mongoose :

![image](https://user-images.githubusercontent.com/69317200/180659341-196b3967-ab78-4b63-b1ee-b3b1a1ac8718.png)

Make 3 folders in the server side :
![image](https://user-images.githubusercontent.com/69317200/180659361-302ff9d7-b73d-4a5b-a161-e691d857f557.png)
