# Cotizador de Servicio Técnico - Presupuestos Tech 💻

Aplicación web profesional y sobria para cotizar trabajos y reparaciones de computadoras, calcular totales automáticamente y compartir el presupuesto como imagen de alta resolución directamente a WhatsApp.

Inspirada en el formato limpio de planillas de cálculo, pero con un acabado moderno, serio y corporativo listo para enviar a clientes.

---

## 🚀 Características Principales

- **Cálculo Automático**: Suma de repuestos, componentes y horas técnicas en tiempo real con formato de moneda legible (`$ 130,000`).
- **Vista Previa en Vivo**: Diseño sobrio y profesional que refleja exactamente la imagen que recibirá el cliente.
- **Compartir por WhatsApp**:
  - **En Celulares (Android / iPhone)**: Abre WhatsApp directamente adjuntando la imagen del presupuesto y el texto de cortesía mediante la API nativa de compartir.
  - **En Computadora / PC**: Copia la imagen al portapapeles (para pegarla con `Ctrl + V`), descarga el archivo PNG de respaldo y abre WhatsApp Web.
- **Atajos Rápidos de Taller**: Botones para agregar rápidamente servicios habituales (*SSD 240 GB*, *Memoria RAM*, *Hora Técnica*, *Mantenimiento y pasta térmica*, *Instalación de SO*).
- **Datos Personalizables de tu Negocio**: Botón en la esquina superior para configurar el nombre de tu taller, teléfono y dirección. Quedan guardados en tu navegador de forma persistente.
- **100% Estático y Ligero**: Sin necesidad de Node.js en producción, sin frameworks pesados ni compilaciones.

---

## 🌐 Cómo Publicar la App en GitHub Pages (Paso a Paso)

La app está construida con HTML5, Tailwind CSS y JavaScript vanilla, lo que significa que funciona de forma nativa en GitHub Pages sin configurar nada complejo:

1. **Crear el repositorio en GitHub**:
   - Entrá a [github.com/new](https://github.com/new).
   - Nombrá tu repositorio (por ejemplo: `presupuestos-tech` o `cotizador-computacion`).
   - Elegí que sea **Público (Public)** y hacé clic en **Create repository**.

2. **Subir los archivos**:
   - Subí los siguientes archivos de esta carpeta:
     - `index.html`
     - `app.js`
   - O hacelo mediante Git desde tu terminal:
     ```bash
     git init
     git add .
     git commit -m "Primera versión del cotizador"
     git branch -M main
     git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
     git push -u origin main
     ```

3. **Activar GitHub Pages**:
   - En tu repositorio de GitHub, andá a la pestaña **Settings** (Configuración).
   - En el menú lateral izquierdo, hacé clic en **Pages**.
   - En **Build and deployment > Source**, seleccioná **Deploy from a branch**.
   - En **Branch**, elegí `main` y la carpeta `/ (root)`. Hacé clic en **Save**.

4. **¡Listo!** En 1 o 2 minutos tu app estará online en:
   `https://<TU-USUARIO>.github.io/<TU-REPOSITORIO>/`

---

## 💻 Uso Local en tu Computadora

Podés usarla sin conexión a internet ni servidores:
- Simplemente hacé **doble clic en `index.html`** para abrirla en Google Chrome, Edge o tu navegador preferido.
- O podés ejecutar `node server.js` y entrar a `http://localhost:3000`.
