# phyton-final

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Windows

2. Creamos una carpeta o directorio: 

    ```bash
    mkdir python-final
    ```

3. Entramos en ella: 

    ```bash
    cd python-final
    ```

4. Iniciamos el repositorio:

    ```bash
    git init
    ```

5. Creamos un archivo:

    ```bash
    touch finales.py
    ```

6. Abrimos VSC:

    ```bash
    code .
    ```

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

    ```bash
    python -V
    python3 -V
    ```

8. Creamos el entorno virtual en Python:

    ```bash
    python3 -m venv venv #Creamos el entorno virtual
    ```

9. Activamos el entorno virtual:

    ```bash
    source venv/bin/activate #Activamos el entorno virtual en Linux
    venv/scripts/activate #En windows
    ```

10. Hacemos actualización del pip de Python:

    ```bash
    python3 -m pip install --upgrade pip #Actualizamos el pip
    ```

11. Investigar ¿Qué es el pip y por qué lo actualizamos?

    # Pip es el sistema de gestión de paquetes utilizado para instalar y administrar paquetes de software escritos en Python.
    Los paquetes de software son conjuntos de módulos y bibliotecas que pueden ser reutilizados en diferentes proyectos. Los paquetes pueden proporcionar funcionalidades que van desde operaciones matemáticas hasta acceso a bases de datos y análisis de datos, entre otros.

La ventaja de usar un gestor de paquetes como pip es que simplifica el proceso de instalación y actualización de paquetes, así como la gestión de dependencias entre ellos. Además, pip permite a los desarrolladores compartir sus propios paquetes con la comunidad y descargar paquetes creados por otros desarrolladores para usarlos en sus proyectos.


