# Instalador del Menú Contextual de Cursor

Este proyecto proporciona una manera sencilla de agregar y eliminar un elemento en el menú contextual del Explorador de Windows para abrir directorios con la aplicación Cursor.

<div align="center">
  <p>
    🤝 Muestra tu apoyo - dale una ⭐️ si te gustó la herramienta 🤝
  </p>
  <p>
    <a target="_blank" href='https://twitter.com/hexcreator'><img src="https://img.shields.io/twitter/follow/hexcreator" alt="Seguir en X (anteriormente Twitter)" width="180" height="30"/></a>
  </p>
</div>

---

## Instalación

Para instalar el elemento del menú contextual, ejecuta el ejecutable `install`. Por defecto, utilizará la ruta `C:\Users\%USERNAME%\AppData\Local\Programs\cursor\Cursor.exe` para la aplicación Cursor. También puedes proporcionar una ruta personalizada al ejecutable de Cursor como argumento en la línea de comandos.

## Compilación

Usé MinGW para compilar este proyecto, pero puedes usar cualquier otro compilador que soporte C++. Comandos de ejemplo:

```bash
g++ -o install install.cpp -static
g++ -o uninstall uninstall.cpp -static
```

## Instrucciones de Uso

Para utilizar el elemento del menú contextual, sigue estos pasos:

1. **Descarga los Ejecutables:**
   - Visita la [página de lanzamientos](https://github.com/hexcreator/open-with-cursor/releases) de este proyecto.
   - Descarga los archivos `install.exe` y `uninstall.exe` de la última versión.

2. **Instala el Elemento del Menú Contextual:**
   - Ejecuta el archivo `install.exe`.
   - Por defecto, utilizará la ruta `C:\Users\%USERNAME%\AppData\Local\Programs\cursor\Cursor.exe` para la aplicación Cursor.
   - Si deseas usar una ruta personalizada para el ejecutable de Cursor, proporciona la ruta como argumento en la línea de comandos al ejecutar `install.exe`.
   - También puedes proporcionar el argumento de línea de comandos `-a` para instalar el elemento del menú contextual para todos los archivos, no solo para directorios.

3. **Desinstala el Elemento del Menú Contextual:**
   - Ejecuta el archivo `uninstall.exe` para eliminar el elemento del menú contextual.
