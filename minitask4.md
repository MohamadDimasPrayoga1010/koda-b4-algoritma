# Flowchart bilangan genap dan ganjil

```mermaid
flowchart TB
START@{shape: circ, label: "Start"}
STOP@{shape: dbl-circ, label: "Stop"}

ANGKA@{shape: lean-r, label: "Angka"}
BIL2@{shape: rect, label: Bilangan dibagi 2}
BAGI2@{shape: diam, label: Bilangan % 2 = 0}

GENAP@{shape: rect, label: '"Genap"'}
GANJIL@{shape: rect, label: '"Ganjil"'}

START-->ANGKA
ANGKA-->BIL2
BIL2-->BAGI2
BAGI2 -- TRUE --> GENAP
BAGI2 -- FALSE --> GANJIL
GANJIL-->STOP
GENAP-->STOP
```
