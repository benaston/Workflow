On Call Cheatsheet
========

Login Problems
----------------
 - Ask what browser they are using
 - Ask the user to retry
 - Note down their name and username
 - send an email marked as 'Urgent' to `rbitechnology.accountmanagement@rbi.co.uk`, with `rbitechnology.servicedesk@rbi.co.uk cc'd` requesting their addition to the group RBI-QHS-SECURITY-ICIS-DARWIN-EDITORIAL
 
Unable to Save
---------------
 - Try again - there are ocassionally intermittent problems
 - Check the deadline in the onboarding tool corresponds to the deadline with the history in ICIS London

Table Formatting
----------------
 - File everything you can in Darwin and the table in legacy. P&D will merge the result.
 
Report Not In Darwin
--------------
 - ask "are your region filters set correctly?"
 - check the onboarding tool, confirm that the date of the report is as expected

General
--------
 - URLs may be typed in wrong the correct URL is: https://editorial.darwin.b2b.regn.net

 
Browser Related 
-----------------
 - They should install Chrome, if they can't then they should call helpdesk on 3696 who can install Chrome for them






Workflow
========

 powershell ./Src/b.ps1 t
 
 for $doc in doc() return xdmp:document-delete(xdmp:node-uri($doc))
 
 xquery version "1.0-ml";

let $d := collection('Preferences')
return $d;