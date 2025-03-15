# PHP Login and Signup Form Instructions

This is a simple PHP login and signup system. Follow these instructions to set it up on your local machine using XAMPP.

## Prerequisites

- **XAMPP** installed on your local machine (Apache, MySQL, PHP)
- A **web browser** (Chrome, Firefox, etc.)

## Step-by-Step Instructions

### 1. Install XAMPP

1. **Download XAMPP** from the official website:  
   [XAMPP Download](https://www.apachefriends.org/index.html)
2. Install **XAMPP** on your system following the installation prompts.

3. Open **XAMPP Control Panel** and start both **Apache** and **MySQL**.

### 2. Clone or Download the Repository

1. Visit the **GitHub repository** where the PHP login and signup form code is hosted.  
   ([Use the link you have for the GitHub repository.](https://github.com/eiirikr/signup_login))

2. **Download the repository as a ZIP file**:
   - Click on the **Code** button on the repository page.
   - Select **Download ZIP**.
3. **Extract the ZIP file** to your system.

4. Move the extracted folder to the `htdocs` directory of XAMPP:
   - The default path for `htdocs` is `C:\xampp\htdocs` on Windows.
   - Move the extracted folder (e.g., `login-register`) into this directory.

### 3. Set Up the Database in phpMyAdmin

1. Open **XAMPP Control Panel** and make sure **Apache** and **MySQL** are running.

2. Open your **web browser** and go to the following URL:  
   [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)

3. Once you're in **phpMyAdmin**, follow these steps:

   - Click on **Databases** in the top menu.
   - Under **Create database**, enter the name `login_register` and click **Create**.

4. Now, import the SQL file:

   - With the `login_register` database selected, click the **Import** tab.
   - In the **File to Import** section, click **Choose File**.
   - Navigate to `C:\xampp\htdocs\login-register` (or the directory where you extracted the files) and select the `login_register.sql` file.
   - Click **Go** to import the database.

5. If everything is green and shows **"Import has been successfully finished"**, you're all set with the database.

### 4. Access the Signup Form

1. Open a new tab in your browser.

2. Go to the following URL:  
   [http://localhost/login-register/signup.php](http://localhost/login-register/signup.php)

3. The PHP login and signup form should now be running successfully!

### 5. Done!

You can now register new users using the signup form. After registration, you can modify or extend the functionality to include a login feature, validate user input, or customize the form as needed.

---

If you face any issues, make sure that the Apache and MySQL services are running in the XAMPP Control Panel and that you have the correct file paths.

Enjoy using your PHP login and signup form!
