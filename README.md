# helm_okd

**Install helm v3**
```sh
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
```


**Install apps via v3**

```sh
helm install nginx .
```

**update apps via helm v3**

```sh
helm upgrade nginx  .
```
