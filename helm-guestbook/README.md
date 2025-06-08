
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout 16ad8eeef9f94f90c8cba53c1e9bb1388b2811c9
helm template . --name-template staginghelm-guestbook --include-crds
```