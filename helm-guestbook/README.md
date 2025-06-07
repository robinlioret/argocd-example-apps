
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 23c3bd8ae3bf0635a7cdc2196a6aa5eef45dfd56
helm template . --name-template github-promoter-test-dev --include-crds
```