### **Erstelle Kubernetes Apache-Server**
```
kubectl apply -f Cluster.yaml
```

### **Lösche denn erstellten Apache-Server**
```
kubectl delete -f Cluster.yaml
```

### **Port-Forward um den Cluster zu testen**
```
kubectl port-forward service/master-service 8080:80  
kubectl port-forward service/worker-service 8081:80   
```

### **Info**
Nachdem erstellen des Clusters und dem Port-Forward können die Worker unter dem Link http://localhost:8081 abgerufen werden und der Master unter http://localhost:8080

So sollte es aussehen wen man http://localhost:8080 aufruft:
![](Screenshots/Ende-1.png)

So sollte es aussehen wen man http://localhost:8081 aufruft:
![](Screenshots/Ende-2.png)