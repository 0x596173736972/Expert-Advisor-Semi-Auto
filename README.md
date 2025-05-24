# EA - Robot de Trading Semi-Automatisé pour MetaTrader 5

Un Expert Advisor (EA) MQL5 avancé avec gestion des risques, entrées basées sur VWAP, et stratégie de positionnement par couches.

## 📌 Fonctionnalités
- **Entrées personnalisables** : VWAP, niveaux de prix prédéfinis, ou combinaison
- **Gestion des risques** : Stop-Loss, Take-Profit, risque ajustable par trade
- **Layering dynamique** : Ajout de positions en fonction de l'évolution du marché
- **Contrôles quotidiens** : Limite de trades, objectif de profit journalier
- **Mode Debug** : Journalisation détaillée pour le débogage

## ⚙️ Paramètres d'Entrée
| Catégorie | Paramètre | Description |
|-----------|-----------|-------------|
| Général | `MagicID` | Identifiant unique pour les trades |
| Risque | `RiskPercentInitial` | Risque initial par trade (%) |
| Entrée | `ModeEntree` | Stratégie d'entrée (VWAP/Niveau/Combiné) |
| Limites | `MaxPositionsTotal` | Nombre maximal de positions simultanées |

## 📸 Capture d'écran
![Dashboard](Docs/Screenshot.png)

## 🛠 Installation
1. Téléchargez le fichier `EA.mq5`
2. Copiez-le dans `MetaTrader 5/MQL5/Experts`
3. Compilez-le dans MetaEditor (F7)
4. Attachez-le à un graphique dans MT5

## ❗ Avertissement
- Testez en backtest avant usage réel
- Ajustez les paramètres selon votre tolérance au risque
- Ne garantit pas des profits

## 🤝 Contribution
Les contributions sont bienvenues ! Ouvrez une *Issue* pour :
- Signaler un bug
- Proposer une amélioration
