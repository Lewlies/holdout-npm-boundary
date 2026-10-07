# holdout-npm-boundary

Repositorio sintético del conjunto de reserva (*hold-out*) del TFG *Análisis automatizado de vulnerabilidades en dependencias de software*. No contiene código, solo el manifiesto de dependencias.

No se usó para diseñar sca-gate. El ground truth (`ground_truth.yaml`) se escribió antes de ejecutar la herramienta sobre él.

| Dimensión | Paquete | Identificador |
|---|---|---|
| borde, lado vulnerable (7.4.5, corregido en 7.4.6) | ws | CVE-2021-32640 |
| borde, lado corregido (primera version sin CVE-2022-25883 en la rama 7.x) | semver 7.5.2 | CVE-2022-25883 |
