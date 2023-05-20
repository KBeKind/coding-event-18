# coding-event-18

This app is for setting up events.


The app is basic right now and can set up an event but not much other functionality


I am supposed to talk about adding a Person class here because that is a future improvement.

Person fields:

id (int) - the unique user ID

firstName (String) - the user’s first name

lastName (String) - the user’s last name

email (String) - the user’s email, which will also function as their username

password (String) - the user’s password

The class would need getters for all of these fields. It could have setters for all fields except id (since it shouldn’t change).

The Person class might also have the following references:

PersonProfile - a class to gather up all of the profile information about the user

List<Events> eventsAttending - to store events the user wants to attend

List<Events> eventsOwned - a different list, to store the events the user has created

Person would have a many-to-many relationship with Event via List<Events> eventsAttending. It would have a one-to-many relationship with Event via List<Events> eventsOwned.
