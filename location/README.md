# 🌐 Objeto JavaScript: `location`

El objeto `location` en JavaScript forma parte del objeto global `window`, y representa la **URL actual** que se muestra en el navegador. A través de él, es posible **obtener información** detallada de la URL y también **modificarla**, lo que lo convierte en una herramienta poderosa para controlar la navegación dentro de las aplicaciones web.

---

## 📚 ¿Para qué sirve el objeto `location`?

El objeto `location` se utiliza para:

- Obtener la URL completa de la página.
- Redireccionar al usuario a otra página o sitio web.
- Recargar la página actual.
- Analizar partes específicas de la URL como el dominio, el protocolo, el puerto, los parámetros de búsqueda, etc.
- Manipular el historial de navegación (en combinación con otros métodos del objeto `window`).

Este objeto es **muy utilizado** en el desarrollo web para:
- Crear navegaciones dinámicas.
- Procesar parámetros de búsqueda en la URL.
- Hacer redirecciones automáticas.
- Validar dominios.
- Cargar recursos en función de la URL actual.

---

## 🔑 Principales propiedades de `location`

| Propiedad             | Descripción |
|----------------------|-------------|
| `location.href`      | Devuelve la URL completa del documento actual. También se puede modificar para redirigir al usuario. |
| `location.hostname`  | Devuelve el nombre del dominio (por ejemplo, `www.ejemplo.com`). |
| `location.pathname`  | Devuelve la ruta del archivo (por ejemplo, `/carpeta/pagina.html`). |
| `location.protocol`  | Devuelve el protocolo usado (`http:`, `https:`). |
| `location.port`      | Devuelve el número del puerto usado (si está presente). |
| `location.hash`      | Devuelve el "fragmento" de la URL (lo que sigue al símbolo `#`). Útil para navegación en una sola página (SPA). |
| `location.search`    | Devuelve los parámetros de búsqueda de la URL (por ejemplo, `?id=123&nombre=juan`). |

---

## 🛠️ Métodos del objeto `location`

| Método                   | Descripción |
|--------------------------|-------------|
| `location.assign(url)`   | Carga una nueva página desde la URL especificada. La nueva URL se guarda en el historial del navegador. |
| `location.replace(url)`  | Reemplaza la página actual por otra sin guardar la URL en el historial (no permite regresar con "Atrás"). |
| `location.reload()`      | Recarga la página actual. Puede forzar la recarga desde el servidor si se le pasa `true`. |

---
