
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/robinlioret/argocd-example-apps
# cd into the cloned directory
git checkout de5451a7f1afac4b5db6955b0cf974de8cc504f4
helm template . --name-template devhelm-guestbook --include-crds
```