```bash
helm repo add phonebook-repo https://raw.githubusercontent.com/alparslanu6347/phonebook-chart-repo/main
helm install phonebook-release phonebook-repo/phonebook-chart
```
- To use own images execute as below:

```bash
helm install phonebook-release phonebook-repo --set webserver_image=<image-name> --set resultserver_image=<image-name>
```