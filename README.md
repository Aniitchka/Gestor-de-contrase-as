# Secure Vault - Gestor de Contraseñas Personal

Un gestor de contraseñas de escritorio seguro, ligero y desarrollado desde cero en Python, implementando estándares de criptografía de grado industrial para garantizar la privacidad absoluta de las credenciales.

---

## Características Principales

* **Cifrado Fuerte:** Utiliza **AES-256-GCM** (Cifrado Simétrico Autenticado) para asegurar que los datos no solo estén ocultos, sino protegidos contra cualquier intento de manipulación o alteración externa.
* **Derivación de Claves:** Implementa **PBKDF2HMAC** con 600,000 iteraciones y un `salt` único para blindar la contraseña maestra frente a ataques de fuerza bruta.
* **Interfaz Gráfica Intuitiva (GUI):** Ventana de escritorio construida con `tkinter` que incluye una barra de búsqueda en tiempo real para filtrar servicios al instante.
* **Generador de Contraseñas Seguras:** Creación de claves aleatorias de alta entropía utilizando el módulo criptográfico `secrets` de Python.
* **Integración con el Portapapeles:** Copiado automático de contraseñas con un solo clic mediante `pyperclip`.

---

## Tecnologías y Librerías Utilizadas

* **Python 3.x**
* `cryptography` — Para las funciones criptográficas y derivación de claves.
* `tkinter` — Para la interfaz gráfica de usuario.
* `pyperclip` — Para la gestión del portapapeles del sistema.

---

## Instalación y Configuración

1. Clona este repositorio o descarga los archivos en tu equipo.
2. Asegúrate de tener Python instalado y ejecuta el siguiente comando en tu terminal para instalar las dependencias necesarias:
   ```bash
   pip install cryptography pyperclip

---

## Roadmap / Próximas Mejoras (Futuro)
[ ] Implementar un temporizador para limpiar el portapapeles automáticamente después de unos segundos.
[ ] Agregar exportación e importación de respaldos cifrados del baúl.
[ ] Mejorar el diseño visual con temas personalizados (Modo Oscuro / Claro).
