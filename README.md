# SOC Simulator Solution Pack

## Release Information

- Solution Pack Version: 1.0.1
- FortiSOAR™ Version Tested on: 7.2.0
- Authored By: Fortinet
- Certified: Yes

## Overview

### Introduction

The FortiSOAR™ SOC Simulator Solution Pack (solution-pack-soc-simulator) enables users to experience the power and capability of FortiSOAR™ incident response for SOC Simulator scenarios. This pack contains utilities for demonstrating FortiSOAR capabilities around a variety of important SOC use-cases without having to integrate with actual device endpoints.

### Usage

[Refer](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/solution-pack-guide.md) to Simulate Scenario documentation to undersand how to Simulate and Reset Scenario.

## Prerequisite

- Ensure that you have deployed the SOAR Framework Solution Pack([solution-pack-soar-framework](https://github.com/fortinet-fortisoar/solution-pack-soar-framework)). The steps for deploying a solution pack are mentioned in the [Deploying a Solution Pack](https://github.com/fortinet-fortisoar/how-tos/blob/main/DeployingASolutionPack.md) article.
- Ensure that the following URL is unblocked in your environment, in order to gather threat intelegence data:
  - [https://otx.alienvault.com](https://otx.alienvault.com)

## Contents

1. Connector(s)

    - FortiSOAR SOC Simulator

        **Warning:** After deployment, this Solution Pack will install or upgrade the connector.

2. Module Schema(s)
    - Scenario

3. Playbook Collection(s)
    - 02 - Use Case - SOC Simulator (4):
Following is a list of playbooks under “02 - Use Case - SOC Simulator”

    |**Playbook Name**|**Description**
    | :- | :- |
    |Reset Scenario|Deletes created alerts and related records|
    |Run Scenario|Executes a scenario and create its related records triggered from 'Scenario' record|
    |Run Scenario - Create Alerts|Creates records related to a scenario|
    |Run Selected Scenario|Executes a scenario and create related records triggered from 'Alerts' page|

    **Warning:** It is recommended not to modify these playbooks to avoid any breaks in scenario simulation functionality
