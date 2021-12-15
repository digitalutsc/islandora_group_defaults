# Testing Setup for Islandora Group module

This module contain exported config which simulated three collections, and three users. User 1 has the role “collection manager” and User 2 has the role “authenticated user,” and user 3 has the role “administrator.” Public users have the “anonymous” role. 

- Collection Based Access Control Setup
  - Restricted Collection 1 with the following group roles:
     - Anonymous cannot view. 
     - Collection Manager: can create, edit, view
     - General User (ie. cataloguer) can view.
     - Administrator: can create, edit, view, and delete.

  - Restricted Collection 2 with the following group roles:
     - Anonymous has the ability to view.
     - Collection Manager: can create, edit, view
     - General User (ie. cataloguer): can edit and view
     - Administrator: can create, edit, view, and delete.

  - Restricted Collection 3 with the following group roles: 
     - Anonymous cannot view. 
     - Collection Manager: can create, edit, view and delete.
     - General User (ie. cataloguer): cannot view
     - Administrator: can create, edit, view, and delete.
     
- Role Based Access Control Setup
  - Anonymous: View
  - Collection Manager: View, Edit, Create assigned collections/items
  - Collection Manager 2: View, Edit, Create, Delete assigned collections/items
  - Authenticated User: View assigned collections/items
  - Admin: CRUD all items

## How to setup 

https://docs.google.com/document/d/1fy2KyjlURBpseLbwqspD3Yv5iFPpv1HQF_qKClV7zso/edit?usp=sharing
