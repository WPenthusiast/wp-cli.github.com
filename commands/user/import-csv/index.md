---
layout: default
title: 'wp user import-csv'
display_global_parameters: true
---

`wp user import-csv` - Import users from a CSV file.

<hr />

### OPTIONS

&lt;file&gt;
: The local or remote CSV file of users to import.

[\--send-email]
: Send an email to new users with their account details.

[\--skip-update]
: Don't update users that already exist.

### EXAMPLES

    wp user import-csv /path/to/users.csv
    wp user import-csv http://example.com/users.csv

    Sample users.csv file:

    user_login,user_email,display_name,role
    bobjones,bobjones@example.com,Bob Jones,contributor
    newuser1,newuser1@example.com,New User,author
    existinguser,existinguser@example.com,Existing User,administrator



