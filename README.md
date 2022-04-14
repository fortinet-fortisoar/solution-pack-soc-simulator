# SOC Simulator Solution Pack

## Overview

### Introduction

The FortiSOAR™ SOC Simulator Solution Pack (solution-pack-soc-simulator). This solution pack enables users to experience the power and capability of FortiSOAR™ incident response for SOC Simulator scenarios. This pack contains simulation data and utilities for demonstrating FortiSOAR capabilities around a variety of important SOC use-cases without having to integrate with actual device endpoints.

### Usage

More information about the usage of the SOC Simulator Solution Pack can be found [here](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/solution-pack-guide.md).

## Version Information

- Solution Pack Version: 1.0.
- FortiSOAR™ Version Tested on: 7.2.0
- Authored By: Fortinet
- Certified: Yes

## Prerequisite

- Before you deploy the SOC Simulator Solution Pack, ensure that you have deployed the SOAR Framework Solution Pack([solution-pack-soar-framework](https://github.com/fortinet-fortisoar/solution-pack-soar-framework)). The steps for deploying a solution pack are mentioned in the [Deploying a Solution Pack](https://github.com/fortinet-fortisoar/how-tos/blob/main/DeployingASolutionPack.md) article. 
- Ensure that the following URLs are unblocked in your environment: 
    - [https://malsilo.gitlab.io/feeds/dumps/ip_list.txt](https://malsilo.gitlab.io/feeds/dumps/ip_list.txt)
    - [https://cybercrime-tracker.net/ccamlist.php](https://cybercrime-tracker.net/ccamlist.php)
    - [https://malsilo.gitlab.io/feeds/dumps/domain_list.txt](https://malsilo.gitlab.io/feeds/dumps/domain_list.txt)
    - [https://openphish.com/feed.txt](https://openphish.com/feed.txt) 

## Contents

1. Connector(s)

    - FortiSOAR SOC Simulator

        **Warning:** After deployment, this Solution Pack will install or upgrade the stated connectors list.

2. Module(s)
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

4. Role(s)
    - Full App Permission