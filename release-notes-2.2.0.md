#### Version Number
${version-number}

#### New Features
 - [CAF-3161](https://jira.autonomy.com/browse/CAF-3161): Library availability  
    The core functionality of the Markup Worker has been extracted into a separate `worker-markup-core` module, which can be consumed as an in-process library.

 - [CAF-3229](https://jira.autonomy.com/browse/CAF-3229): Consistent field ordering  
    A change has been made so that a definitive field order is used when generating hash values.  This could potentially be a breaking change; it may cause the hash values generated to change.

#### Known Issues
 - None
