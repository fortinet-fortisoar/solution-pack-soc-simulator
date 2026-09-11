| [Home](../README.md) |
| -------------------- |

# Contents

The **SOC Simulator** solution pack contains the following resources.

## Connector

| Connector               | Description                                                                                                            |
|:------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| FortiSOAR SOC Simulator | Simulates a SOC environment and creates various scenarios-based artifacts such as alerts, cases, etc. in FortiSOAR     |

>[!Warning]
>After deployment, this solution pack installs/upgrades the *FortiSOAR SOC Simulator* connector.

## Module Schema

| Module Schema | Description                                                                           |
|:--------------|:--------------------------------------------------------------------------------------|
| Scenario      | A schema for listing scenarios included with other solution packs that are installed. The schema includes an *Icon* field that holds a representative image for each scenario. |

## Widget

| Widget             | Description                                                                                                                     |
|:-------------------|:--------------------------------------------------------------------------------------------------------------------------------|
| Scenario Simulator | Lists the available scenarios and runs or resets a simulation from a record list page. Opens as a half-width drawer.            |

## Playbook Collection

|02 - Use Case - SOC Simulator|
|:--                          |


| Playbook Name                           | Description                                                                                |
|:----------------------------------------|:-------------------------------------------------------------------------------------------|
| Export Selected Scenario                | Exports the selected scenarios to a JSON file and creates the file as an attachment record |
| Import Scenario                         | Imports scenarios into the Scenario module from a valid JSON file                          |
| Reset Scenario                          | Deletes created alerts and related records                                                 |
| Reset Scenario - Get Correlated Records | Fetches all the correlated records of the demo record created for the simulation           |
| Run Scenario                            | Executes a scenario and create its related records triggered from the 'Scenario' record    |
| Run Scenario - Create Alerts            | Creates records related to a scenario                                                      |
| Run Selected Scenario                   | Executes a scenario and create related records triggered from the 'Alerts' page            |

>[!Warning]
>Modifying these playbooks may break scenario simulation functionality. Hence, we recommend that you exercise caution.

## Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|