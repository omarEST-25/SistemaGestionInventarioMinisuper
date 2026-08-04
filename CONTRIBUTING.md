# Guía de Contribución

Gracias por tu interés en contribuir al **Sistema de Gestión de Inventario para Mini Súper**.

Esta guía describe el flujo de trabajo que debe seguir cualquier integrante del proyecto para mantener un desarrollo ordenado.



# Flujo de trabajo

## 1. Clonar el repositorio

```bash
git clone https://github.com/omarEST-25/SistemaGestionInventarioMinisuper.git
```



## 2. Crear una nueva rama

Nunca trabajes directamente sobre la rama **main** o **master**.

Crear una rama con un nombre relacionado con la funcionalidad que se desarrollará.

Ejemplo:

```bash
git checkout -b feature/gestion-productos
```



## 3. Realizar los cambios

Implementar la nueva funcionalidad o corregir el problema identificado.



## 4. Guardar los cambios

```bash
git add .
git commit -m "Descripción de la funcionalidad implementada"
```


## 5. Enviar la rama al repositorio

```bash
git push origin feature/gestion-productos
```

---

## 6. Crear un Pull Request

Ingresar al repositorio en GitHub y crear un **Pull Request** hacia la rama **develop**.



## 7. Revisión

El responsable del proyecto revisará:

- Calidad del código.
- Funcionamiento.
- Cumplimiento de los requerimientos.



## 8. Merge

Una vez aprobados los cambios, el Pull Request será integrado a la rama **develop**.

Posteriormente se realizará el Merge hacia la rama principal.



# Recomendaciones

- Utilizar nombres descriptivos para las ramas.
- Realizar commits pequeños y frecuentes.
- Documentar nuevas funcionalidades.
- Mantener actualizado el README y la Wiki.
- Verificar que el proyecto compile correctamente antes de enviar un Pull Request.
