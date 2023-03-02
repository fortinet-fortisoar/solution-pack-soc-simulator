| [Home](/README.md) | 
|--------------------------------------------|

# Contents

## Connector

| Connector               | Description                                                                                                            |
|:------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| FortiSOAR SOC Simulator | Simulates a SOC environment and creates various scenarios-based artifacts such as alerts, incidents, etc. in FortiSOAR |

>**Warning:** After deployment, this Solution Pack will install or upgrade the connector.

## Module Schema

| Module Schema | Description                                                                           |
|:--------------|:--------------------------------------------------------------------------------------|
| Scenario      | A schema for listing scenarios included with other solution packs that are installed. |

## Playbook Collection

|02 - Use Case - SOC Simulator|
|:--                          |

| Playbook Name                | Description                                                                             |
|:-----------------------------|:----------------------------------------------------------------------------------------|
| Reset Scenario               | Deletes created alerts and related records                                              |
| Reset Scenario - Get Correlated Records | Fetches all the correlated records of the demo record created for the simulation |
| Run Scenario                 | Executes a scenario and create its related records triggered from the 'Scenario' record |
| Run Scenario - Create Alerts | Creates records related to a scenario                                                   |
| Run Selected Scenario        | Executes a scenario and create related records triggered from the 'Alerts' page         |

>**Warning:** It is recommended not to modify these playbooks to avoid any breaks in scenario simulation functionality
