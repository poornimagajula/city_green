# City Green

It's an NGO, to provide plants according to your free time,
by using **City Green** can tell us about your voluntary time to do for Plantation.

# Requirements
1. Volunteer Sign-Up page.
2. Volunteer Sign-In page.
3. Admin Sign-In page.
4. Planting followup form.

# Use Cases

 ## I.Volunteer Sign-Up
 
 ### 1.Brief Description
      This Use Case describes how a Volunteer Sign-Up into the City Green form.
      
 ### 2.Flow Of Events
      The Use Case begins when the Volunteer types her/his First name, Second name, User Id, email, 
      location, gender and Password on the Sign-Up form.
      
   #### 2.1 Basic Flow - SignUP
      The System receives the Volunteer Input fields and takes his/her details into DataBase, and 
      takes Volunteer in to Login Page.
      
   #### 2.2 Alternative Flow - SignUP
      User Already Exist. 
      If the User ID is alreaady exists in the Basic flow Signup, the system shows User already exist 
      try another UserID/MailID.
  
  ## II.Volunteer Sign-In
 
 ### 1.Brief Description
      This Use Case describes how a Volunteer Sign-In into the City Green form.
      
 ### 2.Flow Of Events
      The Use Case begins when the Volunteer types her/his Userid/mail/phonenumber and Password on the Sign-In form.
      
   #### 2.1 Basic Flow - SignIn
      The System validates the Volunteer's user_id and password and logs him/her into the Application and 
      takes Volunteer in to Planting details form.
      
   #### 2.2 Alternative Flow - SignIn
      Invalid Username / Password. 
      If the User ID is alreaady exists in the Basic flow Signup, the system shows User already exist 
      try another UserID/MailID.

# Design

# Table

# Test Cases
