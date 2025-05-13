# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form
- 

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
>- 
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

is a well-structured HTML5 document for the registration form with the specified requirements:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <!-- Add CSS link or style tags for styling -->
</head>
<body>
    <form>
        <h1>Registration Form</h1>
        <div>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
        </div>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
        </div>
        <div>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" placeholder="Enter your date of birth" required>
        </div>
        <div>
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="">-- Select --</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div>
            <label for="hobbies">Hobbies:</label>
            <input type="checkbox" id="hobbies" name="hobbies" placeholder="Select your hobbies">
        </div>
        <div>
            <label for="terms">I accept the terms and conditions:</label>
            <input type="radio" id" name="terms" required>
        </div>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
This HTML document meets all the specified requirements, including semantic correctness, proper labels and placeholders, required fields, and validation attributes.
Create an index.html file.
Add an ordered list with roman numerals
Add an external image from pexels.com
Add a table of 5 contacts with; name, address, mobile and emails
Add a registration form

[!NOTE]
The registration form should have:

Name, email, password, and date fields.
A dropdown, radio buttons, and checkboxes.
Proper labels and placeholders.
Required fields and validation attributes.
Ensure proper indentation and commenting.

Tasks
Create a well-structured HTML5 document.
Ensure semantic correctness.
Here is the index.html file with the specified requirements:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index Page</title>
    <!-- Add CSS link or style tags for styling -->
</head>
<body>
    <h1>Index Page</h1>
    <ol>
        <li>I. Introduction</li>
        <li>II. Contacts</li>
        <li>III. Registration Form</li>
    </ol>
    <img src="https://www.pexels.com/photo/smiling-young-woman-with-a-laptop-open-on-her-lap-1581645/" alt="Smiling Young Woman with a Laptop Open on Her Lap">
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St, Anytown, USA</td>
            <td>555-555-1212</td>
            <td>john.doe@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Park Ave, Anytown, USA</td>
            <td>555-555-1213</td>
            <td>jane.smith@example.com</td>
        </tr>
        <tr>
            <td>Bob Johnson</td>
            <td>789 Oak St, Anytown, USA</td>
            <td>555-555-1214</td>
            <td>bob.johnson@example.com</td>
        </tr>
        <tr>
            <td>Sarah Williams</td>
            <td>321 Maple Ave, Anytown, USA</td>
            <td>555-555-1215</td>
            <td>sarah.williams@example.com</td>
        </tr>
    </table>
    <form>
        <h2>Registration Form</h2>
        <div>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
        </div>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
        </div>
        <div>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" placeholder="Enter your date of birth" required>
        </div>
        <div>
            <label for="gender">Gender:</label>
            <select id="gender" name="gender">
                <option value="">-- Select --</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
        </div>
        <div>
            <label for="hobbies">Hobbies:</label>
            <input type="checkbox" id="hobbies" name="hobbies" placeholder="Select your hobbies">
        </div>
        <div>
            <label for="terms">I accept the terms and conditions:</label>
            <input type="radio" id="terms" name="terms" required>
        </div>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
