# Pré-enregistrement V19

- Objet : fermeture externe d'AERA V18, sans nouveau benchmark favorable.
- TLC : v1.8.0, SHA-1 officiel `ae09269f0f74b9a7f69ac8b1e79f1514328082c6`.
- QEMU : tag `v11.0.2`, commit `e545d8bb9d63e9dd61542b88463183314cff9482`.
- Runners : Ubuntu 22.04 et Ubuntu 24.04.
- TLC fixe et rotation : succès obligatoire.
- TLC mutant : contre-exemple d'invariant obligatoire.
- AERA QTest : six tests réussis sur les deux runners.
- IOMMU RISC-V QTest : succès sur les deux runners.
- Une reproduction externe humaine reste distincte et non satisfaite par cette CI.
- Un seul échec maintient le NO-GO FPGA.
