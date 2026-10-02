# Proyecto Colaborativo Git y GitHub - Taller Final

## 1. Integrantes del Equipo
* **Estudiante A:** [David Galarza A] - *Rol: Administrador / Integración*
* **Estudiante B:** [Matias Ruales B] - *Rol: Colaborador / Desarrollo*

---

## 2. Descripción del Proyecto
Este proyecto es un sitio web desarrollado de manera colaborativa utilizando un flujo de trabajo basado en ramas (`dev/estudiante-a` y `dev/estudiante-b`), Pull Requests y revisiones de código cruzadas.

---

## 3. Registro de Conflictos y Resolución
Durante la fase del Taller 2, se provocó un conflicto de fusión intencional en el archivo `style.css` al modificar simultáneamente la misma regla de estilos (`body`).

### Evidencia del Conflicto:
*(Inserta aquí la captura de pantalla guardada previamente con las marcas <<<<<<<, =======, >>>>>>>)*

![Conflicto Git](./ruta-o-nombre-de-tu-captura.png)

### Pasos de Resolución:
1. Se identificó el conflicto mediante la terminal con `git merge`.
2. Se analizaron las líneas en conflicto dentro de VS Code.
3. Se seleccionaron los estilos finales y se eliminaron manualmente las marcas del conflicto.
4. Se ejecutó `git add`, `git commit` y `git push` para confirmar la unificación del código.

---

## 4. Instrucciones de Ejecución
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/dgdavidgalarzaG788/proyecto-final.git](https://github.com/dgdavidgalarzaG788/proyecto-final.git)