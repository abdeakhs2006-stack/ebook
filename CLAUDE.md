# CLAUDE.md — Contexte projet ebook & lifguido

> Ce fichier permet à Claude de reprendre le contexte complet à chaque nouvelle session.
> Dernière mise à jour : 20 mai 2026

---

## 👤 Propriétaire

- **Nom** : David Greenfield
- **Email** : assidir780@gmail.com
- **Blog principal** : lifbio.fr (WordPress + Rank Math SEO)

---

## 🌿 L'ÉCOSYSTÈME

```
lifbio.fr              → blog articles gratuits (SEO, trafic organique)
lifguido.com           → boutique produits digitaux payants (ebooks, guides PDF)
```

Les produits de lifguido.com sont directement inspirés des articles lifbio.fr.

---

## 🌐 LIFBIO.FR — Blog principal

### Identité visuelle
- **Logo** : "lifbio" en minuscules, avec une feuille verte poussant du "f"
- **Couleur principale** : Vert forêt profond (~#2D5A1B)
- **Fond** : Beige crème (#F5F0EB environ)
- **Accent** : Rose saumon (liens "Lire plus", boutons CTA)
- **Tagline** : "Bien vieillir au naturel"

### Catégories du blog
| Catégorie | Contenu |
|-----------|---------|
| Beauté | Soins peau senior, cheveux blancs, maquillage 60+ |
| Nutrition | Régimes bio, compléments, hydratation, petit-déjeuner |
| Bien-être | Rituels quotidiens, mémoire, vitamine D, yoga |
| Tech | Smartphone, tablette, liseuse, pilulier connecté, téléassistance |
| Épanouissement | Bénévolat, mémoire, développement personnel |

### Cible
- **Audience principale** : Seniors francophones 50-75 ans
- **Géographie** : France, Belgique, Suisse, Canada francophone
- **Approche** : Naturelle, bio, accessible, chaleureuse

### État technique
- WordPress + Elementor + Rank Math SEO
- ~35 articles publiés (30 existants + 5 beauté ajoutés)
- Blocage LiteSpeed Bot Challenge sur l'API REST WordPress (voir WORKFLOW-LIFBIO.md)

---

## 🛍️ LIFGUIDO.COM — Boutique produits digitaux

### Identité de marque
- **Nom** : lifguido
- **Domaine** : lifguido.com (disponible au 20/05/2026 — à enregistrer)
- **Logo** : "lifguido" en minuscules vert forêt, feuille verte sur le "f", fond beige crème
- **Tagline** : "vos guides bien-vieillir"
- **DNA visuel** : Sœur de lifbio — même couleurs, même feuille sur le f, même typographie

### Logo validé
Logo Canva approuvé le 20/05/2026 :
- Mot "lifguido" en minuscules, police serif élégante, vert forêt
- Feuille verte positionnée sur le "f"
- Tagline "vos guides bien-vieillir" en vert plus clair
- Fond beige crème
- Style identique à lifbio.fr

### Produits prévus
Chaque produit correspond à une catégorie du blog lifbio :
| Catégorie lifbio | Produit digital lifguido |
|-----------------|--------------------------|
| Tech | **Ebook "Mon smartphone & moi"** (v9B — prêt) |
| Beauté | Guide beauté naturelle senior (à créer) |
| Nutrition | Guide nutrition bien-vieillir (à créer) |
| Bien-être | Guide rituels bien-être (à créer) |
| Épanouissement | Guide épanouissement senior (à créer) |

---

## 📱 PRODUIT 1 — Ebook "Mon smartphone & moi"

### Infos produit
- **Titre complet** : Mon smartphone & moi — Le guide des seniors pour tout maîtriser
- **Édition** : Finale 2026
- **Version actuelle** : **v9B** (version recommandée)
- **Fichiers** : PDF + DOCX

### Versions
| Version | Date | Score audit | Statut |
|---------|------|-------------|--------|
| v6 | 26/04/2026 | 93/100 | Archivée |
| v7 | 27/04/2026 | 93/100 | Archivée |
| **v9B** | 20/05/2026 | **98/100** | ✅ **RECOMMANDÉE** |

### Contenu v9B
- 7 parties, **29 chapitres**, conclusion, **6 annexes**
- 200+ visuels/captures d'écran annotées
- **12 QR codes** tutoriels officiels (Apple, Google, DGFiP, Service-Public.fr)
- Header/footer professionnel avec pagination
- Chapitres 25-29 (nouveaux) : assistants vocaux, emails, MAJ système, mémoire pleine, achats en ligne
- Annexe 6 : index alphabétique complet
- Toutes issues Medium et Low de l'audit v6 résolues

### Tarification recommandée
| Canal | Prix |
|-------|------|
| Gumroad (PDF direct) | 12,99 € |
| Amazon KDP Kindle | 9,99 € |
| Amazon KDP Print | 19,99 € |
| Prix de lancement (-30j) | 9,99 € |
| Pack famille (2 licences) | 19,99 € |

### Cible marketing principale
Enfants 45-60 ans achetant pour leurs parents seniors

### Angles marketing prioritaires
1. Arnaques téléphoniques (meilleur taux de conversion)
2. Autonomie ("arrêtez de répondre à leurs appels du dimanche")
3. Services administratifs FR (FranceConnect, ameli, impôts — introuvable ailleurs)
4. Mise à jour 2026 (concurrents bloqués en 2023-2024)

---

## 📦 GITHUB — Structure des dépôts

| Dépôt | Branche de travail | Contenu |
|-------|-------------------|---------|
| abdeakhs2006-stack/ebook | `claude/push-v9b-release-dxCbD` | Ebook smartphone v9B |
| abdeakhs2006-stack/blog-lifbio | `claude/push-v9b-release-dxCbD` | Scripts et articles lifbio |
| abdeakhs2006-stack/SEO1 | `claude/push-v9b-release-dxCbD` | SEO tools |

### PR ouverte
- **ebook PR #1** : https://github.com/abdeakhs2006-stack/ebook/pull/1
  - Titre : "release: version v9B recommandée — Mon smartphone & moi 2026"
  - Statut : Draft, en attente de merge

---

## 🚀 PROCHAINES ÉTAPES PRIORITAIRES

### Immédiat
- [ ] Enregistrer `lifguido.com` (GoDaddy ou Namecheap, ~12€/an)
- [ ] Sauvegarder le logo lifguido dans Canva
- [ ] Uploader le PDF v9B sur Gumroad à 9,99 € (lancement)
- [ ] Merger la PR #1 sur GitHub

### Court terme (J+7 à J+14)
- [ ] Créer compte Amazon KDP → soumettre ebook smartphone
- [ ] Créer la page de vente lifguido.com (Systeme.io ou Carrd)
- [ ] Lancer 3 posts Facebook seniors avec angle "arnaques"

### Moyen terme (Mois 2-3)
- [ ] Créer le prochain ebook (Guide beauté naturelle senior)
- [ ] Séquence email 5 messages post-achat
- [ ] Soumettre sur Kobo/Fnac
- [ ] Lier lifbio.fr → lifguido.com (bannière + liens internes)

---

## 📝 NOTES IMPORTANTES POUR CLAUDE

1. **Ne jamais changer la charte graphique** : vert forêt + beige crème + feuille sur le "f" — c'est l'ADN de toute la marque
2. **lifbio = contenu gratuit**, **lifguido = produits payants** — ne pas mélanger
3. **Toujours pousser sur** `claude/push-v9b-release-dxCbD` pour ce dépôt
4. **Le PDF v9B** est sur l'ordinateur de David : `C:/Users/hp/Downloads/Mon_smartphone_et_moi_RECOMMANDE_v9B.pdf`
5. **lifguido.com** : disponible au 20/05/2026, à enregistrer en urgence
6. **Audience** : seniors 50-75 ans francophones, ton chaleureux, vouvoiement, pas de jargon technique
