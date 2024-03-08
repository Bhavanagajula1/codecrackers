<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <navbar id="nav">
            <h1>On-Line Examination</h1>
        </navbar>
    </header>
        <main>
            <div id="menu">
                <div id="main_menu">
                    <div class="admin_menu"><a href="registration.html">Registration</a></div>
                    <div class="admin_menu"><a href="rules.html">Examination Rules</a></div>
                    <div class="admin_menu"><a href="results.html">Results</a></div>
                    <div class="admin_menu"><a href="schedule.html">Schedule</a></div>
                    <div class="admin_menu"><a href="objective.html">Objective</a></div>
                    <div class="admin_menu"><a href="subjective.html">Subjective</a></div>
                    <div class="admin_menu"><a href="test.html">Attempt test</a></div> 
                    <div class="admin_menu"><a href="registration.html" onclick="abc()">Logout</a></div>
                </div>
            </div>
            <div id="container">
                <div id="heading"><h3>REGISTRATION</h3></div>
                    <div id="form">
                        <form name="myform" onsubmit="return validateform()">
                            <div class="form-group">
                                <label for="enrollment">Enrollment No.</label><br>
                                <input type="text" id="enrollment" class="input" name="enrollment" placeholder="Enter Your Enrollment No." required>
                            </div>
                            <div class="form-group">
                                <label for="firstname">First Name</label><br>
                                <input type="text" id="first-name" class="input" name="first-name" placeholder="Enter Your First Name" required>
                            </div>
                            <div class="form-group">
                                <label for="lastname">Last Name</label><br>
                                <input type="text" id="last-name" class="input" name="last-name" placeholder="Enter Your Last Name" required>
                            </div>
                            <div class="form-group">
                                <label for="program">Program</label><br>
                                <select id="program" name="program" class="input" required>
                                    <option value="b-tech">B-Tech</option>
                                    <option value="m-tech">M-Tech</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label for="course">Course</label><br>
                                <select id="course" name="course" class="input" required>
                                    <option value="cse">Computer Science Engennering</option>
                                    <option value="ee">Electrical Engennering</option>
                                    <option value="ae">Aerospace Engennering</option>
                                    <option value="me">Machenical Engennering</option>
                                    <option value="ce">Civil Engennering</option>
                                </select>
                            </div>
                            <div class="form-group">
                                <label for="study-center-code">Study Center Code</label><br>
                                <input type="text" id="study-center-code" class="input" name="study-center-code" placeholder="Enter Your Study Center Code" required>
                            </div>
                            <div class="form-group">
                                <label for="password">Password</label><br>
                                <input type="password" id="password" class="input" name="password" placeholder="Enter Your Password" required>
                            </div>
                            <div class="form-group">
                                <label for="confirm-password">Confirm Password</label><br>
                                <input type="password" id="confirm-password" class="input" name="confirmpassword" placeholder="Confirm Your Password" required>
                            </div>
                            <div class="form-group" id="finish">
                                <button type="reset" id="finish_button">Reset</button>
                                <button type="submit" id="finish_button">Submit</button>
                            </div>
                        </form>
                    </div>
                </div>
                <div id="image">
                <img src="online exam.jpeg" width='100%'>
                </div>
            </div>
        </main>
        <script src="script.js"></script>
</body>
</html>
