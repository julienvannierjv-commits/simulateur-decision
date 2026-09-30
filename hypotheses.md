# Hypothèses

Toutes modifiables en direct dans le simulateur. Valeurs de départ = `scenarios.json`. **Ce sont des hypothèses de cadrage, à valider avec le terrain avant décision.**

## Globales
| Hypothèse | Valeur | Justification |
|---|---|---|
| Semaines travaillées / an | 46 | Congés et jours fériés déduits |
| Horizon d'analyse | 3 ans | Durée usuelle d'amortissement d'un outil |
| ROI cible | 200 % | ROI à 3 ans qui vaut 100/100 en valeur |
| Poids valeur / faisabilité / risque | 40 / 30 / 30 | La valeur prime, sans masquer le risque |
| Seuils de décision | stopper < 40, tester ≥ 65 | Voir `regles_calcul.md` |

## Par scénario
| | A Support | B Factures | C Veille |
|---|---|---|---|
| Utilisateurs | 12 | 4 | 3 |
| Usages / semaine / utilisateur | 60 | 150 | 5 |
| Minutes gagnées par usage | 2,5 | 5 | 45 |
| Taux horaire chargé (€) | 45 | 38 | 70 |
| Adoption réelle | 70 % | 90 % | 50 % |
| Jours de mise en œuvre × TJM 700 € | 25 | 60 | 15 |
| Licence + exploitation / an (€) | 9 000 | 20 000 | 4 000 |
| Qualité des données (1-5, 5 = bonne) | 3 | 2 | 4 |
| Maturité technique (1-5, 5 = simple) | 4 | 3 | 5 |
| Sponsor / appui métier (1-5) | 4 | 4 | 2 |
| Sensibilité des données (1-5, 5 = critique) | 3 | 4 | 2 |
| Incertitude des estimations (1-5) | 3 | 4 | 5 |
| Dépendance fournisseur (1-5) | 3 | 4 | 2 |

## Limites connues
- Le temps gagné est supposé converti en valeur au taux horaire : ce n'est vrai que s'il est réaffecté à du travail utile.
- Aucun gain de qualité, de délai client ou de revenu n'est compté.
- Les gains sont constants sur l'horizon (pas de montée en charge).
