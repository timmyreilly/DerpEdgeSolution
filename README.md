
### Sample .env  (sits next to .gitignore and readme at root of project)

```
CONTAINER_REGISTRY_USERNAME_derpregistry=derpRegistry
CONTAINER_REGISTRY_PASSWORD_derpregistry=eL=AAmKsRCySZEycJvVtBmmXlBUKpVjn
```

Connect to ACR from Docker: 

`docker login -u derpRegistry -peL=AAmKsRCySZEycJvVtBmmXlBUKpVjn derpregistry.azurecr.io`