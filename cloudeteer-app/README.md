

# Start minikube
```
minikube start
```

# helm erstellen
```
helm create cloudeteer
```

# deployment.yaml und service.yaml datein erstellen 
   
1. namespace erstellt
2. Persistenzvolume optional kann in values.yaml geändert werden.
3. replicas und Umgebungsvariablen können in values datei angepasst werden.
4. services erstellt
5. dependency erstellen
   
# build dependency
```
helm dependency build .\cloudeteer-app\
```   

# helm installieren
```
helm install myapp ./cloudeteer-app/ 
```

# optional / helm upgrade 
```
helm upgrade myapp ./cloudeteer-app/
helm upgrade myapp cloudeteer-app/ --values cloudeteer-app/values.yaml
```

# 
kubectl get pods 
