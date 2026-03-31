# Guide de Contribution — Kit du Fondateur Francophone

Merci de votre intérêt pour contribuer au **Kit du Fondateur Francophone** ! 🎉

Ce guide vous explique comment contribuer efficacement à ce projet communautaire.

---

## 📋 Table des Matières

- [Code de Conduite](#code-de-conduite)
- [Comment Contribuer](#comment-contribuer)
- [Types de Contributions](#types-de-contributions)
- [Processus de Pull Request](#processus-de-pull-request)
- [Standards de Qualité](#standards-de-qualité)
- [Directives de Style](#directives-de-style)

---

## Code de Conduite

Ce projet et toutes les personnes qui y participent sont soumis au [Code de Conduite](CODE_OF_CONDUCT.md). En participant, vous vous engagez à respecter ce code. Signalez tout comportement inacceptable.

---

## Comment Contribuer

### Fork & Clone

```bash
# 1. Forkez ce repository via l'interface GitHub

# 2. Clonez votre fork
git clone https://github.com/votre-username/founders-kit-fr.git

# 3. Créez une branche
git checkout -b ajout/nom-de-votre-ressource

# 4. Faites vos modifications

# 5. Committez
git add .
git commit -m "feat: ajouter [Nom Ressource] dans [Catégorie]"

# 6. Pushez
git push origin ajout/nom-de-votre-ressource

# 7. Ouvrez une Pull Request sur GitHub
```

---

## Types de Contributions

### ✅ Ce que nous acceptons

| Type | Description |
|------|-------------|
| 🆕 **Nouvelle ressource** | Outil, plateforme, livre ou article pertinent pour les fondateurs |
| 🔗 **Correction de lien** | Un lien qui ne fonctionne plus ou qui a changé d'URL |
| 📝 **Amélioration de description** | Clarifier ou enrichir la description d'une ressource existante |
| 🗂️ **Nouvelle catégorie** | Proposition d'une catégorie manquante avec au moins 3 ressources |
| 🌍 **Ressources francophones** | Outils, programmes, communautés spécifiques à la France ou l'Afrique francophone |
| 🐛 **Correction d'erreur** | Faute d'orthographe, de grammaire ou information incorrecte |

### ❌ Ce que nous n'acceptons pas

- Ressources promotionnelles ou publicitaires non objectives
- Outils sans version gratuite ou trial significatif (sauf exceptions justifiées)
- Doublons avec des ressources déjà listées
- Ressources non pertinentes pour les fondateurs de startups
- Liens d'affiliation non déclarés

---

## Processus de Pull Request

### Format du commit

Utilisez les préfixes conventionnels :

```
feat: ajouter [Nom] dans la section [Catégorie]
fix: corriger lien pour [Nom]
docs: améliorer description de [Nom]
refactor: réorganiser la section [Catégorie]
```

### Checklist avant soumission

Avant d'ouvrir votre PR, vérifiez :

- [ ] Le lien fonctionne et pointe vers la page principale de l'outil
- [ ] La ressource est dans la bonne catégorie
- [ ] La description est en français et concise (1-2 lignes maximum)
- [ ] Vous avez ajouté `✨` si c'est une nouveauté 2026
- [ ] Pas de doublon avec une ressource déjà existante
- [ ] Le formatage Markdown est correct

### Template de PR

```markdown
## Description
Brève description de ce que vous ajoutez/modifiez.

## Type de changement
- [ ] Nouvelle ressource
- [ ] Correction de lien
- [ ] Amélioration description
- [ ] Nouvelle catégorie

## Ressource ajoutée/modifiée
- **Nom** : 
- **URL** : 
- **Catégorie** : 
- **Raison de l'ajout** : 

## Checklist
- [ ] Lien fonctionnel testé
- [ ] Bonne catégorie
- [ ] Description en français
- [ ] Pas de doublon
```

---

## Standards de Qualité

### Pour les outils & plateformes

Une ressource doit remplir **au moins 3** de ces critères :

- ✅ Tier gratuit ou essai gratuit significatif
- ✅ Largement utilisée dans l'écosystème startup (1000+ utilisateurs)
- ✅ Maintenue activement (mise à jour dans les 12 derniers mois)
- ✅ Bonne réputation dans la communauté
- ✅ Valeur ajoutée unique vs les outils déjà listés
- ✅ Pertinente pour le marché francophone / africain

### Pour les ressources éducatives

- ✅ Auteur reconnu dans l'écosystème startup
- ✅ Contenu toujours pertinent et non obsolète
- ✅ Valeur actionnable pour les fondateurs

---

## Directives de Style

### Format d'une entrée

```markdown
- [Nom de l'outil](https://url.com/) ✨ — Description courte et précise en français. Information distinctive.
```

**Règles :**
- Le nom en Markdown link `[Nom](url)`
- `✨` pour les nouveautés 2026 uniquement
- Tiret long `—` avant la description
- Description en français, 1-2 lignes max
- Si startup française/africaine, mentionnez-le avec 🇫🇷 ou le pays

**Exemple :**
```markdown
- [Qonto](https://qonto.com/fr) ✨ — **Fintech française** 🇫🇷 — Néobanque N°1 pour startups et PME en Europe. IBAN FR, cartes virtuelles, comptabilité intégrée.
```

### Ordre dans les sections

Au sein d'une même section, les ressources sont organisées par :
1. Popularité / adoption (les plus utilisées en premier)
2. Les ressources francophones en priorité quand elles existent

---

## 🙋 Questions ?

Ouvrez une [Issue](https://github.com/votre-username/founders-kit-fr/issues) avec le label `question` et nous vous répondrons dans les plus brefs délais.

---

Merci de rendre cette ressource meilleure pour toute la communauté francophone ! 🚀
