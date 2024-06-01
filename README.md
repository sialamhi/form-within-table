<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="lable.css">
   
</head>
<body>
    <div class="form-container">
        <div class="form">
            <h3>REPORT FORM</h3>
            <h2>INFORMATION TABLE</h2>
            <form action="">
                <table>
                    <tr>
                        <td class="label-cell">
                            <label for="name">NAME</label>
                        </td>
                        <td>
                            <input type="text" id="name" name="name">
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="email">EMAIL</label>
                        </td>
                        <td>
                            <input type="email" id="email" name="email">
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="password">PASSWORD</label>
                        </td>
                        <td>
                            <input type="password" id="password" name="password">
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="address">ADDRESS</label>
                        </td>
                        <td>
                            <input type="text" id="address" name="address">
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="country">COUNTRY</label>
                        </td>
                        <td>
                           <select name="country" id="country">
                            <option value="PAKISTAN">PAKISTAN</option>
                            <option value="INDIA">INDIA</option>
                            <option value="CHINA">CHINA</option>
                            <option value="JAPAN">JAPAN</option>
                            <option value="AFGANISTAN">AFGANISTAN</option>
                            <option value="ENGLAD">ENGLAD</option>
                            <option value="SAUDI ARABIA">SAUDI ARABIA</option>



                           </select>
                       

                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="gender">GENDER</label>
                        </td>
                        <td>
                            <input type="radio" name="gender" id="male" value="male">
                            <label for="male">MALE</label>
                            <input type="radio" name="gender" id="female" value="female">
                            <label for="female">FEMALE</label>
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <label for="hobbies">HOBBIES</label>
                        </td>
                        <td>
                            <input type="checkbox" id="hobby1" name="hobby" value="hobby1">
                            <label for="hobby1">Hobby 1</label><br>
                            <input type="checkbox" id="hobby2" name="hobby" value="hobby2">
                            <label for="hobby2">Hobby 2</label><br>
                            <input type="checkbox" id="hobby1" name="hobby" value="hobby1">
                            <label for="hobby1">Hobby 1</label><br>
                            <input type="checkbox" id="hobby1" name="hobby" value="hobby1">
                            <label for="hobby1">Hobby 1</label><br>
                            <input type="checkbox" id="hobby2" name="hobby" value="hobby2">
                            <label for="hobby2">Hobby 2</label>
                        </td>
                    </tr>
                    
                    <tr>
                        <td class="label-cell">
        
                            <label for="name">YOUR WEB SITE</label>
                        </td>
                        <td>
        
                            <input type="text">
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
        
                            <label for="name">OTHER INFORMATION ABOUT YOU</label>
                        </td>
                        <td>
        
                            <TExtarea style="height: 150px;"></TExtarea>
                        </td>
                    </tr>
                    <tr>
                        <td class="label-cell">
                            <input type="button" value="SEND IN MY REPORT" alt="Submit">
        
                            <!-- <label for="name">SEND IN MY REPORT</label> -->
                        </td>
                        
                        <td >
                            <input type="button" value="ERASE REPORT FORM" onclick="this.form.reset(); return false;">
        
                            <!-- <label for="name">SEND IN MY REPORT</label> -->
                        </td>
                    </tr>
                    
                        
                       
                    
                </table>
                <br>
                <!-- Submit button with an image -->
                <input type="image" src="myimg.jpg" alt="Submit" width="50" height="50">
                
                <!-- Reset button with an image -->
                <input type="image" src="myimg.jpg" alt="Reset" width="50" height="50" onclick="this.form.reset(); return false;">
            </form>
        </div>
    </div>
</body>
</html>
.form-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.form {
    border: 1px solid #000;
    padding: 20px;
    background-color: #f9f9f9;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

table {
    width: 100%;
    border-collapse: collapse;
}

table, th, td {
    border: 2px solid #000;
}

td {
    padding: 10px;
}

.label-cell {
    width: 50%; /* Adjust the width as needed */
    text-align: right;
}
h2{
    background-color: rgb(6, 55, 6);
    color: white;
    text-align: center;

}
h3{
    text-align: center;
}
