## CAF_11028 - Markup Worker support for Yahoo! Mail ##

Process plain text from email threads which is derived from emails sent from Yahoo!

**Test Steps**

1. Send plain text from Yahoo! email threads into the Markup worker.
2. Examine output

**Test Data**

Variety of plain text derived from Yahoo! email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the emails are successfully split and Yahoo! headers identified correctly. Dividing text such as Original Message or Forwarded Message should be contained within `divider` tags and not as a separate `email` tag.

**JIRA Link** - [CAF-2013](https://jira.autonomy.com/browse/CAF-2013)

