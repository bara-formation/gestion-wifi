# Gestion WiFi

Application de gestion d'un réseau WiFi payant : codes à durée limitée,
suivi des clients connectés, recettes, et filtrage des appareils
directement dans la box internet.

Distribuée et maintenue par **Bara Formation** (Burkina Faso).

---

## À quoi sert ce dépôt

Uniquement à **distribuer les mises à jour** de l'application.

Le code source n'est pas hébergé ici. Vous ne trouverez dans les
[Releases](../../releases) que les paquets d'installation, destinés aux
applications déjà installées chez nos clients.

Ce dépôt n'accepte ni contributions ni signalements de bugs. Si vous êtes
client, contactez-nous directement (voir plus bas).

---

## Pour nos clients

### Vos mises à jour sont automatiques

Vous n'avez **rien à télécharger sur cette page**. Votre application vérifie
toute seule, une fois par jour, si une correction est disponible.

Ce qui se passe alors :

1. Elle télécharge la nouvelle version et vérifie qu'elle est authentique.
2. Un bandeau bleu **« MISE À JOUR PRÊTE »** s'affiche en haut de l'écran.
3. L'installation se fait au prochain démarrage de l'ordinateur — ou tout de
   suite si vous cliquez sur **« Installer et redémarrer »** dans l'onglet
   *Licence* (comptez une vingtaine de secondes).

**Le WiFi de vos clients n'est jamais coupé pendant l'opération.** Le filtrage
se fait dans la box, pas dans l'application.

Si une nouvelle version ne démarrait pas correctement, l'application revient
automatiquement à la précédente après trois essais. Vous n'êtes jamais bloqué,
et vos données ne sont jamais touchées.

### Si votre application ne se met pas à jour

Vérifiez l'adresse de mise à jour : onglet **Licence** → **Mises à jour** →
*Adresse de mise à jour*. Elle doit être exactement :

```
https://github.com/bara-formation/gestion-wifi/releases/latest/download/manifeste.json
```

Cette adresse ne change jamais, quelle que soit la version.

Un message d'erreur après un essai est le plus souvent une simple coupure
d'internet : l'application réessaiera d'elle-même le lendemain. Cela n'empêche
rien de fonctionner entre-temps.

### Votre licence

Votre clé est liée à **un seul ordinateur**. Pour l'activer ou la renouveler :

1. Ouvrez l'onglet **Licence**.
2. Recopiez le **numéro de votre ordinateur** (8 groupes, par exemple
   `3F7A-91C2-88E0-4B15`).
3. Envoyez-le nous.
4. Collez la clé reçue dans la case prévue, puis cliquez **Activer**.

Pour un abonnement, l'application vous prévient **7 jours avant l'échéance**,
puis tolère encore **7 jours** avant de suspendre la connexion de nouveaux
clients. Même suspendue, elle vous laisse toujours consulter vos codes, vos
clients et vos recettes : **rien n'est jamais effacé**.

Si vous changez d'ordinateur, demandez-nous une nouvelle clé — l'ancienne ne
fonctionnera pas sur la nouvelle machine.

---

## Authenticité des mises à jour

Chaque version publiée ici est **signée cryptographiquement**. L'application
refuse d'installer un paquet qui ne porte pas notre signature, même s'il est
téléchargé depuis cette adresse.

Concrètement : si quelqu'un parvenait à déposer un fichier à notre place, les
applications de nos clients le rejetteraient.

**Ne téléchargez jamais une mise à jour ailleurs que par l'application
elle-même.** Nous ne vous demanderons jamais d'installer un fichier reçu par
message ou par clé USB.

---

## Journal des versions

| Version | Date | Nouveautés |
|---------|------|------------|
| 2.4.0 | septembre 2026 | Nom de l'appareil sur les derniers paiements, et pastille « en ligne » |
| 2.3.3 | septembre 2026 | Retrait d'un rappel devenu inutile sur le tableau de bord |
| 2.3.2 | septembre 2026 | Coordonnées du fournisseur affichées dans l'application |
| 2.3.1 | septembre 2026 | Un œil permet de voir son mot de passe pendant la saisie |
| 2.3.0 | septembre 2026 | Accès à distance par réseau privé, et protection de l'écran de connexion |
| 2.2.0 | septembre 2026 | Réveil automatique de l'ordinateur : les forfaits terminés sont coupés même pendant votre absence |
| 2.1.1 | septembre 2026 | Correction : le nom imprime sur les tickets reprend celui de votre activite |
| 2.1.0 | septembre 2026 | Licences au mois et à l'année, rappel avant échéance, délai de tolérance, mise à jour automatique |
| 2.0 | septembre 2026 | Assistant de première configuration, sauvegarde et restauration, licences |

---

## Nous contacter

**Bara Formation** — Burkina Faso
WhatsApp : **+226 04 04 34 04**

Quand vous signalez un problème, indiquez-nous :

- le **numéro de version** (onglet *Licence* → *À propos*) ;
- ce que vous faisiez au moment du problème ;
- le message affiché à l'écran, si vous en avez un.

Ces trois informations nous font gagner beaucoup de temps.
