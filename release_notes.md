# What's New

## Playbook Enhancements

- Added a new playbook **Reset Scenario - Get Correlated Records** that fetches all the correlated records of the demo record created for the simulation

- Following playbooks have been modified

  - **Run Selected Scenario** playbook modifications:

    - The loop execution mode of the *Create Alert* step is updated from `Sequential` to `Parallel`

    - A `Simulation` tag is added to the playbook

    - The **Create Scenario** step is renamed to **Create Alerts** 

  - **Run Scenario** playbook modifications:

    - The loop execution mode of the *Create Alert* step is updated from `Sequential` to `Parallel`

  - **Run Scenario - Create Alerts** playbook modifications:

    - Updated the playbook so it now adds post-create comments in scenario records after demo records creation

## Module Enhancements

- `Created Alerts ID` field label has been updated to `Created Records ID` in the *Scenario* module


