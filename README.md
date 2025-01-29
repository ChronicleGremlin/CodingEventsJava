Persons class~

fields-
  id (int) - unique user ID
  firstName (String) - the user's first name
  lastName (String) - the user's last name
  email (String) - the user's email, which will also funtion as username
  password (String) - the user's password

getters & setters-
for all fields

PersonProfile class extends Persons - gathers progile info on user

List<Events> eventsAttending - to store events user wants to attend
~ many to many relationship with Event 

List<Events> eventsOwned - a separate list to srote events the user created
~ one to many relationship with Event 



  
