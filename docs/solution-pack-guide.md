# Usage of SOC Simulator Solution Pack

## Configuring the FortiSOAR SOC Simulator Connector

This solution pack will install and pre-configure the FortiSOAR SOC Simulator Connector by default. 

## Scenario Module

Users can use various scenarios to understand how FortiSOAR™ handles various scenarios. Click **Simulations** to view the **Scenario** page. These scenarios can be imported through various solution packs such as Phishing Email Response, Brute Force Attack Response etc.

Some scenarios demonstrate particular features of FortiSOAR™, such as FortiSOAR™ recommendation engine which lists alerts containing similar hosts etc, providing you with a complete picture of the incident. Some scenarios demonstrate an investigation process and therefore contain associated investigation playbooks, etc.  

For example, in the Stolen Credentials scenario, click the down-arrow on the “Stolen credential leading to data exfiltration” row, and the description of this scenario is displayed: 

![Stolen Credentials scenario](media/StolenCredsScenario.png)

To run this scenario, select Stolen credential leading to data exfiltration and click **Simulate Scenario**. Clicking Simulate Scenario creates alerts and/or incidents corresponding to this scenario. Clicking an alert created by this scenario, for example, the “Windows User Created”, opens the alert and when you click on the Recommendations tab, you observe that many similar alerts have been created, giving you an idea that related operations are taking place, and therefore, the task of a SOC analyst to go through a number of alerts to figure out what is similar is solved by FortiSOAR™ Recommendation engine. Now, you can select all the similar alerts and link them and also escalate them to create a Security Incident. 

![Alert created for the Stolen Credentials scenario](media/StolenCredsScenarioAlerts.png)

To view the source for the Stolen credential leading to data exfiltration scenario, click **Simulations** > **Scenario** > **Stolen credential leading to data exfiltration**. Then click on the **Source** tab, the “Steps” section, contains data used by playbooks to create the demo records. Once the alerts are created their IDs are listed in the “Created Alerts” section:

![Viewing source of the Stolen Credentials data](media/StolenCredsSource.png)

If you want to delete the records created by this scenario, you can click the **Reset Scenario** button on the “Scenario” page.  

You can also click the **Simulate Scenario** to create a specific scenario from the “Alerts” page. 