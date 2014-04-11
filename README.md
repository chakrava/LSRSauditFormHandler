LSRSauditFormHandler
====================

A set of Google App Scripts to manage a set of Google Forms.

Overview
-
Educause (educause.edu) has established the LSRS (Learning Space Rating System) initiative to rate learning spaces such as classrooms and labs on their effectiveness towards active learning.  The classroom technology department at Southern Polytechnic State University (SPSU.edu) began incorporating the LSRS initiative, using the provided resources to design a set of Google Forms and Sheets.

The LSRSauditFormHandler is a set of app script (a cloud-based scripting language based on Javascript) to manage and improve the interactions between the Google Form and the Sheet.  The scripts improve the basic functionality of Google's Apps by adding support to edit previously submitted forms, improve the layout of resulting spreadsheet, and handle creating and filling custom-templates to display and analyze the data.

This project has no affiliation with, but uses resources provided by (under the Creative Commons Attribution License 3.0), Educause.

More information about the LSRS initiative can be found at: http://www.educause.edu/eli/initiatives/learning-space-rating-system

-
Google Forms provide a free, versatile way to collect information, and can easily export collected data to a variety of forms.  However, there are many features absent from Google Forms that prevent it from being a more powerful tool.

The default behavior when a Form is submitted is to put the information in a Sheet (Google Spreadsheet).  There is no easy way to go back and edit an existing response to a form, and there is no way (without custom scripts such as this) to automatically create custom-sheets from the resulting data.

The LSRSauditFormHandler solves these problems with no interaction of the user beyond simply filling out the forms.  When a form is submitted the data is pulled onto the master spreadsheet, and a copy of the room-template is created and filled out with the submitted data.  The master spreadsheet includes clickable URLs that pull up previous submissions to be edited to correct errors or update.  Any changes made are automatically updated on the master spreadsheet and the individual room form created earlier.
