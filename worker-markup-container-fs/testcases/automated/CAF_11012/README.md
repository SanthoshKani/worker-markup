## CAF_11012 - Comparison and Variant Hashing ##

Process plain text from email threads, remove the whitespace from the email body and then hash the resultant text of the complete thread.

**Test Steps**

1. Send plain text from email threads into the Markup worker with the hash configuration set for the email thread.
2. Examine output

**Test Data**

Variety of plain text derived from email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the email body is stripped of all whitespace and the result text is then hashed. This hash value is then added along with hash configuration (type of normalization and hash function) to the output.xml for the complete email thread.

**JIRA Link** - [CAF-1248](https://jira.autonomy.com/browse/CAF-1248)

