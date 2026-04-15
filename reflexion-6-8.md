## Reflexión

1.
- --soft: deshace commit pero mantiene staging
- mixed: deshace commit y quita staging
- --hard: borra todo

2.
git reset cambia el historial, por eso es peligroso en repos compartidos.
git revert es más seguro porque crea un commit nuevo.

3.
- soft: corregir último commit
- mixed: reorganizar cambios
- hard: borrar cambios en pruebas
