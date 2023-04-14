# Getting started

```bash
oc apply -k .
oc adm policy add-role-to-user edit system:serviceaccount:shared-pipelines:pipeline -n test-ns
curl -X POST --header "Content-Type: application/json" https://<ROUTE-URL> -d @payload.json
```
