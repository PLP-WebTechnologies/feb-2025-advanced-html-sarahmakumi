<!DOCTYPE html>
<html>
    <head>
        <title>week 2 assignment</title>
    </head>
    <body>
        <h1>assignment</h1>
        <h3>countries</h3>
        <ol type="i">
        <li>Kenya</li>
        <li>Ghana</li>
        <li>Chad</li>
        <li> Nigeria</li>
        <li> Ethiopia</li>
    </ol>

    <h1> pexels image</h1>
    <img src="image2.jpg" alt="picture of the world globe" width="250" height="250">

    <h1>table</h1>
    <table border="1">
        <thead>
            <tr>
                <th>name</th>
                <th>address</th>
                <th>mobile</th>
                <th>email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>sarah</td>
                <td>nairobi</td>
                <td>012345678</td>
                <td>sarah@gmail.com</td>
            </tr>
            <tr>
                <td>sean</td>
                <td>bungoma</td>
                <td>09876543</td>
                <td>sean@gmail.com</td>  
            </tr>
            <tr>
                <td>stephen</td>
                <td>cameroon</td>
                <td>06574839</td>
                <td>stephen@gmail.com</td>
            </tr>
            <tr>
                <td>nick</td>
                <td>kabete</td>
                <td>07392047</td>
                <td>nick@gmail.com</td>
            </tr>
            <tr>
                <td>sande</td>
                <td>taita</td>
                <td>01777657</td>
                <td>sande@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <h1>registration form</h1>
    <form actions="" methods="">
        <label for="name">name</label>
        <input type="text" id="name" name="name" required>
        <br><br>

        <label for="email">email</label>
        <input type="text" id="email" name="email">
        <br><br>

        <label for="password">password</label>
        <input type="password" id="password" name="password">
        <br><br>

        <label for="date">date</label>
        <input type="date" id="date" name="date">
        <br><br>

        <label for="gender">gender</label>
        <input type="radio" id="gender" name="gender" value="female"> female
        <input type="radio" id="gender" naame="gender" value="male">  male
        <br><br>

        <label for="blood group">blood group</label>
        <input type="checkbox" id="blood group" name="blood group" value="A+">A+
        <input type="checkbox" id="blood group" name="blood group" value="A-">A-
        <input type="checkbox" id="blood group" name="blood group" value="B+">B+
        <input type="checkbox" id="blood group" name="blood group" value="B-">B-
        <input type="checkbox" id="blood group" name="blood group" value="AB">AB
        <input type="checkbox" id="blood group" name="blood group" value="O+">O+
        <input type="checkbox" id="blood group" name="blood group" value="O-">O-
        <br><br>

        <label for="universities"></label>
        <select name="universities" id="universities">
            <option >  select university  </option>
            <option value="UON">UON</option>
            <option value="KU">KU</option>
            <option value="MKU">MKU</option>
            <option value="Agakhan">Agakhan</option>
    </select>
        <br><br>

        <button>register</button>
        <button>cancel</button>
    </form>
    </body>
</html>
