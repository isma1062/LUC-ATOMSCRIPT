

# Paquete de LUC y AtomScript para Sublime Text

Este paquete proporciona soporte completo para los lenguajes `LUC` y `AtomScript`, convirtiendo Sublime Text en un potente entorno de desarrollo para crear aplicaciones web híbridas.

## Características

- **Coloreado de Sintaxis Avanzado:** Distingue claramente entre palabras clave de AtomScript, etiquetas HTML, CSS, JavaScript y strings.
- **Snippets Productivos:** Escribe código más rápido con atajos para `componente`, `dato`, y `accion`.
- **Sistema de Ejecución Integrado:** Lanza tu aplicación en el **Navegador Atom/LUC** directamente desde Sublime Text con `Ctrl+B`.

## Instalación

1. Asegúrate de tener instalado [Package Control](https://packagecontrol.io/installation).
2. Abre la paleta de comandos (`Ctrl+Shift+P` o `Cmd+Shift+P`).
3. Selecciona `Package Control: Add Repository`.
4. Pega la URL de tu repositorio de GitHub aquí: `[DEJA ESTE ESPACIO VACÍO POR AHORA]`
5. Abre la paleta de comandos de nuevo, selecciona `Package Control: Install Package`.
6. Busca y selecciona `LUC`.

## Uso

### Sistema de Ejecución (`Ctrl+B`)

Para que el sistema de ejecución funcione, debes editar el archivo `LUC.sublime-build` después de la instalación.

1. Ve a `Preferences` > `Browse Packages...`.
2. Entra en la carpeta `LUC`.
3. Abre `LUC.sublime-build` y modifica la ruta en la sección `"cmd"` para que apunte a tu ejecutable `navegador.py`.

**Ejemplo:**
```json
{
    "cmd": ["/ruta/a/tu/python", "/ruta/a/tu/navegador.py", "$file"]
}# LUC-ATOMSCRIPT
