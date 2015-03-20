# DNHAdmin Wordpress Plugin Proof Of Concept
This PoC demonstrates a possible design pattern for a plgin that can manage a certain MySQL table, with respect to the Wordpress look-and-feel. 

## Features
- A Table that lists all rows of a table, using the WP_List_Table class
- An 'insert new' button that directs the user to a form page, where the user can enter data and insert a new row in the table
- Edit link for each row, that directs the user to a form page, where the user can change data and update a row in the table
- Delete link for each row, that directs the user to a form page, where the user can change options for data integrity when deleting items
- Bulk opereations for deleting
- A fairly generic mechanism for showing Admin notices on success or error.

## How to Install

### Prerequisites
Wordpress should be installed on your (localhost) webserver

### Installation steps
The only procedure I wish to document is by downloading the zip. Cloning or other possible ways you can figure out yourself
1. Download the ZIP
2. Copy the dnhadmin folder into the folder /wp-content/plugins of your Wordpress installation
3. Import the dnhadmin.sql script into your Wordpress database using PHPMyadmin or your favorite MySQL admin tool
4. Select the DNHAdmin menu in the backend of your Wordpress site. It should work now.

Note: this code is primarily intended for HZ students for a certain case and is therefore partly in Dutch. But, feel free to suggest improvements for better code.
