## CAF_11030 - Email being split in the middle of the body content ##

Process plain text from email threads which has the word "an" at the start of a line.

**Test Steps**

1. Send plain text from email threads into the Markup worker.
2. Examine output

**Test Data**

Variety of plain text derived from email threads that contain the word "an" at the start of a line.

**Expected Result**

The files are all processed and the emails are successfully split with only the expected number of emails being returned. The email thread is not split on the word "an".

**JIRA Link** - [CAF-2173](https://jira.autonomy.com/browse/CAF-2173)

