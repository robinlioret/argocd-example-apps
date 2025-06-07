
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 3174b6f2921f88386acf758d74627c558346604a
helm template . --name-template github-promoter-test-prod --include-crds
```