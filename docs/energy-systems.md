# Vol.05 — Systèmes Énergétiques
## Niveau A — Information Publique

---

## 1. Doctrine Énergétique

CORES opère sous une hiérarchie énergétique à quatre paliers :

| Palier | Source | Rôle | Phase |
|---|---|---|---|
| 1 - Primaire | Fission nucléaire | 100% de la demande opérationnelle | Toutes |
| 2 - Survie | Solaire PV + batteries | 50% backup si nucléaire échoue | Toutes |
| 3 - Aspirationnel | Géothermie profonde | Baseload long terme si site permet | R&D Phase 2+ |
| 4 - Exclu | Combustibles fossiles | Non applicable sur Mars | Jamais |

Le nucléaire est primaire car c'est la seule technologie démontrée capable de fournir une puissance continue et dense sur Mars, indépendamment des conditions de surface.

---

## 2. NASA Kilopower / KRUSTY

L'expérience KRUSTY (mars 2018, Nevada) a validé l'architecture fission heat-pipe :

| Paramètre | Valeur |
|---|---|
| Test pleine puissance | 28 heures consécutives |
| Puissance thermique | 5.0 kWt |
| Combustible | Alliage U-Mo (HEU) |
| Transport thermique | Heat pipes sodium (passif) |
| Conversion | Moteurs Stirling à piston libre |
| Efficacité | ~25% thermique-électrique |
| Coût programme | ~20M$ total |

---

## 3. NASA Fission Surface Power (FSP)

En août 2025, NASA a relevé le minimum de 40 kWe à **100 kWe** :

| Paramètre | Cible 2025 |
|---|---|
| Puissance électrique minimum | 100 kWe |
| Combustible | HALEU |
| Conversion préférée | Cycle Brayton fermé |
| Durée de vie | 10 ans minimum |

---

## 4. Solaire = Survie Uniquement

Le solaire sert exclusivement de couche de backup de survie :

| Paramètre | Mars | Terre |
|---|---|---|
| Irradiance moyenne | 590 W/m² | 1,361 W/m² |
| Ratio Mars/Terre | 43% | 100% |
| Réduction tempête poussière | Jusqu'à 99% | N/A |
| Fréquence tempête globale | Tous les 3-4 ans Mars | N/A |

---

## 5. Philosophie de Redondance

Principe : **aucun point de défaillance unique** dans toute l'infrastructure énergétique.

- Redondance de source : multiples sources de paliers différents
- Redondance de distribution : topologie de grille segmentée
- Hiérarchie de délestage : P1 (sécurité vie) jamais délesté → P4 (optimisation) délesté en premier

---

*Source : CORES RDI Version A, Vol.05 — Avril 2026*
