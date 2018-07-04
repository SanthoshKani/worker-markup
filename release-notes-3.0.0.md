
#### Version Number
${version-number}

#### New Features
- [CAF-3518](https://jira.autonomy.com/browse/CAF-3518): Add support for JavaScript post processing  
  Updated to use latest worker-document framework to receive support for post processing in the worker.
- [SCMOD-3427](https://jira.autonomy.com/browse/SCMOD-3427): Update container to latest jeptalon base image
  Updated to use the latest opensuse-jeptalon base image.
- [SCMOD-4034](https://jira.autonomy.com/browse/SCMOD-4034): Updated to add new parameter for document workers
- [SCMOD-4128](https://jira.autonomy.com/browse/SCMOD-4128): Fix erroneous email detection

#### Bug Fixes
- [SCMOD-3065](https://jira.autonomy.com/browse/SCMOD-3065): Updated regex to avoid StackOverflowErrors when performing email splitting.
- [SCMOD-3059](https://jira.autonomy.com/browse/SCMOD-3059): Corrected issues with element tags from notes emials

#### Known Issues

#### Breaking Changes
- [SCMOD-3023](https://jira.autonomy.com/browse/SCMOD-3023): Values modified by the worker are set and not added.
