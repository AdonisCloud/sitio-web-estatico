# Laboratorio AWS – Sitio Web Estático con HTTPS

Este repositorio documenta el despliegue de un sitio web estático en AWS, utilizando:

- Amazon S3 (hosting de archivos estáticos)
- Amazon CloudFront (CDN y HTTPS)
- Certificado SSL gratuito con AWS Certificate Manager (ACM)
- Sin necesidad de dominio propio

---

## Objetivo

Publicar mi currículum como sitio web estático profesional y seguro, accesible desde cualquier navegador con cifrado HTTPS.

---

## Servicios y configuración utilizados

| Servicio     | Función                                    |
|--------------|---------------------------------------------|
| S3           | Almacenamiento y hosting del sitio          |
| CloudFront   | Distribución global y redirección a HTTPS   |
| ACM          | Certificado SSL gratuito                    |

---

## Estructura del proyecto
## Pasos realizados

1. Crear bucket en Amazon S3 con nombre único y habilitar el hosting estático.
2. Subir el archivo `curriculum.html` y las imágenes necesarias.
3. Hacer los archivos públicos mediante políticas de bucket.
4. Crear una distribución de CloudFront con el endpoint del sitio S3 como origen.
5. Habilitar redirección a HTTPS y elegir el certificado SSL proporcionado por ACM.
6. Obtener y probar la URL generada por CloudFront (ejemplo: `https://d3iwj5t24ewe90.cloudfront.net`).

---

## Resultado final

- Sitio accesible en todo el mundo.
- Seguridad mediante HTTPS.
- Despliegue profesional para portafolio técnico.

---

## Autor

**Adonis Rojas** – *Creado como parte de mi aprendizaje en AWS y para documentar mi avance en el mundo cloud.*
