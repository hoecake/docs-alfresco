---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
---

# LibreOffice configuration properties

LibreOffice uses the OOoJodConverter subsystem. Configure the following properties for the OOoJodconverter subsystem.

-   **jodconverter.connectTimeout**

    Specifies the maximum number of milliseconds before a connection times out. The default is 10000 milliseconds \(10 seconds\).

-   **jodconverter.enabled**

    Enables or disables the Jodconverter process\(es\).

-   **jodconverter.maxTasksPerProcess**

    Specifies the number of transforms before the process restarts. The default is 200.

-   **jodconverter.officeHome**

    Specifies the name of the LibreOffice install directory. The following are examples of install directory paths:

    -   Mac OS X: jodconverter.officeHome=/Applications/alfresco/libreoffice.app/Contents
    -   Windows: jodconverter.officeHome=c:/Alfresco/LibreOffice.org
    -   Linux: /opt/alf5100/libreoffice
-   **jodconverter.portNumbers**

    Specifies the port numbers used by each processing thread. The number of process will match the number of ports. The default numbers are 2022, 2023, and 2024.

-   **jodconverter.taskExecutionTimeout**

    Specifies the maximum number of milliseconds that an operation is allowed to run before it is aborted. It is used to recover from operations that have hung. The default is 120000 milliseconds \(2 minutes\).

-   **jodconverter.taskQueueTimeout**

    Specifies the maximum number of milliseconds a task waits in the transformation queue before the process restarts. It is used to recover hung LibreOffice processes. The default is 30000 milliseconds \(30 seconds\).


**Parent topic:**[Configuring LibreOffice](../concepts/OOo-subsystems-intro.md)

