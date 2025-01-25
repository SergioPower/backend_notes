# App de Notas

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) 
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

## Descripción

Esta es una aplicación web para la gestión de notas personales. Permite a los usuarios crear, editar, eliminar y visualizar notas de manera sencilla. La aplicación está construida con un backend personalizado utilizando Render y una base de datos MongoDB, mientras que el frontend está desarrollado con React y alojado en la carpeta `dist`.

---

## Características

- Creación de notas con títulos y descripciones.
- Edición en tiempo real de las notas existentes.
- Eliminación de notas innecesarias.
- Visualización fácil e intuitiva de todas las notas.

---

## Tecnologías

### Backend:
- **Node.js**: Entorno de ejecución para el backend.
- **Render**: Para el despliegue del servidor backend.
- **MongoDB**: Base de datos NoSQL para almacenar las notas.



### Frontend:

- **React**: Biblioteca JavaScript para construir la interfaz de usuario.

---

## Estructura del Proyecto

```
root
├── dist/                 # Contiene el frontend construido con React
├── src/                  # Código fuente del backend
├── package.json          # Dependencias y scripts del proyecto
├── README.md             # Documentación del proyecto
└── ...                   # Otros archivos de configuración
```

---

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   ```

2. Instala las dependencias del backend:

   ```bash
   cd tu-repositorio
   npm install
   ```

3. Configura las variables de entorno para conectar a MongoDB. Crea un archivo `.env` en la raíz con los siguientes valores:

   ```env
   MONGODB_URI=tu_url_de_mongodb
   PORT=puerto_para_el_backend
   ```

4. Ejecuta el servidor:

   ```bash
   npm start
   ```

5. Accede al frontend alojado en la carpeta `dist`. Puedes servir esta carpeta usando cualquier servidor estático o configurarla en Render para despliegue.

---

## Uso

1. Ve al dominio donde está alojada la aplicación.
2. Usa la interfaz para:
   - Crear nuevas notas.
   - Editar notas existentes.
   - Eliminar notas que ya no necesites.
3. Los cambios se sincronizan con la base de datos en tiempo real.

---

## Contribución

1. Haz un fork del proyecto.
2. Crea una rama para tu funcionalidad:
   ```bash
   git checkout -b mi-nueva-funcionalidad
   ```
3. Realiza tus cambios y haz commit:
   ```bash
   git commit -m "Agrega mi nueva funcionalidad"
   ```
4. Sube tus cambios:
   ```bash
   git push origin mi-nueva-funcionalidad
   ```
5. Abre un Pull Request en este repositorio.

---

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

