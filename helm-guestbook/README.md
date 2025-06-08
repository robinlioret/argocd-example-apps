
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout f529ef119e3cc68ce73c302c4c49800cfe724e07
helm template . --name-template prodhelm-guestbook --include-crds
```