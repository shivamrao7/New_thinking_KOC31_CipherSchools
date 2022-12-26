<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exam Portal</title>
    <style>
        button{
            margin: 30px 0 10px 30px;
            height:100%;
            font-size: 28px;
        }
        body{
            background:url("https://images.unsplash.com/photo-1472289065668-ce650ac443d2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2069&q=80") ;
            background-size: cover;
        }
        .t{
        position:absolute;
        top:200px;
        right: 10px;
        margin-right: 30px;
        font-size: 28px;
        }
    </style>
</head>
<body>
    <header style="font-size: 40px; margin: 40px; color: brown;"><u><strong>ONLINE EXAM PORTAL</strong></u></header>
    <main >
        <a style="background-color: rgb(15, 232, 236);" href="#"><button>Student Management</button></a><br><br>
        <a style="background-color: green; href="#"><button>Question Management</button></a><br><br>
        <a style="background-color: red; href="#"><button>Subject Management</button></a><br><br>
        <a style="background-color: rgb(137, 5, 252); href="#"><button>Examination Management</button></a><br><br>


        <div class="t">     

            <div>
                <label for="Select">LOG In:</label>
    
                <select  id="Select">
                 <option value="Student">Student</option>
                 <option value="Faculty">Faculty</option>
                </select> 
                 <br><br>
            </div>

             <label for="Username">Username:</label>
            <input type="Username"  id="Username" placeholder="Username" required><br><br>

            <label for="Password">Password:</label>
            <input type="Password" id="Password" placeholder="Password" required><br><br>
            
            <button type="submit" class="signupbtn">Log In</button>
        </div>
               
    </main>    

</body>
</html>
