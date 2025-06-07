
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 126d3cb723ea7ccbe300ce1346fc33a14d80a43f
helm template . --name-template github-promoter-test-dev --include-crds
```