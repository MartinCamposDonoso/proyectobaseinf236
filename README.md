# Proyecto Base INF236

## Requisitos

1. **Docker**: Asegúrate de tener Docker y Docker Compose instalados en tu máquina. Puedes descargar Docker desde [aquí](https://www.docker.com/products/docker-desktop).

## Pasos de Instalación

### 1. Clonar el Repositorio

Primero, clona el repositorio en tu máquina local usando Git:

```bash
git clone https://gitlab.com/martin2316/proyectobaseinf236.git
cd proyectobaseinf236
```

### 2. Descargar e Inicializar Docker

1. **Descargar Docker**: Si aún no tienes Docker instalado, descárgalo desde [Docker Desktop](https://www.docker.com/products/docker-desktop) y sigue las instrucciones de instalación.

2. **Inicializar Docker Desktop**: Abre Docker Desktop y asegúrate de que esté en ejecución.

### 3. Construir y Levantar el Proyecto

Una vez que Docker esté en funcionamiento, construye las imágenes de Docker y levanta los contenedores del proyecto con los siguientes comandos:

```bash
docker-compose up --build
```

Ahora cierra la terminal.

### 4. Levantar el Proyecto

Para iniciar el proyecto después de haber construido las imágenes,  usa:

```bash
docker-compose up
```

#### 5. Verificar el Funcionamiento

Una vez que el proyecto esté en ejecución, visita http://127.0.0.1:8000/docs en tu navegador para probar los endpoints disponibles.

## Notas Adicionales

- Asegúrate de que Docker esté ejecutándose correctamente antes de ejecutar los comandos.

Si tienes alguna pregunta o encuentras algún problema, no dudes en preguntar al tutor