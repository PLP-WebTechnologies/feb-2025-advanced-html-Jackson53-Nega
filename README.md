<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Implementation</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>
    
    <!-- External Image from Pexels -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/sample-image.jpg" alt="Sample Image from Pexels" width="500">
    
    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table border="1">
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
                <td>Mueni Muthiani</td>
                <td>123 Ngong, Nairobi</td>
                <td>+1234567890</td>
                <td>jacksonnega53@gmail.com.com</td>
            </tr>
            <tr>
                <td>Jaackson Nega</td>
                <td>456 Ngong Road, CA</td>
                <td>+1987654321</td>
                <td>jacksonnega53@gmail.com.com</td>
            </tr>
            <tr>
                <td>Stephen Nega</td>
                <td>789 Meru Rd, TX</td>
                <td>+1122334455</td>
                <td>stephennega53@gmail.com</td>
            </tr>
            <tr>
                <td>Sarah Wegesa</td>
                <td>101 Nairbi Kenya, FL</td>
                <td>+1555666777</td>
                <td>sarah@gmail.com</td>
            </tr>
            <tr>
                <td>David Chacha</td>
                <td>222 Gwikonge, WA</td>
                <td>+1444333222</td>
                <td>david@gmail.com</td>
            </tr>
        </tbody>
    </table>
    
    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
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
        
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male"> Male
        <input type="radio" id="female" name="gender" value="female"> Female
        <br><br>
        
        <label for="interests">Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports"> Sports
        <input type="checkbox" id="music" name="interests" value="music"> Music
        <input type="checkbox" id="reading" name="interests" value="reading"> Reading
        <br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select a country</option>
            <option value="usa">KE</option>
            <option value="uk">TZ</option>
            <option value="UGanda">Canada</option>
            <option value="Nigeria">Nigeria</option>
        </select>
        <br><br>
        
        <button type="submit">Register</button>
    </form>
    
    <!-- Audio and Video Elements -->
    <h2>Multimedia Elements</h2>
    
    <h3>Audio</h3>
    <audio controls>
        <source src="sample-audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    
    <h3>Video</h3>
    <video width="500" controls>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</body>
</html>
