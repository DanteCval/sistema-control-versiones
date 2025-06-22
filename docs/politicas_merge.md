# Políticas de combinación de ramas (merge)

Reglas para la combinación de ramas:

* Permitido el uso de **merge commit** para mantener el historial de cambios.
* El uso de **squash merge** está permitido para Pull Requests pequeños.
* **Rebase merge** no está permitido para evitar conflictos de historial.

## Condiciones previas al merge
* El código debe pasar todas las pruebas automáticas (CI).
* Debe de haber al menos 1 revisión/aprobación antes del merge.
* Todo cambio debe de contener comentarios en el pull Request.
* Debe estar actualizado con la rama 'develop' antes de hacer merge.
