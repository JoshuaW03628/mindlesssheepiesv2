# How to Idiot Proof Login

### Code

// idiot-proofing
    if (pwd === "") {
        document.getElementById('pswd').placeholder = "Please Enter A Password";
        document.getElementById('pswd').style.borderBottomColor = "red";
    }

- Essentially what this is doing is making it so that the password input must match with the UID