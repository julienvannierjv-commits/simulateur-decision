# Règles de calcul

Chaque score est reproductible à la main. Le simulateur affiche ces formules avec les valeurs du scénario.

## 1. Valeur
- Gain annuel = utilisateurs × usages/sem × semaines × (minutes ÷ 60) × taux horaire × adoption
- Coût initial = jours × TJM
- Coût récurrent = licence + exploitation (par an)
- Gain net annuel = gain annuel − coût récurrent
- Coût total sur l'horizon = initial + récurrent × horizon
- **ROI** = (gain annuel × horizon − coût total) ÷ coût total
- **Délai de retour (mois)** = coût initial ÷ (gain net annuel ÷ 12) ; infini si gain net ≤ 0
- **Score valeur** = min(100 ; max(0 ; ROI ÷ ROI cible × 100))

## 2. Faisabilité
Score = (données + technique + sponsor) ÷ 15 × 100. Chaque critère va de 1 (défavorable) à 5 (favorable).

## 3. Risque
Score risque = (sensibilité + incertitude + dépendance) ÷ 15 × 100. Plus il est haut, plus le risque est élevé.

## 4. Score global
Global = (P_v × Valeur + P_f × Faisabilité + P_r × (100 − Risque)) ÷ (P_v + P_f + P_r)

## 5. Recommandation
Appliquée dans cet ordre, la première règle vraie l'emporte.
1. **Stopper** si ROI ≤ 0, ou délai de retour > 36 mois, ou global < 40.
2. **Tester** si global ≥ 65 **et** faisabilité ≥ 55 **et** risque ≤ 60.
3. **Creuser** sinon (potentiel réel, mais incertitudes à lever avant d'engager).
