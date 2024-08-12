### Importar la Base de Datos
1. Instala PostgreSQL y pgAdmin.
2. Crea una nueva base de datos en pgAdmin con el nombre `nombre_de_tu_base_de_datos`.
3. Haz clic derecho en la base de datos y selecciona **Restore** (para archivos .backup) o **Query Tool** (para archivos .sql).
4. Si usas la Query Tool, carga el archivo `db/tu_base_de_datos.sql` y ejecuta el script para crear las tablas y datos necesarios.

En tu terminal:

psql -U tu_usuario -h localhost -p 5432 -d nombre_de_tu_base_de_datos -f ruta_del_archivo/tu_base_de_datos.sql
