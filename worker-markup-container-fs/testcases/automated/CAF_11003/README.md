## CAF_11003 - Extend markup worker with email splitting ##

Process plain text from email threads and split up the thread into constituent emails adding a start and end tag to each individual email.

**Test Steps**

1. Send plain text from email threads into the Markup worker
2. Examine output

**Test Data**

Variety of plain text derived from email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the email threads are successfully split into the constituent emails. Each email will have a start `<email>` and end `</email>` tag added to the output.xml 

**JIRA Link** - [CAF-1439](https://jira.autonomy.com/browse/CAF-1439)

