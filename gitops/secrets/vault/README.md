# Rancher Fleet - Vault

This is a chart to get you started with deploying Vault via Rancher Fleet.

## Upstream Chart Repository

[Vault Helm Chart](https://github.com/hashicorp/vault-helm/tree/v0.20.1)

## Usage

1. Fork this repository.
2. Modify the `gitrepo.yaml` file to reference your hosted.
3. Update the `secrets/vault/helm/values.yaml` file with your specific chart overrides.
5. Commit/push to a new repository.
5. While referencing your Rancher/Fleet cluster, run `kubectl apply -f gitrepo.yaml`.

## Related Fleets

* [External-Secrets](https://github.com/rancherfederal/bullpen/external-secrets)