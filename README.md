# Cross-Repository JSON File Sync Test

This workspace contains a test setup for automatically syncing JSON interface files between two repositories using GitHub Actions.

## Structure
- **Repo A (ModelDeploy)**: Source repository that generates JSON interface files
- **Repo B (ETLDeploy)**: Target repository that receives the JSON files

## Workflow
When JSON files are updated in `Repo-A/output/interfaces/`, a GitHub Actions workflow automatically copies them to `Repo-B/app/mapping/`.

## Test Files
The test includes sample JSON interface files:
- MODELZ2_states.json
- MODELZ2_params.json  
- MODELZ2_outputs.json
- MODELZ2_mapping.json
- MODELZ2_inputs.json