## The endpoint we can get configs from:

```GET http://localhost:8888/requests/default```

## For the service in order to work correctlly - the absolute path needs to be updated in the application.yaml file:

```yaml
cloud:
    config:
      server:
        native:
          search-locations: file:///{path-of-the-machine}/maint-manager-config-service/src/main/resources/config
```





