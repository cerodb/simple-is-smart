# Simple is Smart

Una skill para revisar planes, propuestas, cambios y flujos de trabajo con foco
en el objetivo real, la complejidad necesaria y el esfuerzo total.

## Uso

Dale al agente el material y el objetivo, y pedile:

> Usá simple-is-smart para revisar este plan: qué conservar, qué simplificar
> y cuál es el siguiente paso mínimo. El objetivo es [resultado esperado].

La revisión entrega un veredicto: **mantener**, **simplificar** o
**falta evidencia**. Cuando aporta, señala hasta tres recortes prioritarios y
una acción concreta para comprobar el resultado. Puede concluir que no hace
falta cambiar nada. Pedir una revisión no autoriza a aplicar sus propuestas.

## Archivos

- `SKILL.md`: instrucciones y descripción de la skill.
- `agents/openai.yaml`: metadatos de interfaz para Codex.

Para instalarla, colocá esta carpeta con el nombre `simple-is-smart` en el
directorio de skills admitido por tu agente. Consultá la documentación de tu
cliente para la ubicación y el procedimiento de carga.

## Estado

Experimental. Su aporte incremental frente al mismo agente sin la skill no
está demostrado de forma general. El criterio 80/20 orienta la priorización;
no promete porcentajes de ahorro.
