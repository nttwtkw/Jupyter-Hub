# Images Version

- Hub

| Images | Version |
| ------ | ------ |
| hub | jupyterhub/k8s-hub:1.1.4 |
- Image puller hook&continuous



| Images | Version |
| ------ | ------ |
| image-pull-singleuser (init) | chinnapatke01/elyra:vaex-1.3.1 |
| pause | nattawut07x/pause:3.5 |

- Proxy

| Images | Version |
| ------ | ------ |
| chp | jupyterhub/configurable-http-proxy:4.5.0 |
| kube-scheduler | nattawut07x/kube-scheduler:v1.19.13 |

- Scheduling-user-placeholder

| Images | Version |
| ------ | ------ |
| pause | nattawut07x/pause:3.5 |

- Scheduling-user-scheduler

| Images | Version |
| ------ | ------ |
| kube-scheduler | nattawut07x/kube-scheduler:v1.19.13 |


# Procedure
Edit values.yaml file
```sh
helm template jhub . --output-dir test -n rdt-uat
kubectl create -f template/<sub folder> 
```


