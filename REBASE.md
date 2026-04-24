# Proceso de limpieza de commits

## Situación inicial
El historial contenía commits con mensajes poco claros:
- "cambios"
- "cosas"
- "arreglos"

## Acción realizada
Se utilizó el comando:

git rebase -i HEAD~3

## Decisiones tomadas
- Se usó "reword" para mejorar el mensaje principal
- Se usó "squash" para fusionar commits innecesarios

## Resultado
Se obtuvo un único commit con mensaje claro:
"Actualiza script.sh añadiendo varias líneas de prueba"
