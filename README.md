# uispecific

<!-- headings -->
# User Page
* New User Button
    * Blue button with a plus on the left side has the word "New User" on it
    * at the left most corner
* Hide Disabled User Button
    * Right next to the new user button
    * It can be checked in and out and does not show the disabled users on the table
    * automatically checked in 
    * [x] Hide Disabled User
* Save User Button
    * gets clickable after the user info has been entered in the __New User Form__ below it
    * it is adjusted at the right most side of the page above the new user form

## Table 
* takes left half of the page comes after the new user button and hide disabled user button
* Has four columns ID, User Name, Email, Enabled
* ID starts from 1
* Each columns has their own order by option for both ways (increasing/decreasing , A->Z/Z->A)
* Enabled is a boolean -> true or false

__example is below__

| ID | User Name | Email | Enabled |
| ---|-----------|-------|---------|
| 1|AdminUser|admin@piworks.net|true|
| 2|Test User|testuser@piworks.net|true|

## New User Form
* Under the __Save User__ button
* New User tab
    * Highlighted
* Has six columns all of the boxes are across from the title
    * Username
    * Display Name
    * Phone
    * Email
    * User Roles
        * When it is clicked on the area across it the role list appears
        * Has three roles; Guest, Admin, SuperAdmin
    * Enabled
        * checkbox format


