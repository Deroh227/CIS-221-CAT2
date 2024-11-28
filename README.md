<!DOCTYPE html>
<html lang="en">
    <head>
        <style>
            body,label,input,select,button{
                margin: 0;
                padding: 0;
                align-items: center;
            }
            button{
                margin-right:100px;
            }
            h2{
                margin-right: 200px;
            }
            body{
                background-color: rgba(245,245,245,0,);
                display: flex;
                justify-content: center;
                align-items: center;
                min-height: 100vh;
            }
            .a{
                color:red;
                font-weight: bold;
            }
            form{
                display: flex;
                flex-direction: column;
            }
            .form-group{
                margin-bottom: 15px;
            }
            label{
                margin-bottom: 10px;
            }
            input{
                padding: 5px;
                border-radius: 2px;
                border:1px solid black;
                align-content: center;
            }
        </style>
        <meta charset="UTF-8">
        <meta name="viewport"content="width=device-width,initial-scale=1.0">
<head>
<title>Register Account</title>
<form>
    <body>
        <div class="container">
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<h1>Register Account</h1>
            <form id="registeration-form">
                <div class="form-group">
   <label for="name">Full Name:</label>
     <input type="text"placeholder="as"id="fullname"name="fullname"/>
     <span class="a" >User name must be atleast 4 characters</span></div><br/>
     <div class="form-group">
        <label for="password">Password:</label>
         <input type="password"placeholder="...."id="password"name="password"/>
         <span class="a" >Password must be atleast 4 characters</span></div><br/>
         <div class="form-group">
            <label for="confirm-password">Confirm password:</label>
             <input type="password"placeholder="...."id="confirm-password"name="confirm-password"/>
             <span class="a" >Passwords do not match</span></div><br>
             <div class="form-group">
                <label for="email">Email:</label>
                 <input type="email"placeholder="Ojiambo@gmail"id="email"name="email"/>
                 <span class="a" >Invalid Email format</span></div><br/>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Format:Ojiambo@gmail.com
                </div><br>
                    <div class="form-group">
                        <label for="phone number">Phone Number:</label>
                        <input type="tel"placeholder="1111111111"id="phone"name="phone"/>
                        <span class="a" >Invalid phone number</span></div><br/>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Format:0XXX-XXX-XXX
                </div><br>
            <div class="form-group">
                <label for="zip">Zip Code:</label>
                <input type="text"placeholder="1111111111"id="zip"name="zip"/>
                <span class="a" >Invalid zip code</span></div><br/>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Format:Use 5 or 9 digits zip code
        </div><br>
        <div class="form-group">
        <label for="card-type">Card-Type:</label>
        <select id="card-type"name="card-type">
        <option value="visa">Visa</option>
        <option value="mastercard">Mastercard</option>
        <option value="amex">American Express</option> 
        </select>
        </div><br> 
        <div class="form-group">
            <label for="card-number">card-number:</label>
            <input type="text"placeholder="1111111111"id="card-number"name="card-number"/>
            <span class="a" >Invalid card-number format</span></div><br/>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Format:1111_2222_3333_4444
    </div><br>
    <div class="form-group">
        <label for="expiration-date">Expiration Date:</label>
        <input type="date"placeholder="1111111111"id="expiration-date"name="expiration-date"/>
        <span class="a" >Invalid date format</span></div><br/>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Format:YYYY_MM_DD
</div><br>
<div class="form-actions">
    <button type="submit">Register</button>
    <button type="reset">Clear Form</button>
</div>
</form>
</body>
</html>

       
