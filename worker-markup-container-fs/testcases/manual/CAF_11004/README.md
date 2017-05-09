## CAF_11004 - Standardize the header names ##

Process plain text from email threads and re-map the header names to a standard list.

**Test Steps**

1. Send plain text from email threads into the Markup worker
2. Examine output

**Test Data**

Variety of plain text derived from email threads e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the email headers are re-mapped to a standard list e.g:

- `<from>`, `<sent by>` should be mapped to `<from>`
- `<sent>`, `<date sent>` should be mapped to `<sent>`
- `<to>`, `<sent to>`, `<recipient>` should be mapped to `<to>` 

**JIRA Link** - [CAF-1442](https://jira.autonomy.com/browse/CAF-1442)

