#Políticas de acceso a usuarios

Roles principales:

1- Líder de proyecto
* Puede hacer 'push' directo a la rama 'main'
* Tiene permisos de administrador del repositorio y la página/proyecto
* Revisa y aprueba los Pull Requests

2- Desarrollador
* Crea ramas a partir de una rama 'develop'
* Debe crear Pull Requests para incorporar cambios
* No tiene permiso de 'push' directo a ramas protegidas

3- Colaborador externo
* Solo puede trabajar en su propio fork del repositorio
* Debe hacer Pull Requests para proponer cambios
* Sus cambios deben ser revisados y aprobados por un desarrollador o líder
