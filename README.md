	# Infraestructura de Odoo 19 con Docker

Este repositorio contiene la configuración de Infraestructura como Código (IaC) para desplegar **Odoo 19 (LTS)** utilizando Docker y Docker Compose.

El objetivo es crear una instancia robusta, portable y segura de Odoo, diseñada inicialmente para gestionar un taller informático y dar soporte a usuarios.

---

## 🚀 Puesta en Marcha (Entorno Local)

Esta configuración está lista para un despliegue local inmediato. Expone Odoo directamente en el puerto `8069`.

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/Enzonmds/odoo-sistemas.git](https://github.com/Enzonmds/odoo-sistemas.git)
    cd odoo-sistemas
    ```

2.  **Levanta los contenedores:**
    Asegúrate de tener Docker en ejecución y luego lanza el entorno en modo "detached" (en segundo plano).
    ```bash
    docker compose up -d
    ```

3.  **¡Accede a Odoo!**
    Espera unos 30-60 segundos para que Odoo se inicie por primera vez. Luego, abre tu navegador y ve a:
    * **[http://localhost:8069](http://localhost:8069)**

Para detener todo el entorno, simplemente ejecuta:
```bash
docker compose down
