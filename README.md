# Lab-1_202001270

# Q1) Library Information System (LIS)
**A) Functional Requirements:**

   i) A user should have an option to login with either username or email and password to show that he/she is a valid user of the LIS.
   
  ii) A user should be able to search for books with any one or a combination of book name, author, publisher, publication number, volume, subject.
  
 iii) System should allow user to request for a book (if not already available in the library).
 
  iv) The interface should allow a user to borrow and return a book with ease.
  
   v) The interface should allow a user to extend the date of borrowing for a book if there is no other booking for that particular book.
   
  vi) The interface should allow an administrator of the system to add a book to the system and make it available for all the users.
  
 vii) The interface should also allow an administrator to remove a book from the system in the scenario that book is not longer available in the library.
 
viii) The system should be deployed to work on institute LAN only.


**B) Non-functional requirements:**

  i) Security: System should have some kind of encryption method to ensure confidential information is not stored in plain text form.
  
 ii) Scalibility: System should be scalable to ensure smooth running when the number of users increase in the future.
 
iii) Access Privilage: The sytem should have a way to assign different roles and privileges to users like administrator, IT etc.

 iv) Speed: The system should have good performance and should produce responses within reasonable amount of time.
 
  v) Ease of use: The system should be easy to use for users.
  
 vi) Reliable: The system should be reliable like now allowing a user to borrow a book when it's already being borrowed by some other user, and should work accurately  with searching, authentication etc. by updating the database by synchronizing between database and application.


# Q2) Scope, features and non-functional aspects hearing aid application

**A) Scope:**

Approximately 5% of the total world population i.e. a stagerring 466 million people are suffering from hearing disability. Their health and safety is a huge point of concern. To ensure their safety and also to track their treatment progress, a mobile application can prove to be very beneficial. The mobile application can use cloud technology to store the results hearing tests performed by the user previously and provide tracking data to monitor their hearing condition. The tracking data would be beneficial to show that if the user is undergoing some traetment then the treatment is working well or not. The application would also have safety features for the user. These features would include the signalling the user by vibration if cars are honking nearby. This would alert the user if he is crossing a road. The application would also detect the sound a babies in case a baby is lost and is somewhere around. There are many more advantages of this application so its scope is very wide.


**B) Functional Requirements:**

Requiremnts for users with hearing disability:

  i) To be able to login to their account.
  
 ii) To be able to check their past tests data.
 
iii) To be able to track the progress of the ongoing treatment if any.

 iv) To be able to share his test data with his doctor.
 
  v) To be able to turn on road crossing mode where he would get alert signals if a car is honking nearby.
  
 vi) To be able to get alert signal if a baby is crying nearby.
 
Requirements for doctors:

  i) To be able to track the data of their patient.
  
 ii) To be able to notify his patient about further treatment process and tests to be perfomrmed.


**C) Non Functional Requirements:**

i) Safety:

The system should be durable. In case of any system crash/failure, user data must not be lost. Backup should be available.

ii) Security:

There are 2 types of users - patient and doctor. So abstractness must be maintained between the users.

iii) Software Quality and Interface Requirements:

The interface should be made in a user friendly way where he must not be made thinking where to find a particular option or what to do after performing a specific action. New users should also not get irritated after using the system.
