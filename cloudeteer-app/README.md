

# Start minikube
```
minikube start
```

# helm erstellen
```
helm create cloudeteer
```

# deployment.yaml und service.yaml datein erstellen 
   
1. appname festgelegt
2. namespace erstellt
3. Persistenzvolume optional kann in values.yaml geändert werden.
4. replicas und Umgebungsvariablen können in values datei angepasst werden.
5. services erstellt
   

# helm installieren
```
helm install cloudeteer-release cloudeteer-app/ --values cloudeteer-app/values.yaml
```

# optional / helm upgrade 
```
helm upgrade cloudeteer-release cloudeteer-app/ --values cloudeteer-app/values.yaml
```


