# SOC Simulator Incident Response Solution Pack 7.0.2

## Overview

This article describes the FortiSOAR™ SOC Simulator Incident Response Content Pack (solution-pack-soc-simulator). This content pack enables users to experience the power and capability of FortiSOAR™ incident response for SOC Simulator scenarios. 

FortiSOAR™ is built using modular architecture and the FortiSOAR™ Incident Response Content Pack is the implementation of the best practices to configure and use FortiSOAR™ in an optimal manner. The FortiSOAR™ Incident Response Content Pack also contains a lot of sample/simulation/training data that enables you to experience FortiSOAR™ without having all the devices.

## Deploying SOC Simulator IR Solution Pack

**Important**: Before you deploy the solution pack, ensure that you have deployed the FortiSOAR™ Incident Response Solution Pack (solution-pack-incident-response).

Use the following procedure as a *root* user to deploy the solution pack:

1. Log onto the Solution Pack GIT repo (https://github.com/fortinet-fortisoar/solution-pack-soc-simulator](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator)) using your credentials.
2. Click the **Code** button and select the **Download ZIP** option.
   ![Fortinet-FortiSOAR GIT branch > Code >Download the solution pack zip](media/socSimulatorZip.png)
3. Log into your FortiSOAR instance, and on the left-navigation, click **Import Wizard**.
   ![Import Wizard](media/importWizard.png)
4. On the `Import Wizard` page, click **Import From File** and selected the solution pack zip that you have downloaded, and navigate through the Import Wizard.
   ![Importing the IR Solution Pack zip file](media/importIRCP.png)
   **Note**: It is recommended not the change any configurations or options of the imported solution pack zip file.
   Once the import is successfully completed, you can use the SOC Simulator IR solution pack.
