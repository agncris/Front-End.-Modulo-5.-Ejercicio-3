# Hospital Sale Sano

* PRODUCTO DE UN ERROR NO DETECTADO AL 3/2/2025 LA PANTALLA SE MUESTRA EN BLANCO *

Es un sitio web de presentación de los servicios y personal médico de un hospital ficticio. Este proyecto utiliza: React y Vite para construir una aplicación web moderna, modular y eficiente. Está diseñado con una estructura escalable, utilizando estilos SCSS y enrutamiento manejado con React Router.

## Tecnologías utilizadas

- React
- Vite
- React Router
- SCSS
- Bootstrap

## Actualizaciones e Implementaciones:

### 1. Gestión de Estado con useState
- Implementación de formularios controlados para registro de pacientes y citas médicas
- Almacenamiento temporal de datos del usuario
- Gestión de estados de carga y errores
- Manejo de estados para autenticación y datos de usuario

### 2. Gestión de Efectos Secundarios con useEffect
- Peticiones automáticas a la API para obtener datos de doctores y pacientes
- Actualización automática de datos en tiempo real
- Control de ciclo de vida de componentes
- Manejo de autenticación y tokens JWT

### 3. Hooks Personalizados
- `useFormulario`: Hook personalizado para manejo de formularios con validación
- `useError`: Hook para gestión centralizada de errores
- Validación de datos en tiempo real
- Manejo de estados de envío y respuesta

### 4. Sistema de Manejo de Errores
- Captura y manejo de errores en peticiones API
- Mensajes de error claros y amigables para el usuario
- Validación de formularios con feedback inmediato
- Sistema centralizado de manejo de errores

### 5. Implementación Correcta de Hooks
- Hooks llamados en el nivel superior de los componentes
- No hay llamadas condicionales a Hooks
- Respeto de las reglas y mejores prácticas de React
- Optimización de rendimiento con useCallback y useMemo

## Descripción de páginas y funcionalidades:

- **Inicio (index.jsx)**: Página de bienvenida, mostrando la misión, visión, servicios y testimonios con la intención de generar confianza en nuevos posibles pacientes.
- **Equipo médico (equipo.jsx)**: Sección para mostrar la información de los especialistas que trabajan en el hospital.
- **Contacto (contacto.jsx)**: Página de contacto para que el usuario envíe un mensaje a través de un formulario y vea en un mapa la ubicación del hospital.
- **Reserva de hora (Reservar.jsx)**: Formulario para reservar citas médicas.

## Créditos

Para los elementos gráficos no se utilizaron imágenes cargadas como archivos en la carpeta del proyecto, sino que están conectadas a links de internet.

- **Íconos**: Íconos de servicios y redes sociales fueron tomados de:
  - Iconfinder
  - DuckDuckGo
  - Vecteezy
- **Imágenes**: Las imágenes de perfil de los doctores y el logo fueron obtenidos de:
  - SonicSEO
  - Public Domain Pictures
  - Stockvault

## Estructura del Proyecto

```
📦hospital
 ┣ 📂public
 ┃ ┗ 📜vite.svg
 ┣ 📂src
 ┃ ┣ 📂assets
 ┃ ┃ ┗ 📜react.svg
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📜AppointmentForm.jsx
 ┃ ┃ ┣ 📜Contacto.jsx
 ┃ ┃ ┣ 📜DoctorCard.jsx
 ┃ ┃ ┣ 📜Equipo.jsx
 ┃ ┃ ┣ 📜ErrorBoundary.jsx     # Manejo global de errores
 ┃ ┃ ┣ 📜ErrorMessage.jsx      # Componente de mensajes de error
 ┃ ┃ ┣ 📜Footer.jsx
 ┃ ┃ ┣ 📜Header.jsx
 ┃ ┃ ┣ 📜Home.jsx
 ┃ ┃ ┣ 📜MedicosList.jsx
 ┃ ┃ ┣ 📜ProtectedRoute.jsx    # Rutas protegidas
 ┃ ┃ ┣ 📜Reservar.jsx
 ┃ ┃ ┗ 📜ServiceList.jsx
 ┃ ┣ 📂hooks
 ┃ ┃ ┣ 📜useFormulario.js      # Hook personalizado para formularios
 ┃ ┃ ┣ 📜useError.js           # Hook de manejo de errores
 ┃ ┣ 📂context
 ┃ ┃ ┣ 📜AuthContext.jsx       # Contexto de autenticación
 ┃ ┃ ┣ 📜DoctorContext.jsx     # Contexto de datos médicos
 ┃ ┣ 📂styles
 ┃ ┃ ┣ 📂abstracts
 ┃ ┃ ┃ ┣ 📜_bootstrap-override.scss
 ┃ ┃ ┃ ┣ 📜_breakpoints.scss
 ┃ ┃ ┃ ┣ 📜_functions.scss
 ┃ ┃ ┃ ┣ 📜_mixins.scss
 ┃ ┃ ┃ ┗ 📜_variables.scss
 ┃ ┃ ┣ 📂base
 ┃ ┃ ┃ ┣ 📜_base.scss
 ┃ ┃ ┃ ┣ 📜_resets.scss
 ┃ ┃ ┃ ┗ 📜_typography.scss
 ┃ ┃ ┣ 📂components
 ┃ ┃ ┃ ┣ 📜_button.scss
 ┃ ┃ ┃ ┣ 📜_footer.scss
 ┃ ┃ ┃ ┗ 📜_header.scss
 ┃ ┃ ┣ 📂layout
 ┃ ┃ ┃ ┣ 📜_footer.scss
 ┃ ┃ ┃ ┣ 📜_grid.scss
 ┃ ┃ ┃ ┗ 📜_header.scss
 ┃ ┃ ┣ 📂pages
 ┃ ┃ ┃ ┣ 📜_contacto.scss
 ┃ ┃ ┃ ┣ 📜_equipo.scss
 ┃ ┃ ┃ ┗ 📜_home.scss
 ┃ ┃ ┣ 📂partials
 ┃ ┃ ┃ ┗ 📜_breakpoints.scss
 ┃ ┃ ┣ 📂vendors
 ┃ ┃ ┃ ┗ 📜_bootstrap.scss
 ┃ ┃ ┣ 📜main.css
 ┃ ┃ ┣ 📜main.css.map
 ┃ ┃ ┗ 📜main.scss
 ┃ ┣ 📜App.css
 ┃ ┣ 📜App.jsx
 ┃ ┣ 📜index.css
 ┃ ┗ 📜main.jsx
 ┣ 📂styles
 ┃ ┗ 📜main.css
 ┣ 📜.gitignore
 ┣ 📜eslint.config.js
 ┣ 📜index.html
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ 📜README.md
```

