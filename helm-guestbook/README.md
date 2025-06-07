
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 18e6374bf4d23b96fbd96bc2517a02d4048b5e4a
helm template . --name-template github-promoter-test-staging --include-crds
```