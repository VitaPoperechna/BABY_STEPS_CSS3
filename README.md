# BABY_STEPS_CSS3
## ⚙️ Instalación y Configuración

Sigue estos pasos para ejecutar el proyecto localmente:

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/VitaPoperechna/BABY_STEPS_CSS3.git
    cd [nombre-del-repositorio]

2.  **Construye la imagen Docker::**
    ```bash
    docker build -t baby-steps-css .
   
    ```

3.  **Ejecuta el contenedor:**
    ```bash
    docker run -d -p 8080:80 baby-steps-css
    ```

4.  **Abre el proyecto en el navegador:**
   Accede a http://localhost:8080

   Este proyecto usa nginx:alpined como servidor web ligero para servir los archivos estáticos (HTML, CSS).

   Asegúrate de que el puerto 8080 no esté en uso por otra aplicación.