# Laboratorio # 2: HTML5 y CSS3

📅 Fecha: [10/02/2026]

## 📄 Contenido del Repositorio

Este repositorio contiene el desarrollo del Laboratorio #2 de la asignatura Desarrollo Web, correspondiente al Módulo II: Diseño Web con HTML5 y CSS3. Incluye la maquetación estructurada de datos tabulares, el uso de elementos semánticos de HTML5, la implementación de hipervínculos seguros, y la aplicación de selectores CSS (etiqueta, clase e ID) para estilizar contenido de manera profesional.

## 🛠️ Tecnologías Utilizadas

- **Lenguaje de marcado:** HTML5
- **Estilos:** CSS3
- **Servidor local:** WampServer 3.4.0 (Apache 2.4.65)
- **Editor:** Visual Studio Code
- **Navegador:** Opera GX
- **Control de versiones:** Git / GitHub

## 🖥️ Capturas de Pantalla y Problemas

### Interfaz Principal

*(Aquí se incluye la imagen de la salida de cada problema)*

- **Tabla #1 (`tablas.html`):** tabla de informe de gastos de viaje usando `<th>`, y los atributos `headers` y `axis` para asociar cada celda de datos con su encabezado correspondiente, además de metadatos completos en `<head>` (charset, viewport, description, keywords, author, robots).

 <img width="670" height="415" alt="image" src="https://github.com/user-attachments/assets/195aaff9-fe9e-4b83-93ac-b82dc0929b4b" />

- **Tabla #2 (`tablas2.html` + `Estilos/estilosTabla.css`):** la misma tabla de datos, estilizada con un archivo CSS externo usando selectores de clase (`.tabla`, `.tabla th`, `.modo1`, `.modo2`) para alternar la apariencia de las filas.

 <img width="652" height="160" alt="image" src="https://github.com/user-attachments/assets/aee2babb-3bfb-4469-85f9-e6d1aebb5fa3" />


- **Ejemplo #3 (`parrafos.html` + `Estilos/estilosParrafos.css`):** párrafo con una cita (`<q>`) y texto en negrita (`<strong>`), estilizado mediante el selector descendiente `p strong`.

<img width="785" height="137" alt="image" src="https://github.com/user-attachments/assets/f50299bc-1ed2-424b-bfed-608c387b8898" />


- **Ejemplo #4 (`Ejemplo1.html`):** sección con un hipervínculo externo seguro (`target="_blank" rel="noopener"`), usando selector de clase (`.card-seccion`, `.link-externo`) y selector de ID (`#footer-recurso`) con estilos embebidos.

<img width="3662" height="512" alt="image" src="https://github.com/user-attachments/assets/a0c92a4e-4d3a-46e0-ae70-8fc2b38ce04d" />
<img width="3655" height="1217" alt="image" src="https://github.com/user-attachments/assets/5206ba78-252c-4756-8bb3-80552b2bdd95" />


- **Ejemplo #5 (`EjemploSecciones.html`):** estructura semántica completa con `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` y `<footer>`, cada uno con su propio estilo visual.

  <img width="3697" height="1560" alt="image" src="https://github.com/user-attachments/assets/67d5a05d-e4c3-416e-950d-943b1e1129d2" />


## 📁 Estructura de Carpetas o Directorios

```
laboratorio2/
├── tablas.html              # Tabla #1: informe de gastos con metadatos completos
├── tablas2.html              # Tabla #2: tabla estilizada con CSS externo
├── parrafos.html              # Ejemplo #3: cita y texto resaltado
├── Ejemplo1.html                # Ejemplo #4: clases, ID y enlace externo seguro
├── EjemploSecciones.html          # Ejemplo #5: estructura semántica completa
├── Estilos/
│   ├── estilosTabla.css           # Estilos de la Tabla #2
│   └── estilosParrafos.css        # Estilos del Ejemplo #3
└── README.md                        # Documentación del proyecto
```

## ▶️ Instrucciones de Ejecución / Uso

1. Clonar el repositorio.
2. Copiar la carpeta del proyecto dentro de `C:\wamp64\www\` (o la carpeta `htdocs` de tu servidor local).
3. Iniciar WampServer y verificar que Apache esté activo (ícono en verde).
4. Abrir el navegador y acceder a cada archivo, por ejemplo:
   - `http://localhost/laboratorio2/tablas.html`
   - `http://localhost/laboratorio2/tablas2.html`
   - `http://localhost/laboratorio2/parrafos.html`
   - `http://localhost/laboratorio2/Ejemplo1.html`
   - `http://localhost/laboratorio2/EjemploSecciones.html`

## 👤 Autor y Contexto

- **Nombre:** René
- **Institución:** Universidad Tecnológica de Panamá (UTP) - Facultad de Ingeniería en Sistemas, Campus Víctor Levy Sasso
- **Fecha de Realización:** [10/02/2026]

## 🔗 Referencias

- Laboratorio #2: HTML5 y CSS3 - Módulo II: Diseño Web con HTML5 y CSS3
- Documentación oficial de HTML5: https://developer.mozilla.org/es/docs/Web/HTML
- Documentación oficial de CSS3: https://developer.mozilla.org/es/docs/Web/CSS
