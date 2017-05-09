# Markup Testcase Generation using Template file

Some of the Markup testcases are designed with different input parameters e.g. hashConfiguration, outputFields. In order to generate Markup testcases with these input parameters you need to use a template file. The testcase which use a template file will have a `*.yaml` file within the testcase directory.

In order to run testcase generation which utilises the template file you need to add the `-Dtask.template=filename.yaml` variable to the command when running the worker testing application.



