## CAF_11009 - Tag processed items with Worker name and version ##

Verify that when an item is processed by the Markup worker it gets tagged with the name and version of the worker

**Test Steps**

1. Set up system to perform Markup using the debug parameter
2. Examine the output messages from the Markup worker

**Test Data**

Any plain text file derived from email threads e.g. output from Text Extract worker.

**Expected Result**

The output task message will contain a "sourceInfo" section that has the name and version of the Markup worker 

**JIRA Link** - [CAF-1438](https://jira.autonomy.com/browse/CAF-1438)

