charts for scry specific development


## structurizr-local debug

```
helm upgrade -i structurizr ./charts/structurizr-local

helm install --set localDirectory="/FULL PATH TO THE FOLDER" --set ingress.host="diagrams.local.scryapp.website" --repo https://garunski-co.github.io/scry-helm-charts/ structurizr structurizr-local 

helm upgrade -i --set localDirectory="/FULL PATH TO THE FOLDER" --set gatewayApi.create=true --set gatewayApi.host="diagrams.local.scryapp.website"   --repo https://garunski-co.github.io/scry-helm-charts/ structurizr structurizr-local 


```

## postgres-local debug
```
helm upgrade -i --repo https://garunski-co.github.io/scry-helm-charts/ postgres-local postgres-local 
```

```
helm upgrade -i postgres-local  ./charts/postgres-local 
```

```
helm delete postgres-local
```