# Default configuration for Islandora Group module

This module contain default configuration for [Islandora Group module](https://github.com/digitalutsc/islandora-group).

## How to setup 

Follow this document https://docs.google.com/document/d/1fy2KyjlURBpseLbwqspD3Yv5iFPpv1HQF_qKClV7zso/edit?usp=sharing for setting up testing evironment for the access control:

### Collection Based Access Control Setup
  - **Restricted Collection 1** with the following group roles:
     - Anonymous cannot view. 
     - Collection Manager: can create, edit, view
     - General User (ie. cataloguer) can view.
     - Administrator: can create, edit, view, and delete.

  - **Restricted Collection 2** with the following group roles:
     - Anonymous has the ability to view.
     - Collection Manager: can create, edit, view
     - General User (ie. cataloguer): can edit and view
     - Administrator: can create, edit, view, and delete.

  - **Restricted Collection 3** with the following group roles: 
     - Anonymous cannot view. 
     - Collection Manager: can create, edit, view and delete.
     - General User (ie. cataloguer): cannot view
     - Administrator: can create, edit, view, and delete.
     
### Role Based Access Control Setup
  - Anonymous: View
  - Collection Manager: View, Edit, Create assigned collections/items
  - Collection Manager 2: View, Edit, Create, Delete assigned collections/items
  - Authenticated User: View assigned collections/items
  - Admin: CRUD all items


