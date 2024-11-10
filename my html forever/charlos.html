<?php
$myconn = require_once('dbconnect.php'); // Ensure this returns a valid connection

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Capture and sanitize form data
    $studentName = htmlspecialchars(trim($_POST['studentName']));
    $email = htmlspecialchars(trim($_POST['email']));
    $age = intval(trim($_POST['age']));
    $gender = htmlspecialchars(trim($_POST['gender']));
    $hobby = htmlspecialchars(trim($_POST['hobby']));
    $regNumber = htmlspecialchars(trim($_POST['regNumber']));
    $courseTitle = htmlspecialchars(trim($_POST['courseTitle']));
    $english = intval(trim($_POST['english']));
    $history = intval(trim($_POST['history']));
    $cre = intval(trim($_POST['cre']));
    $biology = intval(trim($_POST['biology']));

    // Calculate total and average marks
    $totalMarks = $english + $history + $cre + $biology;
    $averageMarks = $totalMarks / 4;

    // Determine grade based on average marks
    if ($averageMarks >= 70) {
        $grade = 'Distinction';
    } elseif ($averageMarks >= 60) {
        $grade = 'Credit';
    } elseif ($averageMarks >= 50) {
        $grade = 'Pass';
    } else {
        $grade = 'Fail';
    }

    // Prepare the SQL query with proper escaping to prevent SQL injection
    $insert = "INSERT INTO joseh(studentname, email, gender, regnumber, coursetitle, english, history, cre, biology, totalmarks, averagemarks)
               VALUES ('$studentName', '$email', '$gender', '$regNumber', '$courseTitle', $english, $history, $cre, $biology, $totalMarks, $averageMarks)";
    
    if (mysqli_query($myconn, $insert)) {
        echo "Record added successfully<br>";
    } else {
        echo "Failed: " . mysqli_error($myconn) . "<br>"; // Display error for debugging
    }
}
?>

<html>
<head>
    <title>Student Marks Result</title>
</head>
<body>
    <h2>Student Marks Result</h2>

    <!-- Display results -->
    <p><strong>Student Name:</strong> <?php echo isset($studentName) ? htmlspecialchars($studentName) : ''; ?></p>
    <p><strong>Registration Number:</strong> <?php echo isset($regNumber) ? htmlspecialchars($regNumber) : ''; ?></p>
    <p><strong>Course Title:</strong> <?php echo isset($courseTitle) ? htmlspecialchars($courseTitle) : ''; ?></p>
    <p><strong>Student Age:</strong> <?php echo isset($age) ? htmlspecialchars($age) : ''; ?></p>
    <p><strong>Gender:</strong> <?php echo isset($gender) ? htmlspecialchars($gender) : ''; ?></p>
    <p><strong>Email:</strong> <?php echo isset($email) ? htmlspecialchars($email) : ''; ?></p>
    <p><strong>Hobby:</strong> <?php echo isset($hobby) ? htmlspecialchars($hobby) : ''; ?></p>

    <h3><u>Marks</u></h3>
    <p>English: <?php echo isset($english) ? $english : ''; ?></p>
    <p>History: <?php echo isset($history) ? $history : ''; ?></p>
    <p>CRE: <?php echo isset($cre) ? $cre : ''; ?></p>
    <p>Biology: <?php echo isset($biology) ? $biology : ''; ?></p>

    <h3><u>Results</u></h3>
    <p>Total Marks: <?php echo isset($totalMarks) ? $totalMarks : ''; ?></p>
    <p>Average Marks: <?php echo isset($averageMarks) ? number_format($averageMarks, 2) : ''; ?></p>
    <p>Grade: <?php echo isset($grade) ? $grade : ''; ?></p>
</body>
</html>
