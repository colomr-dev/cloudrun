# 👋 Hello World en Cloud Run

Este es un ejemplo básico de una aplicación Python desplegada en Google Cloud Run.

## 🛠️ Estructura
- `app.py`: Aplicación Flask que sirve una página web simple
- `Dockerfile`: Configuración para construir el contenedor
- `requirements.txt`: Dependencias Python necesarias
- `static/`: Recursos estáticos (CSS, imágenes)
- `templates/`: Plantillas HTML

## 🚀 Despliegue Local
1. Construir el contenedor:
```bash
docker build -t hello-world .
```

2. Ejecutar localmente:
```bash
docker run -p 8080:8080 hello-world
```

## 📝 Notas
- La aplicación escucha en el puerto 8080 (requerido por Cloud Run)
- Incluye ejemplos de uso de recursos estáticos y plantillas
- Demuestra las mejores prácticas para aplicaciones Cloud Run
