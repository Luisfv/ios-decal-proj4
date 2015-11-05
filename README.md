# ios-decal-proj4

# Habanow
*   Luis Vasquez
## Purpose
Habanow is a mobile app for people to make quick plans with friends and get invited to their events.  
## Features
* invite friends to events with minimal work
* organize friends in groups for mass invitations
* friends only get invitations if they are subscribed to you or your group
## Control Flow
* Users begin at a screen showing them upcoming events they're invited to after logging in with facebook. They can click on the event to see more details or tap a button to start an event. A popup will guide them through creating an event efficiently. Then the user can choose who to invite from their subscribers or groups. Users will get notifications and optionally respond.
## Implementation
### Model
* Subscription.swift
* User.swift
* Event.swift
### View
* EventTableView
* EventPopupView
* UserProfileView
### Controller
* EventTableViewController
* UserProfileViewController


project4
