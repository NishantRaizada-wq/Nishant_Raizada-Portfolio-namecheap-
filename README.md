# NishantRaizada-wq.github.io
<!DOCTYPE html>
<html>
    <head>
  <style>
.login-page {
  width: 360px;
  padding: 8% 0 0;
  margin: auto;
  

}
  .item
  {
      color: blue;
  }
  #button
  {
    position: relative;
  }
  
  .clear { 
        width: 40px;
        height: 46px; 
        position: absolute;         
        font-family: monospace;
        font-size: 7px;
        padding-left: 13px;
    }
      .username1
      {
        position: relative;

      }

.form {
  position: absolute;
  z-index: 1;
  background: #FFFFFF;
  max-width: 360px;
  margin: 0 auto 100px;
  padding: 45px;
  text-align: center;
  box-shadow: 0 0 20px 0 rgba(0, 0, 0, 0.2), 0 5px 5px 0 rgba(0, 0, 0, 0.24);
}
 .form input {
  font-family: "Roboto", sans-serif;
  outline: 0;
  background: #f2f2f2;
  width: 100%;
  border: 0;
  margin: 0 0 15px;
  padding: 15px;
  box-sizing: border-box;
  font-size: 14px;
}
.editpassw
{
  position: absolute;
  font-family: monospace;
        font-size: 7px;
        padding-left: 13px;
        width: 40px;
        height: 46px; 

}
  .gogi
  {
    margin-top: 3px;
    position: absolute ;
    
  }
 
   
form button {
  font-family: "Roboto", sans-serif;
  text-transform: uppercase;
  outline: 0;
  background: #4CAF50;
  width: 100%;
  border: 0;
  position : relative ;
  padding: 15px;
  color: #FFFFFF;
  font-size: 14px;
  -webkit-transition: all 0.3 ease;
  transition: all 0.3 ease;
  cursor: pointer;
}
#id1 , #id2 , #id3 ,  #id4 ,  #id5 , #id6
  {
    background-color: black;
    color: rgb(226, 26, 26);
    font-weight: bolder;
    border-collapse: collapse !important; 
    border-color: darkblue;
    }

      
.form .message {
  margin: 15px 0 0;
  color: #b3b3b3;
  font-size: 12px;
}
.form .message a {
  color: #4CAF50;
  text-decoration: none;
}
  .baggi
  {
    position: relative;

      }  
      .BOX
      {
             border: 2px solid rgb(168, 110, 22);
             width: 500px;
             height: 600px;


      }

  </style>



    </head>
<body>
<div class="login-page">
    <div class="form">
      <form class="register-form">
        <div> 
        <input  class="username" type="text" placeholder="name" name="username" value=""/>    
        <button class="clear">clear</button> 
     </div>
     <div>
        <input class = "username1"  type="password" placeholder="password" value=""/>
        <button class="editpassw">clear</button>                                      
      </div>
      <div>
        <input type="text" placeholder="email address" value=""/>
        <button class="editpassw">clear</button>
        </div>
        <button class="baggi">create</button>
        <p class="message">Already registered? <a href="#">Sign In</a></p>
      </form>
      <form class="login-form">
        <div>
        <input type="text"  placeholder="username"/>
       <button class="editpassw">clear</button>
        </div>
        <div>
        <input type="password" class="ju" placeholder="password"/>
        <button class="editpassw">clear</button>
      </div>
        <button class="yogi">login</button>
        <p class="message">Not registered? <a href="#">Create an account</a></p>
      </form>
      <ul class = "itemsh">
        <li class = "item">Item 1</li>
        <li class="item">Item 2</li>
        <li class="item">Item 3</li>
        </ul>
    </div>
    
  </div>
<div class="lsoutput">

</div>
<tr>
<button class = "show" style=" border-radius: 2px; font-family: monospace; font-size: medium;  background-color: rgb(98, 163, 33);">Local storage details</button>
<button class = "show1" style=" margin-left: 65%; font-family: monospace; font-size: medium;  background-color: rgb(98, 163, 33);">Edit Local storage details</button>
</tr>

<br></br>
<button id = "button" >Click Here Bro</button>
<div>
  <input type="text" id = "filter" placeholder="Search items..."  autocomplete="on" value=""/>
  <button class="gogi">Search</button>
</div>
<br>
<tr>
  <button id = "id1">GET</button>
  <button  id = "id2">POST</button>
  <button  id = "id3">PUT</button>
  <button  id = "id4">PATCH</button>
  <button  id = "id5">UPDATE</button>
  <button id = "id6">DELETE</button>
</tr>
<br>
<br>
<div class="BOX">
  <div class="BOX-ITEMS" style="color: chartreuse;">
    HEllo here GET post put patch data is stored 
  </div>
</div>

  </body> 
  <script src="https://cdnjs.cloudflare.com/ajax/libs/axios/0.19.0/axios.min.js"></script>  
  <script src="indexjs.js">
     // npx json-server --watch -p 234 db.json  command for using json server at particular port
  </script>
  </html>
