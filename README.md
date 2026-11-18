# Audit logiciel du site e-commerce Foorshop

Projet réalisé dans le cadre du module **Génie Logiciel** (Ingénieur 3ème année, Semestre 2, année universitaire 2024/2025) à l'Université Mouloud Mammeri de Tizi-Ouzou, Faculté de GEI, Département d'Informatique.

> Projet à but pédagogique. Les constats reposent sur une analyse visuelle et technique du site en mars 2025 (navigateur, outils de développement, GTmetrix).

## Site audité
[Foorshop](https://foorshop.com/) : plateforme algérienne de commerce électronique, créée en 2016.

## Objectif
Évaluer le site selon plusieurs axes, relever les points forts et les points faibles, puis proposer des solutions concrètes.

## Axes d'audit
- **Ergonomie** : navigation, hiérarchie visuelle, lisibilité, alignements, espacement
- **SEO et référencement** : URLs, balises H1/H2, attributs `alt`, title et meta description, maillage interne
- **Accessibilité** : balises ARIA, contrastes, textes alternatifs, affichage mobile
- **Contenu** : organisation, textes, appels à l'action, cohérence du design
- **Fonctionnalités** : panier, formulaires, fenêtres modales, liens morts
- **Sécurité** : validation des champs, données sensibles, sessions, HTTPS, paiement
- **Conformité réglementaire** : mentions légales, CGV, politique de confidentialité, RGPD
- **Présence en ligne et e-réputation** : réseaux sociaux, avis clients, influenceurs

## Outils utilisés
- Outils de développement du navigateur Chrome (DevTools)
- GTmetrix (analyse de performance)
- Analyse manuelle du HTML et du CSS

## Principaux constats

**Points faibles**
- Performance moyenne : note **D** sur GTmetrix (performance 47 %, LCP 3,1 s)
- Bouton « Postulez maintenant » mal libellé dans la fenêtre d'ajout au panier
- Pas de validation stricte des champs du formulaire (numéro de téléphone)
- Absence de lien vers les mentions légales et incohérence entre « Foorshop » et « Hayla Market » dans le copyright
- Page « Retours et échanges » en erreur 404, liens morts, aucun avis clients
- Paiement uniquement à la livraison, pas de paiement en ligne sécurisé
- Texte « Lorem Ipsum » resté dans la section d'abonnement
- Mélange d'affichage RTL/LTR sur du texte français
- Comptes Instagram et Facebook peu actifs depuis 2024

**Points forts**
- HTTPS activé
- Filtres, tris et catégories bien présents
- Prix et promotions clairement affichés en DZD
- Coordonnées de contact et adresse physique visibles
- Site bilingue (français et arabe), compatible multi-navigateurs
- Forte communauté Instagram (environ 82 000 abonnés)

## Recommandations principales
1. Corriger les libellés et le contraste des boutons et des textes
2. Ajouter des validations de formulaire avec messages d'erreur clairs
3. Optimiser les images (WebP, lazy loading), le cache et les scripts
4. Ajouter les mentions légales, les CGV et une page de retours complète
5. Mettre en place les avis clients et un paiement en ligne sécurisé
6. Améliorer le SEO (balises Hn, alt, title, meta description, URLs courtes)
7. Rendre le site responsive et accessible (ARIA, tailles tactiles)
8. Relancer l'activité sur les réseaux sociaux

## Rapport complet
Le rapport détaillé (80 pages avec captures d'écran) est disponible dans ce dépôt : [projetGLfinal (2).pdf](<projetGLfinal (2).pdf>)

## Auteurs
- HOCINE Zahia
- LOUNIS Tassadit
