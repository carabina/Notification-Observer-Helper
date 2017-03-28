# Notification-Observer-Helper
When using block based API to register as an observer for notification from NSNotificationCenter, we will have to remove observer manually. 

This utility aims at solving this problem. 

1)Create a instance of NotificationObserver class with the notification you want to register
2)Hold a reference to it as long as you need it

and voila you are done.

Don't ever worry about removing observer again!!!

The above code contains 

1)An example project
2)Tests to validate it

Please look into NotificationObserverHelper.swift for more details.

The advantages i have had so far 

- Register as observer for all your notification at one place.
- Makes code more readable as we do not create any more functions to register as selectors.
- We use a block based API and thus makes it easy to use and declarative.