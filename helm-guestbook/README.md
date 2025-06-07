
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout c1ddaa17a256042351b7781f9d49697a49ea53e4
helm template . --name-template github-promoter-test-dev --include-crds
```