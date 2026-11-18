# parcial2-v2-software

**Alumno:** Federico Javier Romero
**Fecha:** 18/11/26

Página web simple de control de stock, empaquetada con Docker (nginx:alpine)

## Cómo construir y ejecutar

```bash
docker build -t parcial2-v2-software .
docker run -d -p 8080:80 parcial2-v2-software
```

Abrir en el navegador: http://localhost:8080