# civo-guide

Add your apikey
```bash
civo apikey add shubham xxxxxxxxxxxxxxxxxxxxxxxx
```

show your API key
```bash
civo apikey show
```

create new cluster
```bash
civo kubernetes create civo-beta-cluster
```

list kubernetes clusters
```bash
civo kubernetes ls
```

get cluster details
```bash
civo kubernetes show civo-beta-cluster
```

delete cluster
```bash
civo kubernetes rm civo-beta-cluster -y
```

save config
```bsah
civo kubernetes config civo-beta-cluster --save --merge
```
