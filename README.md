BootStrap---A2Billing-templates
===============================

Custom templates using the Twitter Bootstrap 2.0 API to enhance A2billing UI templates.
Basically I dislike how the A2billing GUI looks like. 
I was looking for a clean design, reusable, liquid layout / table less, open source and easy to implement solution. 
For sure there are many other options/frameworks, but I dediced to give it a try to Twitter Bootstrap 2.0 http://twitter.github.com/bootstrap/

In order to install these templates, you have 2 alternatives:

1 - Create a new folder name at the same level as default, for example for the customer UI would be here /var/www/html/a2billing/customer/templates/. 
    Then you would have to create a script to change the SKIN_NAME variable in all files. Sorry but I did not try this way since it was so time consuming given my sed my expertise. Also I could not find an easy way to change this value on one place neither a blog that explains how to do it. The only reference found was to develop a scrip to make the changes and be able to reuse it when upgrading A2billing.
2 - Backup your default folder and overwrite the *.tpl files. No further changes are required. Just refresh your browser. Remember that smarty will recompile your template when it checks that the time stamp is different.

By the way, this was developed for A2Billing version 1.9.4

