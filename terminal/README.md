# 環境構築

```bash
wget https://raw.githubusercontent.com/cashewnuts/multipass-env/master/terminal/cloud-config.yaml
multipass launch -n microk8s-vm --cloud-init cloud-config.yaml --mem 4G --disk 40G
```
