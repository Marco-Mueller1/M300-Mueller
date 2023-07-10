### **Erstelle ein Image**
```
docker build -t imagename .
```

### **Erstelle ein Container**
```
docker run -p 8080:8080 imagename
```

Schlussendlich sollte man unter http://localhost:8080 das hier sehen:
![](Screenshots/Ende.png)