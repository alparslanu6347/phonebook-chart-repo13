```bash
helm repo add phonebook-repo https://raw.githubusercontent.com/alparslanu6347/phonebook-chart-repo13/main
helm install phonebook-app phonebook-repo/phonebook-chart
```
- To use own images execute as below:

```bash
helm install phonebook-app phonebook-repo/phonebook-chart --set webserver_image=<image-name> --set resultserver_image=<image-name>
```