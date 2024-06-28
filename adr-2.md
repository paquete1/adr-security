# ADR 1 Unsafe Consumption of APIs


## Context

Se tienen que poner medidas de seguridad que garanticen el correcto funcionamiento de la API, evitando usos excesivo y ataques intencionados de ciberdelincuente.

## Decision

La API debe ser publicada mediante protocolo https.

Limitar el acceso a la API mediante Autentificación

Dar permisos personalizados a cada usuario Autentificado para que solo puedan hacer uso de los que le hayamos autorizado.

Limitar la cantidad de llamadas que se puede hacer a la API.

Poner validación en los inputs para que se cumplan los requisitos que necesita la API para el correcto funcionamiento. 

En caso que la API haga llamada a otra/s API´s poner timeout a dichas llamadas para evitando que se quede colgada nuestra API.


## Status

[Indicate the current status of the decision, such as "proposed", "accepted", "rejected", "superseded", or "obsolete".]

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
