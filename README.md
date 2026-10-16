# Presupuestos

App de escritorio para Windows que prepara presupuestos con IA a partir del histórico de la empresa.
Aquí solo están las versiones para instalar.

## Instalar

1. Descarga la última versión: **[Presupuestos.zip](https://github.com/andresantonager/presupuestos-versiones/releases/latest/download/Presupuestos.zip)**.
2. Antes de descomprimir: clic derecho en el zip → **Propiedades** → marca **Desbloquear** → Aceptar.
3. Descomprímelo en una carpeta fija (por ejemplo, `C:\Presupuestos`) y abre `Presupuestos\Presupuestos.exe`.
   La primera vez Windows avisará (SmartScreen) porque el programa no está firmado: **Más información** → **Ejecutar de todas formas**.
4. Necesita Windows 10 u 11 de 64 bits. Recomendado: [LibreOffice](https://es.libreoffice.org/), para que los PDF salgan con el formato de la empresa.

No la pongas en «Archivos de programa»: ahí Windows no la deja actualizarse sola.

## Primeros pasos

- **Presupuestos:** pestaña Histórico → «Importar carpeta» o «Subir presupuestos» (.odt, .ods y .pdf).
- **Asistente:** Ajustes → Claves de los proveedores (OpenAI, Claude o Mistral) y, en «Asistente con IA», el proveedor y el modelo.
- **Correo:** Ajustes → Correo. Gmail, con una contraseña de aplicación de Google. Outlook u Hotmail, con «Conectar con Microsoft».
- **Dictado:** el micrófono del Asistente. Con la clave de OpenAI va directamente; sin ella, la primera vez se descarga un modelo básico.
- **Desde el móvil** (opcional): instala [Tailscale](https://tailscale.com/download) en el PC y sigue Ajustes → Acceso desde el móvil.

## Actualizar

Se actualiza sola. Cuando hay una versión nueva, la app avisa junto a su nombre y en Ajustes → Datos → Actualizaciones. Pulsa **Actualizar**: se cierra un momento y se abre ya actualizada.

Tus presupuestos, ajustes y claves no se tocan, porque están en otro sitio:
- `Documentos\Presupuestos`
- `%APPDATA%\Presupuestos`
- `%LOCALAPPDATA%\Presupuestos`
