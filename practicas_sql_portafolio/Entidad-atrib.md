# Portafolio

## Lista de Entidades y Atributos

### Persona  
- id_persona **(PK)**
- nombre
- apellido
- titulo
- url_banner
- url_imagen_persona
- sobre_mi 
- contacto **(FK)**

### Experiencia Laboral
- id_experiencia **(PK)**
- url_logo_empresa
- nombre_empresa
- puesto 
- trabajo_actual
- inicio
- finalizacion
- descripcion

### Educación
- id_educación **(PK)**
- url_foto_instituto
- nombre_instituto
- titulo
- inicio
- fin
- porcentaje


### Certificados
- id_educación **(PK)**
- url_foto_instituto
- nombre_instituto
- certificado
- anio
- porcentaje 

### Hard & Soft Skills
- id_hard & soft skill **(PK)**
- tipo_habilidad 
- nombre
- grado_dominio


### Proyectos
- id_proyecto **(PK)**
- nombre_proyecto
- fecha
- descripcion
- url_imagen
- url_proyecto
- tecnologia

### Redes
- id_redes **(PK)**
- nombre
- url_imagen


### Contacto
- id_contacto **(PK)**
- correo
- telefono

### Usuario
- id_usuario **(PK)**
- contrasenia


