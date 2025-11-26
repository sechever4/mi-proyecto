# Portal de Gestión Académica

Este proyecto es un portal web diseñado para la gestión académica, que permite visualizar información importante como cursos, notas, estado académico y perfil del usuario. Está construido usando HTML, CSS con Bootstrap y FontAwesome para iconografía.

## Autores

- Dalianys
- Santiago
- Andrés

## Descripción del proyecto

El Portal de Gestión Académica es una interfaz intuitiva y responsiva que facilita el acceso a la información educativa de los usuarios. La aplicación presenta una barra lateral de navegación, un encabezado con logo y foto de perfil, y varias secciones con tarjetas que muestran detalles sobre los cursos, estado académico, próximas entregas y perfil.

## Estructura y componentes principales

### Barra lateral (Sidebar)
- Ubicada a la izquierda, fija, con fondo oscuro.
- Incluye enlaces hacia Inicio, Cursos, Notas y Perfil.
- Utiliza iconos de FontAwesome.

### Encabezado (Header)
- Barra superior con el logo del portal y una foto de perfil alineada a la derecha.
- Fondo rojo oscuro (#a20000) y texto blanco.

### Contenido principal
- Tarjetas con información organizada:
  - **Cursos:** Lista de asignaturas y calificaciones.
  - **Estado Académico:** Estado general del estudiante.
  - **Próximas Entregas:** Fechas límite de proyectos.
  - **Perfil:** Datos del estudiante (nombre, correo, créditos, inglés, etc.).

## Tecnologías utilizadas

- HTML
- CSS
- Bootstrap
- FontAwesome
- Archivo `styles.css` para estilos personalizados

---

## Instrucciones para uso y despliegue

### Requisitos previos
- Tener **Git** instalado.
- Navegador moderno (Chrome, Firefox, Edge).
- (Opcional) VS Code + extensión Live Server.

### Cómo clonar el repositorio

#### Clonar vía HTTPS:
```
git clone https://github.com/usuario/nombre-del-repositorio.git
cd nombre-del-repositorio
```

#### Clonar vía SSH:
```
git clone git@github.com:usuario/nombre-del-repositorio.git
cd nombre-del-repositorio
```

👉 *Reemplaza `usuario/nombre-del-repositorio` por el nombre real de tu repositorio.*

### Si NO tienes Git instalado
- **Windows:** Instalar Git for Windows.  
- **Linux:**
```
sudo apt install git
```
- **macOS:**
```
brew install git
```

### Abrir el proyecto localmente
La forma más simple:
- Abrir `index.html` dando doble clic.

### Abrir con Live Server (VS Code)
1. Abrir la carpeta del proyecto en VS Code.  
2. Instalar la extensión **Live Server**.  
3. Clic en “Go Live”.

---

## Despliegue en Amazon EC2 (resumen)

1. Crear instancia **t3.micro** con Ubuntu.
2. Conectarse por SSH:
```
ssh ubuntu@TU_IP_PUBLICA
```
3. Instalar Apache:
```
sudo apt update
sudo apt install apache2 -y
```
4. Subir los archivos vía **scp**, **rsync**, o usando `git clone` en la instancia.
5. Colocar el contenido en:
```
/var/www/html/
```
6. Reiniciar Apache:
```
sudo systemctl restart apache2
```
7. Acceder desde la URL pública de la instancia.

---

## Estructura de archivos

```
/
|-- index.html        # Archivo principal de la página
|-- styles.css        # Estilos personalizados
|-- /imagenes         # Logos y fotos utilizadas
```

## Detalles de estilos importantes

- Barra lateral: ancho 230px, fondo #1f2a36, texto blanco.
- Efecto hover en navegación.
- Encabezado rojo oscuro (#a20000) con logo redondeado.
- Tarjetas con borde redondeado, sombra ligera y fondo blanco.
- Fondo general claro (#f4f6fb) para contraste.

---

## Agradecimientos

Muchas gracias por su atención.  
Agradecemos el tiempo dedicado a revisar este proyecto y esperamos que su estructura, funcionalidad y claridad sean de utilidad para futuros desarrollos o evaluaciones.  
Quedamos atentos a cualquier sugerencia, recomendación o mejora que pueda enriquecer este trabajo.  
Nuestro objetivo es seguir aprendiendo, creciendo y aplicando buenas prácticas en cada entrega.

¡Gracias nuevamente por su tiempo y consideración!