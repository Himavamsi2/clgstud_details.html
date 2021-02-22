# clgstud_details.html<!DOCTYPE html>
<html>
    <head>
        <title></title>
        <script type="text/javascript"></script>
        <style type="text/css" media="all">
            body{
                background-color: #f0080f;
            }    
            h1{
                color: #006666;
                font-family: Verdana;
                text-align: center;
            }
            #rentalcost
            {
                border:1px solid;
            }
        </style>

    </head>
    <body >
       
            <h1>College details</h1>
        <center>
            <form>
            <table>
            <tr>
                <td><label>Name</label></td>
                <td><input type="text" name="name" id="name" value="" placeholder="college name" pattern="[A-Za-z/s]+" required=""/></td>
            </tr>
            <tr>
                <td><label>Reg id</label></td>
                <td><input type="text" name="rid" id="rid" value="" placeholder="xxxx@dept" required/></td>
            </tr>
            <tr>
                <td><label>Year founded</label></td>
                <td><input type="text" name="year" id="year" value="" pattern="[7-9]{1}[0-9]{9}" placeholder="" required=""/></td>
            </tr>
            <tr>
                <td><label>City</label></td>
                <td><input type="text" name="city" id="city" value="" placeholder="city name" pattern="[A-Za-z/s]+" required=""/></td>
            </tr>
            <tr>
                <td><label>No of students</label></td>
                <td><input type="number" name="num_student" id="num_student" value="" required/></td>
            </tr>
            <tr>
                <td><label>Courses</label></td>
                <td><select name="courses" id="courses" required>
                    <option value="Computer science">Computer science</option>
                    <option value="IT">IT</option>
                </select></td>
            </tr>
            <tr>
                <td><input type="submit" name="submit" id="submit" value="result"></td>
                <td><input type="reset" name="clear" id="reset" value="Reset"></td>
            </tr>
        </table>
        </form>
        <div id="result" name="result"></div>
    </center>
    </body>
</html>
