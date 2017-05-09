# jep-talon-image

This is an image that installs the Mailgun/Talon library and it's dependencies as well as the Jep Python interpreter to allow the execution of Python scripts from Java. It is created as a separate image to allow for shorter build times of images that require the installation of Python, Jep and Talon. 

The [jep-talon-install-script](https://github.com/CAFDataProcessing/worker-markup/tree/develop/jep-talon-install-script) is installed into a container. The following application/libraries are installed:

- Python 2.7.9
- Pip 1.5.6
- Python-tools 5.5.1
- Python-numpy 1.8.2
- Python-scipy 0.14.0
- Other various required libraries(libxml2, libxslt1, zlib1g, lxml, matplotlib)
- Talon 1.3.3
- Jep 3.5.2


This can be used as a base image by adding the following within the build elements in your pom.xml file:

    <from>${docker.dev.repo}/caf/jep_talon-image:1.2.0</from>

For example:

    <image>
       <alias>new-worker-image</alias>
       <name>${docker.dev.repo}/caf/new-worker-image:${project.version}</name>
        <build>
         <maintainer>john.smith@hpe.com</maintainer>
         <from>${docker.dev.repo}/caf/jep_talon-image:1.2.0</from>
		</build>
    </image>
