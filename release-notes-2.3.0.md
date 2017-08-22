#### Version Number
${version-number}

#### New Features
- [CAF-3320](https://jira.autonomy.com/browse/CAF-3320): Added `NORMALIZE_CASE` normalization.
  A new normalization has been added that normalizes field values to the same character casing. This means that
  field values may be used to produce the same output field value regardless of their case.

- [CAF-3340](https://jira.autonomy.com/browse/CAF-3340): Updated to only create one jepThreadPool object per worker and share this across all doWork calls.

#### Known Issues
