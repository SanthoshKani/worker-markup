## CAF_11026 - Markup Worker support for GMail Web Client ##

Process plain text from email threads which is derived from emails sent from the GMail Web Client

**Test Steps**

1. Send plain text from GMail email threads into the Markup worker.
2. Examine output

**Test Data**

Variety of plain text derived from GMail email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the emails are successfully split and GMail headers identified correctly. Dividing text such as Original Message or Forwarded Message should be contained within `divider` tags and not as a separate `email` tag.

**JIRA Link** - [CAF-1697](https://jira.autonomy.com/browse/CAF-1697)

