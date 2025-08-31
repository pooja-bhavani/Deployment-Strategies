# To create cluster with the configuration file
``` 
kind create cluster --config kind-config.yml
```
# To Forward the svc port to the EC2 instance port 3000  
```
kubestl port-forward --address 0.0.0.0 svc/recreate-service 3000:3000 -n recreate-ns &
```
