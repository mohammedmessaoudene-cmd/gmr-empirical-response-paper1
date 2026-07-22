# ORGA-OS / SOCU V19 — External Closure Only

V19 ne crée pas un nouveau simulateur. Elle ferme les gates TLC et QEMU/QTest du
mécanisme AERA : perception ≠ attestation ≠ autorisation, révocation atomique,
revalidation au commit, résistance au replay, reset, hot-swap, IRQ perdue et MMIO
invalide.

## Exécution locale avec dépendances disponibles

```bash
TLA2TOOLS_JAR=/path/to/tla2tools.jar ./formal/run_tlc_gate_v19.sh
QEMU_SRC=/path/to/qemu-v11.0.2 ./qemu/run_qemu_gate_v19.sh
```

La campagne de référence est la matrice GitHub Actions Ubuntu 22.04/24.04. Le
passage FPGA reste interdit tant que toutes les gates, dont une reproduction
humaine indépendante, ne sont pas fermées.
