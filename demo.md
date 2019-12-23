# Demo'ing CD4PE with Hydra

## Manifest.yaml

NOTE: The manifest.yaml file needs to have the following at a minimum:

---
tf_action: apply -auto-approve
agents: true
cd4pe: true

It is recommended to have at least 2 machines (besides the master) to demonstrate CD4PE.
