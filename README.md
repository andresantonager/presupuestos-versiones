# Presupuestos

App de escritorio para Windows que prepara presupuestos con IA a partir del histórico de la empresa.
Aquí solo están las versiones para instalar.

## Instalar

1. Descarga el instalador: **[Instalar-Presupuestos.exe](https://github.com/andresantonager/presupuestos-versiones/releases/latest/download/Instalar-Presupuestos.exe)**.
   Si el navegador avisa de que «no se descarga con frecuencia», elige **Conservar**.
2. Ábrelo. La primera vez Windows avisará (SmartScreen) porque el programa no está firmado: **Más información** → **Ejecutar de todas formas**.
3. Pulsa **Instalar** (si quieres, deja marcado el acceso directo en el escritorio) y después **Finalizar**: se abre la app.

No hace falta ser administrador: se instala para tu usuario. Se desinstala desde Configuración → Aplicaciones, como cualquier otra.

Necesita Windows 10 u 11 de 64 bits. Recomendado: [LibreOffice](https://es.libreoffice.org/), para que los PDF salgan con el formato de la empresa.

## Primeros pasos

- **Presupuestos:** pestaña Histórico → «Importar carpeta» o «Subir presupuestos» (.odt, .ods y .pdf).
- **Asistente:** Ajustes → Claves de los proveedores (OpenAI, Claude o Mistral) y, en «Asistente con IA», el proveedor y el modelo.
- **Correo:** Ajustes → Correo. Gmail, con una contraseña de aplicación de Google. Outlook u Hotmail, con «Conectar con Microsoft».
- **Dictado:** el micrófono del Asistente. Con la clave de OpenAI va directamente; sin ella, la primera vez se descarga un modelo básico.
- **Desde el móvil** (opcional): instala [Tailscale](https://tailscale.com/download) en el PC y sigue Ajustes → Acceso desde el móvil.

## Actualizar

No hay que hacer nada: se actualiza sola, sin preguntar. Cuando hay una versión nueva, la descarga en segundo plano y la instala al cerrar la app, o al abrirla la próxima vez. En Ajustes → Datos → Actualizaciones se ve cómo va y está el botón «Actualizar ahora».

Tus presupuestos, ajustes y claves no se tocan, porque están en otro sitio:
- `Documentos\Presupuestos`
- `%APPDATA%\Presupuestos`
- `%LOCALAPPDATA%\Presupuestos`

Sin instalador también vale: descarga [Presupuestos.zip](https://github.com/andresantonager/presupuestos-versiones/releases/latest/download/Presupuestos.zip) y descomprímelo en una carpeta tuya, como `C:\Presupuestos`, no en «Archivos de programa». Antes, clic derecho → Propiedades → Desbloquear.
