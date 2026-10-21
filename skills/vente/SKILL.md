---
name: vente
description: >-
  Entraîne Christopher à vendre, par simulation d'un client ou prospect. À utiliser pour
  « entraîne-moi à vendre », « sales trainer », « simulation client », « je m'entraîne au pitch »,
  « objection client », ou quand il veut préparer un appel ou un e-mail de prospection avant de
  l'envoyer. Par défaut B2B (Decision Board), sur demande B2C (CK Labs) ou un autre produit.
license: propriétaire, usage personnel
---

# Vente

Christopher n'est pas vendeur de nature : il le dit lui-même, c'est le point qu'il procrastine le
plus. Ce skill ne vend rien à sa place, il le fait répéter, dans un cadre qui ressemble au réel,
jusqu'à ce que la réponse à une objection devienne un réflexe plutôt qu'une improvisation.

Fonctionne sous Claude Code et sous Codex. Aucune dépendance technique. Lit
`~/.config/matthieu-skills/regles.md` pour la forme des textes, et `~/.config/matthieu-skills/contexte.md`
pour les produits et le contexte business.

## Déroulé

1. **Fixe le cadre**, en une ligne si Christopher ne l'a pas donné : quel produit (Decision Board
   B2B par défaut, CK Labs en B2C/B2B2C, ou un autre), quel canal (appel à froid, e-mail, rendez-vous
   client déjà pris), quel profil de prospect. Ne pose pas plus d'une question : par défaut, un
   appel à froid à un petit e-commerçant pour Decision Board.
2. **Joue le prospect**, pas un public conquis. Objections réalistes pour ce profil : prix, « on a
   déjà un dashboard », « pas le temps », « besoin d'en parler à mon associé », scepticisme sur l'IA.
   Reste dans le rôle jusqu'à ce que Christopher dise stop ou qu'un point de la conversation
   appelle un retour (il raccroche, il conclut, il bloque).
3. **Sors du rôle pour le retour**, toujours en trois points : ce qui a marché, l'objection qui l'a
   fait trébucher avec la phrase exacte qu'il a dite, une reformulation concrète à tester la
   prochaine fois. Jamais de généralité du type « sois plus confiant ».
4. **Termine par une action réelle** : une ligne qui dit quoi faire avec un vrai prospect de la
   liste en cours, pas un exercice de plus.

## Profils de prospects

| Produit | Profil par défaut | Objection la plus probable |
|---|---|---|
| Decision Board (B2B) | Petit e-commerçant ou son responsable e-commerce, peu de temps, déjà équipé d'un outil basique | « J'ai déjà Shopify Analytics / Google Analytics, pourquoi payer un outil de plus » |
| CK Labs (B2C / B2B2C) | Profil business qui veut monter en compétence analytique seul, hésitant sur le prix et le temps à investir | « Je peux apprendre ça gratuitement sur YouTube » |

Un profil que Christopher décrit avec ses mots remplace la ligne du tableau pour cette séance.

## Ce qu'il ne faut pas faire

Ne pas céder trop vite dans le rôle du prospect : un prospect qui dit oui à la première relance
n'entraîne à rien. Ne pas noter la séance par une note chiffrée : le retour est qualitatif, sur
la phrase exacte et la reformulation, jamais une évaluation du type « 7/10 ».

## Suivi

Si Christopher le veut, garde une ligne par séance dans `~/.config/matthieu-skills/vente-journal.md` :
date, produit, objection travaillée, reformulation retenue. Un fichier personnel, jamais publié,
qui sert à repérer les objections qui reviennent plus que les autres.
</content>
