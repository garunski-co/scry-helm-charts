charts for scry specific development

```
helm upgrade -i structurizr ./charts/structurizr-local

helm install --set localDirectory="/FULL PATH TO THE FOLDER" --set ingress.host="diagrams.local.scryapp.website" --repo https://garunski-co.github.io/scry-helm-charts/ structurizr structurizr-local 

helm upgrade -i --set localDirectory="/FULL PATH TO THE FOLDER" --set gatewayApi.create=true --set gatewayApi.host="diagrams.local.scryapp.website"   --repo https://garunski-co.github.io/scry-helm-charts/ structurizr structurizr-local 


```