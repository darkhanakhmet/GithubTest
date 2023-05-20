#html
    <!DOCTYPE html> 
    <html> 
    <head> 
    <title>Online Application Form</title> 
    <style> 
        .error { 
        color: red; 
        } 
    </style> 
    </head> 
    <body> 
    <h1>RACE REGISTRATION FORM</h1> 
    <form id="applicationForm" onsubmit="return validateForm()"> 
        <div> 
        <label for="email">E-mail:</label> 
        <input type="email" id="email" required>  
        </div> 
        <div> 
        <br> <label for="title">Title:</label> 
        <select id="title" required> 
        <option value="">Select a title</option> 
            <option value="Mr.">Mr.</option> 
            <option value="Mrs.">Mrs.</option> 
            <option value="Ms.">Ms.</option> 
        </select> 
        </div> 
        <div> 
            <br> <label for="firstName">First Name:</label> 
        <input type="text" id="firstName" pattern="[A-Za-z]+" required> 
        </div> 
        <div> 
            <br> <label for="lastName">Last Name:</label> 
        <input type="text" id="lastName" pattern="[A-Za-z]+" required> 
        </div> 
        <div>
            <br> <label for="address">Address:</label>
            <input type="text" id="address" required>
        </div>
        <div>
            <br> <label for="city">City:</label>
            <input type="text" id="city" required>
        </div>
        <div>
            <br> <label for="state">State:</label>
            <input type="text" id="state" required>
        </div>
        <div>
            <br> <label for="zip">Zip Code:</label>
            <input type="text" id="zip" pattern="[0-9]{5}" required>
        </div>
        </div> 
        <div> 
            <br> <label for="phone">Phone:</label> 
        <input type="tel" id="phone" pattern="[8]\d{9}" required> 
        </div> 
        <div> 
            <br> <label for="fax">Fax:</label> 
        <input type="tel" id="fax" pattern="[8]\d{9}\(\d{3}\)" required> 
        </div> 
        <div> 
            <br><label for="maritalStatus">Marital Status:</label> 
        <select id="maritalStatus" required> 
            <option value="">Select marital status</option> 
            <option value="Single">Single</option> 
            <option value="Married">Married</option> 
            <option value="Divorced">Divorced</option> 
            <option value="Widowed">Widowed</option> 
        </select> 
        </div> 
        <div> 
            <br><label for="roomSharingPreference">Room Sharing Preference:</label> 
        <select id="roomSharingPreference" required> 
            <option value="">Select room sharing preference</option> 
            <option value="Single Room">Single Room</option> 
            <option value="Double Room">Double Room</option> 
            <option value="Shared Room">Shared Room</option> 
        </select> 
        </div> 
        <div> 
            <br> <label for="age">Age:</label> 
        <input type="number" id="age" min="2" max="69" required> 
        </div> 
        <div> 
            <br> <label for="birthdate">Date of Birth:</label> 
        <input type="date" id="birthdate" required> 
        </div> 
        <div> 
            <br> <label for="tshirtSize">T-Shirt Size:</label> 
        <input type="text" id="tshirtSize"> 
        </div> 
        <h3>Passport Details</h3>
        <div> 
            <label for="passport">Exact name as it appears:</label> 
            <input type="passport" id="passport" required>  
        </div>
        <div> 
            <br> <label for="number">Number:</label> 
            <input type="number" id="number" required>  
        </div> 
        <div> 
            <br> <label for="date">Date Issued:</label> 
        <input type="date" id="date" required>  
        </div> 
        <div> 
            <br> <label for="country">Where Issued:</label> 
            <input type="countrt" id="country" required>  
        </div> 
        <div> 
            <br> <label for="date">Date Expired:</label> 
        <input type="date" id="date" required>  
        </div> 
        <form id="applicationForm" onsubmit="return validateForm()"> 
            <button type="submit">Send</button> 
        </form>
    
        <script>
            function validateForm() {
                alert("Congratulations! You successfully registered.");
                return false;
            }
        </script>
        
    </form>
    #dfjdkvkdd
