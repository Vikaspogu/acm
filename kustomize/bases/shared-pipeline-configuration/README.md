Create shared pipeline task

```bash
oc apply -k .
curl -X POST --header "Content-Type: application/json" https://<ROUTE-URL> -d @payload.json
```
