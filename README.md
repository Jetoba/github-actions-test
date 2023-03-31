For debug any workflow, we need add in the settings, exactly in the secrets module, the following variables :

Name: ACTIONS_RUNNER_DEBUG
value: true

Name: ACTIONS_STEP_DEBUG
value: true

After add these variables, we need re-launch the workflow and verify the logs and if every is  correct, we have the oportunity to see more details about these actions.

