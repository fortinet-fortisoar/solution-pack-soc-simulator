<h1 style="font-size:2rem;">FortiSOAR SOC Simulator Solution Pack – Out-of-the box Playbooks Collections</h1>

<p style="font-size:1.9rem; font-weight: 600; margin-bottom: 5px;">Scenario Playbook Collections</p>
You can use the Scenario Playbook Collections to set up various scenarios in FortiSOAR such as brute force attempt, comprised credentials, etc., and demonstrate how FortiSOAR is used to respond to these scenarios. <br>
<br>

- [16- Scenario - Brute Force Attack Scenario](#16--scenario---brute-force-attack-scenario)
- [16- Scenario - Compromised Credentials Scenario](#16--scenario---compromised-credentials-scenario)
- [16- Scenario - FortiDeceptor](#16--scenario---fortideceptor)
- [16- Scenario - FortiSIEM](#16--scenario---fortisiem)
- [16- Scenario - LogRhythm](#16--scenario---logrhythm)
- [16 - Scenario - Microsoft CASB](#16---scenario---microsoft-casb)
- [16- Scenario - Phishing Scenario](#16--scenario---phishing-scenario)
- [16- Scenario - Sunburst](#16--scenario---sunburst)
- [16- Scenario - Symantec](#16--scenario---symantec)

## 16- Scenario
Following is a table that lists the playbooks that are part of the “**16- Scenario**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > Brute Force Attempt|Generates an alert and corresponding task for brute force attempt.|
|2|Generate > Compliance Alert|Generates a compliance alert.|
|3|Generate > Device Lost/Stolen|Generates an alert for lost/stolen device.|
|4|Generate > DLP Alert|Generates a DLP Alert and escalates it to an incident and creates a task for the same.|
|5|Generate > FortiAnalyzer (C&C Alert)|Generates a demo incident from a FortiAnalyzer incident with the 'Command and Control' type.|
|6|Generate > FortiAnalyzer (User login from SSH)|Generates a demo alert from a FortiAnalyzer incident for User login from SSH.|
|7|Generate > IDS Alert|Generates an alert for Snort IDS.|
|8|Generate > Malware Alert (Host1)|Creates an alert for the incidents fetched from Symantec ATP  with an IOC that is similar to the IOC on other hosts (Host 2 and Host 3). The analyst can then decide the actions that need to be carried out in relation to the alert.|
|9|Generate > Malware Alert (Host2)|Creates an alert for the incidents fetched from Symantec ATP with an IOC that is similar to the IOC on other hosts (Host 1 and Host 3). The analyst can then decide the actions that need to be carried out in relation to the alert.|
|10|Generate > Malware Alert (Host3)|Creates an alert for the incidents fetched from Symantec ATP  with an IOC that is similar to the IOC on other hosts (Host 1 and Host 2).  The analyst can then decide the actions that need to be carried out in relation to the alert.|
|11|Generate > PaloAlto Blocked C2 Connection Alert|Generates demo alert and task for a C2 Connection blocked by Palo Alto.|
|12|Generate > PaloAlto Panorama Threat Alert|Generates Palo Alto Panorama Threat Alert.|
|13|Generate > S3 Bucket Alert|Generates an alert and task for S3 Bucket Alert.|

## 16- Scenario - Brute Force Attack Scenario
Following is a table that lists the playbooks that are part of the “**16- Scenario - Brute Force Attack Scenario**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > FortiSIEM (Brute Force Attack)|Generates a demo record - Brute Force Attack.|

## 16- Scenario - Compromised Credentials Scenario
Following is a table that lists the playbooks that are part of the “**16- Scenario - Compromised Credentials Scenario**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description** |
| :- | :- | :- |
|1|Generate > FortiSIEM (01 - Initial Access - Firewall Configuration Change - Port Forwarding)|Generates a demo alert from a FortiSIEM incident, which is created when there is a change in the firewall configuration related to port forwarding.|
|2|Generate > FortiSIEM (02 - Initial Access - Firewall Configuration Change - Policy Change)|` `Generates a demo alert from a FortiSIEM incident, which is created when there is a change in the firewall configuration related to policy.|
|3|Generate > FortiSIEM (03 - Persistence - Domain User Created)|Generates a demo alert from a FortiSIEM incident, when a domain user is created and a persistence threat is detected.|
|4|Generate > FortiSIEM (04 - Persistence - User Password Reset)|Generates a demo alert from a FortiSIEM incident, which is created when the user password has been reset and a persistence threat is detected.|
|5|Generate > FortiSIEM (05 - Persistence - User Added to Administrator Group)|Generates a demo alert from a FortiSIEM incident, which is created when the user password has been reset and a persistence threat is detected.|
|6|Generate > FortiSIEM (06 - Persistence - Schedule Task)|Generates an alert from a FortiSIEM incident for ‘Persistence - Schedule Task’ scenario. Generates a demo alert from a FortiSIEM incident, which is created when the ‘Schedule Task’ scenario is executed.|
|7|Generate > FortiSIEM (07 - Exfiltration - File Transfer)|Generates an alert from a FortiSIEM incident for ‘Exfiltration - File Transfer’ scenario. Generates a demo alert from a FortiSIEM incident, which is created when a data exfiltration event has occurred.|

## 16- Scenario - FortiDeceptor
Following is a table that lists the playbooks that are part of the “**16- Scenario - FortiDeceptor**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > FortiDeceptor Alerts|Generates an alert from FortiDeceptor CEF.|

## 16- Scenario - FortiSIEM
Following is a table that lists the playbooks that are part of the “**16- Scenario - FortiSIEM**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > FortiSIEM (Concurrent Successful Authentications To Same Account From Multiple Countries)|` `Generates a demo alert from a FortiSIEM incident, which is created when concurrent successful authentications to the same account have been detected from multiple countries.|
|2|Generate > FortiSIEM (Excessive Denied Connections)|Generates a demo alert from a FortiSIEM incident, which is created when excessive denied connections events have been detected.|
|3|Generate > FortiSIEM (Important process down)|` `Generates a demo alert from a FortiSIEM incident, which is created when an important process is not running.|
|4|Generate > FortiSIEM (Large Outbound Transfer)|` `Generates a demo alert from a FortiSIEM incident, which is created when large outbound transfer has been detected.|
|5|Generate > FortiSIEM (Process Stopped)|` `Generates a demo alert from a FortiSIEM incident, which is created when a process has been stopped.|
|6|Generate > FortiSIEM (Sudden Increase in System Memory Usage)|Generates a demo record for the event - Sudden Increase in System Memory Usage. Generates a demo alert from a FortiSIEM incident, which is created when a sudden increase in system memory usage has been detected.|

## 16- Scenario - LogRhythm
Following is a table that lists the playbooks that are part of the “**16- Scenario - LogRhythm**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :-: | :-: | :-: |
|1|Generate > LogRhythm Alarms|Generates alerts for alarms pulled from LogRhythm during the specified duration.|

## 16 - Scenario - Microsoft CASB
Following is a table that lists the playbooks that are part of the “**16 - Scenario - Microsoft CASB**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate Microsoft CASB (Malware Infection) Alert|Generates a demo alert from a Microsoft CASB alert, which is created when a malware infection is detected.|

## 16- Scenario - Phishing Scenario
Following is a table that lists the playbooks that are part of the “**16- Scenario - Phishing Scenario**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > Phishing Alert|Generates an alert and a corresponding task for a phishing event.|

## 16- Scenario - Sunburst
Following is a table that lists the playbooks that are part of the “**16- Scenario - Sunburst**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > Sunburst Alert|Generates a Sunburst alert.|

## 16- Scenario - Symantec
Following is a table that lists the playbooks that are part of the “**16- Scenario - Symantec**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Generate > Symantec CloudSOC (External Filesharing Alert)|Generates an alert for Symantec CloudSOC incidents.|
|2|Generate > Symantec Email.Cloud|Generates an alert for a list of IOCs downloaded from Symantec Email.Cloud specific to a particular domain.|

