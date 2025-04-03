# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Forms and Multimedia</title>
</head>
<body>

<!-- Content goes here -->

</body>
</html>


- Add an ordered list with roman numerals
!-- Ordered List with Roman Numerals -->
<ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
    <li>Item 4</li>
    <li>Item 5</li>
</ol>


- Add an external image from pexels.com
- 
!-- External Image from Pexels -->
<img src="https://www.pexels.com/photo/landscape-photography-of-trees-and-hills-1778092/" alt="Beautiful landscape" width="500">


- Add a table of 5 contacts with; name, address, mobile and emails
<!-- Contacts Table -->
<table border="1">
    <caption>Contact Information</caption>
    <thead>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>123 Elm St, Springfield</td>
            <td>(123) 456-7890</td>
            <td>john.doe@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Oak Ave, Metropolis</td>
            <td>(234) 567-8901</td>
            <td>jane.smith@example.com</td>
        </tr>
        <tr>
            <td>Alex Johnson</td>
            <td>789 Pine Rd, Gotham</td>
            <td>(345) 678-9012</td>
            <td>alex.johnson@example.com</td>
        </tr>
        <tr>
            <td>Maria Lee</td>
            <td>101 Maple Ln, Star City</td>
            <td>(456) 789-0123</td>
            <td>maria.lee@example.com</td>
        </tr>
        <tr>
            <td>David Clark</td>
            <td>202 Birch Dr, Central City</td>
            <td>(567) 890-1234</td>
            <td>david.clark@example.com</td>
        </tr>
    </tbody>
</table>

- Add a registration form
<!-- Registration Form -->
<h2>Registration Form</h2>
<form action="#" method="post">
    <!-- Name Field -->
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>
    <br><br>

    <!-- Email Field -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>
    <br><br>

    <!-- Password Field -->
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required>
    <br><br>

    <!-- Date Field -->
    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>
    <br><br>

    <!-- Dropdown -->
    <label for="country">Country:</label>
    <select id="country" name="country" required>
        <option value="">Select your country</option>
        <option value="USA">USA</option>
        <option value="Canada">Canada</option>
        <option value="UK">UK</option>
    </select>
    <br><br>

    <!-- Radio Buttons -->
    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label>
    <br><br>

    <!-- Checkboxes -->
    <label for="subscribe">Subscribe to newsletter:</label>
    <input type="checkbox" id="subscribe" name="subscribe" value="yes">
    <br><br>

    <!-- Submit Button -->
    <input type="submit" value="Register">
</form>

Full HTML File Example

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Forms and Multimedia</title>
</head>
<body>

<!-- Ordered List with Roman Numerals -->
<ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
    <li>Item 4</li>
    <li>Item 5</li>
</ol>

<!-- External Image from Pexels -->
<img src="https://www.pexels.com/photo/landscape-photography-of-trees-and-hills-1778092/" alt="Beautiful landscape" width="500">

<!-- Contacts Table -->
<table border="1">
    <caption>Contact Information</caption>
    <thead>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John Doe</td>
            <td>123 Elm St, Springfield</td>
            <td>(123) 456-7890</td>
            <td>john.doe@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Oak Ave, Metropolis</td>
            <td>(234) 567-8901</td>
            <td>jane.smith@example.com</td>
        </tr>
        <tr>
            <td>Alex Johnson</td>
            <td>789 Pine Rd, Gotham</td>
            <td>(345) 678-9012</td>
            <td>alex.johnson@example.com</td>
        </tr>
        <tr>
            <td>Maria Lee</td>
            <td>101 Maple Ln, Star City</td>
            <td>(456) 789-0123</td>
            <td>maria.lee@example.com</td>
        </tr>
        <tr>
            <td>David Clark</td>
            <td>202 Birch Dr, Central City</td>
            <td>(567) 890-1234</td>
            <td>david.clark@example.com</td>
        </tr>
    </tbody>
</table>

<!-- Registration Form -->
<h2>Registration Form</h2>
<form action="#" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>
    <br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter your email" required>
    <br><br>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required>
    <br><br>

    <label for="dob">Date of Birth:</label>
    <input type="date" id="dob" name="dob" required>
    <br><br>

    <label for="country">Country:</label>
    <select id="country" name="country" required>
        <option value="">Select your country</option>
        <option value="USA">USA</option>
        <option value="Canada">Canada</option>
        <option value="UK">UK</option>
    </select>
    <br><br>

    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label>
    <br><br>

    <label for="subscribe">Subscribe to newsletter:</label>
    <input type="checkbox" id="subscribe" name="subscribe" value="yes">
    <br><br>

    <input type



>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

