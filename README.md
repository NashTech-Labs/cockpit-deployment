# cockpit-deployment
cockpit-deployment using manifest files
```
cd  deployment-manifests 
```
* apply all the manifest file using command 
```
kubectl apply -f [name of the file]
```
* for start using cockpit use this command 
```
kubectl port-forward deployments/cockpit-ui 5000:80
```
