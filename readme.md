# Web Application Functionality and Hosting Guide

**Made by UZAIRxDEV223**
**Markdown script by ChatGPT**

## Overview

This guide provides an overview of the web application's functionalities and instructions for hosting it on InfinityFree. Additionally, it includes links to video demonstrations of various features.
[Visit This](https://for-myuse.infinityfreeapp.com/register/index.html) to check the website without upload but i recommend you to upload it read the this article full.
## Index.html

The `index.html` file serves as the main entry point for users to sign in or sign up.

- **Sign In Form**:
  - Contains fields for email and password.
  - Links to `forgetpswd.html` if the user forgets their password.
  - Submits the form data to `signin.php`.

- **Sign Up Form**:
  - Contains fields for name, email, and password.
  - Submits the form data to `signup.php`.

- **Overlay Panel**:
  - Provides a toggle between the Sign In and Sign Up forms using JavaScript.

## signin.php

Handles the sign-in functionality.

- **Process**:
  - Reads data from `data.txt`.
  - Verifies if the provided email and password match any entry.
  - Displays a success message if a match is found or an error message if not.

## signup.php

Handles the sign-up functionality.

- **Process**:
  - Appends the provided email and password to `data.txt`.
  - Displays a success message upon account creation.

## forgetpswd.html

Provides a form for users to input their email to retrieve their password.

- **Process**:
  - Submits the email to `forgetpswd.php`.
  - Displays the retrieved password or an error message.

## forgetpswd.php

Handles the password retrieval functionality.

- **Process**:
  - Reads data from `data.txt`.
  - Checks if the provided email exists.
  - Returns the corresponding password or an error message.

## Important Note

You must create a `data.txt` file on your server to store the email and password data. Ensure this file is located in the same directory as your PHP files.

## Another Important note

You have to change "https://for-myuse.infinityfreeapp.com" with your own website so if a user login or register he will redircted to your website not mine
 
## MediaFire Links

- [index.html](https://www.mediafire.com/file/dp1jh6kxsdjtlrw/index.html/file)
- [signin.php](https://www.mediafire.com/file/l5r5yadi1xn2r18/signin.php/file)
- [signup.php](https://www.mediafire.com/file/4hsjy1cd2lgm9rm/signup.php/file)
- [forgetpswd.html](https://www.mediafire.com/file/r0bpulhzpd57t1m/forgetpswd.html/file)
- [forgetpswd.php](https://www.mediafire.com/file/ds81z9icbbf02nt/forgetpswd.php/file)
- [data.txt](https://www.mediafire.com/file/0x4qf6a5dycdhd7/data.txt/file)

## Video Demonstrations

- [1.mp4: Animation Function](1.mp4)
- [2.mp4: Forget Password Functionality](2.mp4)
- [3.mp4: Sign Up Functionality](3.mp4)

## Hosting Guide on InfinityFree

1. **Create an Account**:
   - Visit [InfinityFree](https://infinityfree.net).
   - Sign up for a free account.

2. **Set Up a New Website**:
   - Log in to your InfinityFree account.
   - Click on "Create Account" and follow the instructions to set up your domain.

3. **Upload Files**:
   - Go to the "File Manager" from the control panel.
   - Navigate to the `htdocs` directory.
   - Upload `index.html`, `signin.php`, `signup.php`, `forgetpswd.html`, `forgetpswd.php`, and `data.txt` files to this directory.

4. **Configure Permissions**:
   - Ensure all PHP files have the correct permissions to execute. Typically, 644 for files and 755 for directories.

5. **Access Your Website**:
   - Visit your domain to ensure everything is working correctly.
   - Test the sign-up, sign-in, and password recovery functionalities to verify proper setup.

If you encounter any issues, tell me in the issue section.
