<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>

<body>
    <table>
        <pre><h1 style="color: cadetblue;font-style: italic;border: 1px;border-color: blacklo;">               Registration Form</h1></pre>
        <form action="php"> Name : <input type="text" style="border-radius: 4px;"></div><br><div>         </div><br>
            <!-- in background color to change color of that text we can write background-color: rgb(234, 232, 232);color:red;border-radius:5px... -->
           <div>Class : &nbsp;<select name="1"
                    style="background-color: rgb(234, 232, 232);border-radius: 4px;border-radius: 4px;" id="year">
                    <option value="!">1</option>
                    <option value="2">2</option>
                    <option value="3">3</option>
                    <option value="4">4</option>
                </select> Year <br></div><br>
            <div> Qualification : <select name="q" style="background-color: rgb(234, 232, 232);border-radius: 4px;"
                    id="">
                    <option value="B.Tech">B.Tech</option>
                    <option value="M.Tech">M.Tech</option>
                    <option value="Msc">Msc</option>
                    <option value="PhD">PhD</option>
                </select> <br></div><br>
            <div> Email ID : <input type="email" style="border-radius: 4px;"> <br></div><br>

            <div>
                Address : <textarea name="address" id="" rows="4" cols="15" style="border-radius: 4px;"></textarea><br>
            </div><br>
            <!-- <label for="browse">browse..</label> -->
            <label for="photo">Upload Photo :</label>
            <button type="file">Browse..</button>
            <div><br>
                &emsp;&emsp; &emsp;<button type="reset">Clear</button> &nbsp; <button type="submit">Register</button>

                <!-- <br><button type="reset">clear</button> -->



        </form>
    </table>

</body>

</html>
