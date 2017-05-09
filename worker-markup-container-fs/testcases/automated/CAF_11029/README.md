## CAF_11029 - Markup Worker support for Hotmail ##

Process plain text from email threads which is derived from emails sent from Hotmail

**Test Steps**

1. Send plain text from Hotmail email threads into the Markup worker.
2. Examine output

**Test Data**

Variety of plain text derived from Hotmail email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the emails are successfully split and Hotmail headers identified correctly. Dividing text such as Original Message or Forwarded Message should be contained within `divider` tags and not as a separate `email` tag. Also any emails that are indented, have preceding `>` characters or both are identified and successfully split as individual emails. 

**JIRA Link** - [CAF-2014](https://jira.autonomy.com/browse/CAF-2014)

