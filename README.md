#This modules adds some functionalities to the issues for AbAKUS. 

Functionalities:
---
    - Auto sets the "Assigned" stage when a person is assigned.
    - Adds a due date field.
    - Moves the project field on the upper side.
    - Adds 2 server actions: 
        - Project issue email matching. It sets the project from an email issue
        - Project issue email matching + email to SM
    - Adds "My Issues" and "Unassigned Issues" menuitems in Project.
    - Removes "Issues" menuitem from the project module.
    - Replaces priority stars selection by a normal name selection in the issue form.
    - Replaces priority stars in kanban view by the priority name.

This module has been developed by Bernard Delhez, intern @ AbAKUS it-solutions, under the control of Valentin Thirion.

Latest UPDATES 2015-08-07:
    - corrections in 2 server actions:
        - contact is set now
        - BL project check
        - check partner contacts email then partner email

UPDATES 2015-04-13:
    - Merging modules in this module: 
        - project_issue_remove_star_widget
        - project_issue_form
    - New server action for email matching.