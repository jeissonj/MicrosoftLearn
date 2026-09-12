De la parte de GitHub 
El contenido del curso es 
- Información general breve de la plataforma GitHub Enterprise
- Creación de un repositorio
- Adición de archivos a un repositorio
- Búsqueda de repositorios
- Introducción a gists y wikis

para la Creación de una nueva rama se usaa
git checkout -b newBranchName
ese codigo nos  hubia de una ez en la nueva rama 


Los estados principales de un archivo de un repositorio de Git son Untracked y Tracked.

Sin seguimiento: Estado inicial de un archivo cuando aún no forma parte del repositorio de Git. Git desconoce su existencia.

Seguimiento: Un archivo con seguimiento es aquel que Git está supervisando activamente. Puede estar en uno de los siguientes subestados:

Sin modificar: Se realiza un seguimiento del archivo, pero no se ha modificado desde la última confirmación.
Modificado: el archivo ha cambiado desde la última confirmación, pero estos cambios aún no están almacenados provisionalmente para la siguiente confirmación.
Staged: El archivo se ha modificado y los cambios se han agregado al área de preparación (también conocida como índice). Estos cambios están listos para confirmarse.
Comprometido: El archivo se encuentra en la base de datos del repositorio. Representa la versión confirmada más reciente del archivo.



Una solicitud de incorporación de cambios es un mecanismo que sirve para indicar que las confirmaciones de una rama están listas para combinarse en otra.

El miembro del equipo que envía el pull request pide a uno o varios revisores que comprueben el código y aprueben la fusión. Estos revisores podrán comentar los cambios, agregar otros o usar la solicitud de incorporación de cambios para realizar un análisis más exhaustivo.

Tipos de ramas en Git Flow
El flujo de Git usa varias ramas temporales y de larga duración:

master: siempre refleja el código listo para producción.
develop: contiene el trabajo de desarrollo más reciente para la próxima versión.
feature/*: se usa para crear nuevas funcionalidades; creado a partir de develop y se fusiona de nuevo cuando se complete.
release/*: prepara una nueva versión de producción desde develop; permite pruebas finales y correcciones de errores menores.
hotfix/*: se utiliza para aplicar revisiones urgentes para los problemas de producción; se bifurca a partir de master.
