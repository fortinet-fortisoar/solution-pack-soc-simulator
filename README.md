## Release Information

- Solution Pack Version: 1.0.1
- Minimum Compatible FortiSOAR™ Version: 7.2.0
- Authored By: Fortinet
- Certified: Yes

## Overview

### Introduction

The FortiSOAR™ SOC Simulator Solution Pack (solution-pack-soc-simulator) enables users to experience the power and capability of FortiSOAR™ incident response for SOC Simulator scenarios. This pack contains utilities for demonstrating FortiSOAR capabilities around a variety of important SOC use-cases without having to integrate with actual device endpoints.

### Usage

For a better understanding of the Simulate and Reset scenarios, refer to the document [here](docs/solution-pack-guide.md).

## Prerequisite

Ensure that the below solution packs are deployed:

|**Solution Pack**|**Purpose**|**Doc Link**|
| :- | :- | :- |
|SOAR Framework 1.0.0|Require for Incident Response modules and Action playbooks|[Click here](https://github.com/fortinet-fortisoar/solution-pack-soar-framework/blob/develop/README.md)|

- Ensure that the following URL is unblocked in your environment, to gather threat intelligence data:
  - [https://otx.alienvault.com](https://otx.alienvault.com)

## Contents

1. Connector(s)

    - FortiSOAR SOC Simulator

        **Warning:** After deployment, this Solution Pack will install or upgrade the connector.

2. Module Schema(s)
    - Scenario

3. Playbook Collection(s)
    - 02 - Use Case - SOC Simulator (4):

    |**Playbook Name**|**Description**
    | :- | :- |
    |Reset Scenario|Deletes created alerts and related records|
    |Run Scenario|Executes a scenario and create its related records triggered from the 'Scenario' record|
    |Run Scenario - Create Alerts|Creates records related to a scenario|
    |Run Selected Scenario|Executes a scenario and create related records triggered from the 'Alerts' page|

     **Warning:** It is recommended not to modify these playbooks to avoid any breaks in scenario simulation functionality
