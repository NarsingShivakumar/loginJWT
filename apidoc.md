///////////// /
*GetAllUser/ (GET)> http://localhost/users

/*Register/ (POST)> http://localhost/register (body) => {"name":"Shiva", "email":"shiva@gmail.com","password":"12345678","phone":343432,role?":"user"}

/*Login/ (POST) => http://localhost/login (body) => {"email":"shiva@gmail.com","password":"12345678"} (response)=> {auth:true,token:'dgsdg'}

/*UserInfo/ (GET) => http://localhost/userinfo 
# (Header) => {'x-access-token':'token value from login'}

npm i bcryptjs body-parser cors express jsonwebtoken mongoose
