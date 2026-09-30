# Recommandation

Résultats avec les hypothèses de départ (voir `hypotheses.md`). À recalculer dans le simulateur si elles changent.

| Scenarii | Gain net / an | ROI 3 ans | Retour | Valeur | Faisab. | Risque | Global | Décision |
|---|---|---|---|---|---|---|---|---|
| A Support | 34 470 € | 193 % | 6,1 mois | 96 | 73 | 60 | 73 | **Tester** |
| B Factures | 58 660 € | 131 % | 8,6 mois | 66 | 60 | 80 | 50 | **Creuser** |
| C Veille | 14 113 € | 142 % | 8,9 mois | 71 | 73 | 60 | 62 | **Creuser** |

## Lecture
- **A : tester.** Meilleur ROI, retour en 6 mois, risque juste sous le seuil. Piloter 4 semaines avec 3 agents, mesurer les minutes réellement gagnées et l'adoption.
- **B : creuser.** Le gain net le plus élevé, mais des données de faible qualité (2/5) et un risque de 80/100 (données sensibles, forte dépendance fournisseur). Auditer un échantillon de 200 factures avant de décider.
- **C : creuser.** Gain modeste et incertitude maximale (5/5). Le sponsor est faible (2/5) : confirmer le besoin auprès de la direction avant tout développement.

## Ce qui ferait changer la décision
- A passe en « creuser » si l'adoption tombe sous ~50 % ou si la sensibilité des données monte à 4.
- B passe en « tester » seulement si trois leviers jouent ensemble : mise en œuvre ramenée à ~30 jours, données à 4/5, et risque ≤ 60 (sensibilité 3, dépendance 2).
- C passe en « tester » si un sponsor s'engage (4/5) et que l'incertitude baisse à 3.
