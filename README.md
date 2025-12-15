# Simon dice k8s

### Paso 1
Lista de manifiestos para deployar, utilice Docker Hub en Windows (WSL) y Active la opción de Kubernetes.
<img width="1308" height="715" alt="image" src="https://github.com/user-attachments/assets/105a05d1-2c5f-42aa-8b49-a16451ca7942" />

### Paso 2 
Descarga los manifiestos "Manifests" en criollo, los archivos de este repo.

### Paso 3
Abri la linea de comandos que utilices
Posicionate en la carpeta con los manifiestos
IMPORTANTE: Si no tenes las imágenes previas tenes que descargar con 
```
docker login
docker pull mrelexay/eko-apilayer:1.0.0
docker pull mrelexay/eko-db:1.0.0
docker pullmrelexay/eko-frontend:1.0.0
```

Luego simplemente:
```
kubectl apply -f .
```




