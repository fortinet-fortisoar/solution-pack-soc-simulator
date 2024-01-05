# What's New

## Playbook Enhancements

- Following playbooks have been modified

  - **Run Selected Scenario** playbook modifications:
    - A `SystemWaitForCompletion` tag is added to the playbook to disable the 'Simulate Scenario' button in the Scenario record for long-running simulation

  - **Run Scenario** playbook modifications:
    - A `SystemWaitForCompletion` tag is added to the playbook to disable the 'Simulate Scenario' button in the Scenario record for long-running simulation

  - **Run Scenario - Create Alerts** playbook modifications:
    - Updated the playbook to fix inconsistencies demo record IRIs in scenario record's "Created Records ID" field. 

  - **Reset Scenario** playbook modifications:
    - A `SystemWaitForCompletion` tag is added to the playbook to disable the 'Reset Scenario' button in the Scenario record while resetting the scenario
    - Updated the playbook so it excludes mitre records from deletion




