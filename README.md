# -Fake-PawPatrol
This website is designed to allow three different types of accounts to log-in;admin, volunteer, and owner. The admin accounts can not
be created unless directly inserting them into the database itself. However, the volunteers and owners can register freely. 

Admin
 -delete appointment
 -deactivate and reactivate users
 -search appointmets
 
Volunteer
 -register/unregister for appointments
 -lookup appointments that they hacve already registered for
  
Owner
 -create/delete appointments
 -lookup appointments they have already made
 
Assumptions
 -The owners won't have walking go passed midnight
 -The email they are using is their most frequented email
 -The owners will contact the volunteers directly when cancelling
 -Volunteers will find their own replacements when they can't make an appointment
 
Known Bugs/Suggested fixes
 -Searching appointments while having input in both boxes doesn't work properly
 -PHP code is redundent and could be merged to fewer files
 -HTML files could also be condensed
 -Passwords aren't hashed in database for testing and validation purposes, but should be implemented 
 -Appointment out put should be sorted earliest to latest
 -Browse alerts should be replaced with red text above input boxes when login/registration fails
