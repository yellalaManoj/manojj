<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Registration Form</title>
</head>
<body>
    <h2>Employee Registration</h2>
    <form>
        <div>
            <label for="employeeId">Employee ID</label>
            <input type="text" id="employeeId" name="employeeId" required>
        </div>
        <div>
            <label for="firstName">First Name</label>
            <input type="text" id="firstName" name="firstName" required>
        </div>
        <div>
            <label for="lastName">Last Name</label>
            <input type="text" id="lastName" name="lastName" required>
        </div>
        <div>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
        </div>
        <div>
            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" required>
        </div>
        <div>
            <label for="department">Department</label>
            <select id="department" name="department" required>
                <option value="">Select a department</option>
                <option value="HR">Human Resources</option>
                <option value="IT">Information Technology</option>
                <option value="Finance">Finance</option>
                <option value="Marketing">Marketing</option>
            </select>
        </div>
        <div>
            <label for="jobTitle">Job Title</label>
            <input type="text" id="jobTitle" name="jobTitle" required>
        </div>
        <div>
            <label for="dateOfJoining">Date of Joining</label>
            <input type="date" id="dateOfJoining" name="dateOfJoining" required>
        </div>
        <div>
            <button type="submit">Register</button>
        </div>
    </form>
</body>
</html>
