### **Erstelle ein Image**
```
docker build -t mein-image .
```

### **Erstelle ein Container**
```
docker run -p 8080:8080 mein-image
```

Schlussendlich sollte man unter http://localhost:8080 das hier sehen:
![](Screenshots/Ende.png)