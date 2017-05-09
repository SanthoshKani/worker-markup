## CAF_11027 - Markup Worker pass in language arrays to configuration ##

Process plain text from email threads which includes condensed email headers that are in common languages such as English, French, German and Spanish.

**Test Steps**

1. Send plain text from email threads into the Markup worker with the condensed email header mappings set for the common languages.
2. Examine output

**Test Data**

Variety of plain text derived from email threads with condensed email headers in different languages e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the different language condensed email headers are all successfully contained within the To, From, Sent and Subject xml tags.

**JIRA Link** - [CAF-2056](https://jira.autonomy.com/browse/CAF-2056)

