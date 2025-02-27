* This workflow modifies problem notification settings, so be sure of your variable values and test in NonProd if possible. I recommend commenting out the calls to the ``putSettingsObjectById`` endpoint and running the Workflow as a dry
* run to validate which notifications will be updated.
  
The ``Update ServiceNow notification user and password`` Workflow updates the password for all ServiceNow notifications of a given ServiceNow tenant.

Pre-Reqs:
1. In the ``update_pw`` task, specify the ServiceNow instance name and the new password.
