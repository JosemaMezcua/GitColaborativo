# GitColaborativo

## 📌 Descripción
Tarea Despliegue Aplicaciones Web Git Colaborativo

## 👥 Equipo y Roles
- **Líder de Proyecto:** Jose Manuel Mezcua Rivas 
- **Desarrollador de Estructura (HTML):** Manuel Navarro Pozuelo 
- **Diseñador CSS:** Juan Prados Cantarero  
- **Programador JavaScript:** Rafael Moreno Torres  
- **Tester:** Francisco Jesus Lopez Carrillo 

## 📂 Estructura de Ramas
- **principal** → Rama principal donde se integrará el trabajo final.
- **desarrollo** → Rama donde se combinarán las características antes de pasar a `principal`.
- **tarea-nombre-de-la-tarea** → Ramas individuales para cada nueva funcionalidad o modificación.

## 🔄 Flujo de Trabajo

1. **Clonar el repositorio**
   ```sh
   git clone [URL-del-repositorio]
   cd [nombre-del-repositorio]
   git checkout -b desarrollo origin/desarrollo
   ```

2. **Crear una nueva rama desde `desarrollo`**
   ```sh
   git checkout -b tarea-nombre-de-la-tarea desarrollo
   ```

3. **Realizar cambios y confirmar los commits**
   ```sh
   git add .
   git commit -m "Descripción clara de los cambios"
   ```

4. **Subir la rama al repositorio remoto**
   ```sh
   git push origin tarea-nombre-de-la-tarea
   ```

5. **Crear un Pull Request (PR) hacia `desarrollo`**
   - En GitHub, ir a la pestaña `Pull Requests` y seleccionar la rama creada.
   - Enviar la solicitud y etiquetar al líder del proyecto para su revisión.

6. **Revisión y aprobación**
   - El líder del proyecto revisará los cambios y resolverá posibles conflictos.
   - Una vez aprobado, se fusiona la rama en `desarrollo`.

7. **Integración final en `principal`**
   - Cuando todas las tareas estén en `desarrollo`, se hace un PR final hacia `principal`.

## 📸 Entrega Final
Cada equipo debe:
- Compartir la URL del repositorio.
- Enviar capturas de pantalla del historial de commits y ramas con:
   ```sh
   git log --oneline --graph
   ```

_Cualquier duda, contactar al líder del proyecto._

