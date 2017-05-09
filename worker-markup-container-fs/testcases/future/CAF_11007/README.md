## CAF_11007 - Parsing of headers from mobile clients ##

Process plain text from email threads that originate from mobile client and re-map the header names to a standard list.

**Test Steps**

1. Sent plain text from email threads originating from mobile clients into the Markup worker
2. Examine output

**Test Data**

Variety of plain text derived from email threads originating from mobile clients e.g. output from Text Extract worker.

**Expected Result**

The files are all processed and the email headers are re-mapped to a standard list e.g:

- `<from>`, `<sent by>` should be mapped to `<from>`
- `<sent>`, `<date sent>` should be mapped to `<sent>`
- `<to>`, `<sent to>`, `<recipient>` should be mapped to `<to>`

**JIRA Link** - [CAF-1452](https://jira.autonomy.com/browse/CAF-1452)

**Note** - There is no target date set for the delivery of this feature at the moment.

