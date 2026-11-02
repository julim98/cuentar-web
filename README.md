# Cuent-Ar Web · Landing Page & Android App Links

Sitio web estático oficial y portal de enlaces universales de la aplicación móvil **Cuent-Ar** (Gestión financiera y gastos compartidos con privacidad Zero-Knowledge).

## 🌐 URLs del Sitio
* **Web Oficial / Landing:** [https://julim98.github.io/cuentar-web/](https://julim98.github.io/cuentar-web/)
* **Receptor de Invitaciones a Grupos:** [https://julim98.github.io/cuentar-web/join](https://julim98.github.io/cuentar-web/join)
* **Verificación Digital Asset Links (Android):** [https://julim98.github.io/cuentar-web/.well-known/assetlinks.json](https://julim98.github.io/cuentar-web/.well-known/assetlinks.json)

---

## 📁 Estructura del Repositorio

* **`index.html`:** Página web de inicio y presentación de Cuent-Ar.
* **`join.html` / `join/index.html`:** Receptor universal de invitaciones. Si se abre desde un navegador (PC o celular sin la app), muestra el código del grupo y redirige automáticamente al esquema nativo `cuentar://join`.
* **`.well-known/assetlinks.json`:** Archivo de verificación de **Android App Links**. Contiene las huellas digitales públicas SHA-256 de los certificados de firma (Release y Debug) para que Android abra la app directamente desde cualquier enlace compartido sin pasar por el navegador.
* **`.nojekyll`:** Archivo indicador para GitHub Pages, necesario para que el servidor de GitHub no ignore los directorios ocultos que comienzan con un punto (`.well-known`).

---

## 🚀 Despliegue en GitHub Pages

1. En el repositorio de GitHub, ir a **Settings > Pages**.
2. En **Build and deployment > Source**, seleccionar `Deploy from a branch`.
3. Seleccionar la rama (`main` o `gh-pages`) y la carpeta `/ (root)`.
4. Guardar los cambios. GitHub publicará el sitio automáticamente en segundos.

---

## 🔒 Privacidad y Seguridad
Este repositorio contiene exclusivamente contenido estático público (HTML, CSS y certificados públicos). No contiene claves privadas, contraseñas ni tokens sensibles.
