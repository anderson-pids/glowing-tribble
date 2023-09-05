# glowing-tribble
Passbolt in k8s


ref: https://www.passbolt.com/blog/installing-passbolt-with-helm
## Steps to install passbolt k8s

1. Add helm repository
```bash
helm repo add passbolt-repo https://download.passbolt.com/charts/passbolt
```
2. Copy of values.yaml
```bash
wget https://raw.githubusercontent.com/passbolt/charts-passbolt/main/values.yaml
```
