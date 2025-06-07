
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 68657670d9131dc5bc5f538b14c1de3377d74591
helm template . --name-template github-promoter-test --include-crds
```