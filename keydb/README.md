# KeyDB
```
helm repo add enapter https://enapter.github.io/charts/
helm repo update
helm show values enapter/keydb > helm-values.yml
helm upgrade -i keydb enapter/keydb --values=helm-values.yml
```
