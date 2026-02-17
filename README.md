# Politique de confidentialité — TransMemo

**Dernière mise à jour : 17 février 2026**

## Éditeur

TransMemo est développée par l'association **Chrysalide Lyon**.
Contact : duxmuxxy.dev@proton.me

## Objet de l'application

TransMemo est un outil de suivi personnel permettant de planifier des rappels de prise de traitement, de suivre son stock de médicaments et de noter son bien-être au quotidien. TransMemo n'est pas un dispositif médical et ne fournit aucun conseil médical.

## Données collectées

### Données saisies par l'utilisateur

L'ensemble des données saisies dans l'application est **stocké exclusivement sur l'appareil de l'utilisateur**, dans une base de données locale. Ces données comprennent :

- Noms et paramètres des traitements (produits, dosages, intervalles de prise)
- Historique des prises effectuées
- Informations sur les contenants (stock, dates de péremption)
- Notes de bien-être et notes quotidiennes
- Préférences de l'application (thème, paramètres de notifications)

**Aucune de ces données n'est transmise à un serveur distant.** Elles ne quittent l'appareil que si l'utilisateur utilise volontairement la fonction d'export de base de données.

### Données collectées automatiquement

L'application intègre **Firebase Crashlytics** et **Firebase Analytics** (Google) pour :

- **Crashlytics** : collecter automatiquement des rapports d'erreur en cas de plantage de l'application. Ces rapports contiennent des informations techniques (modèle d'appareil, version du système d'exploitation, trace d'erreur). Ils ne contiennent aucune donnée de santé ni donnée personnelle saisie dans l'application.
- **Analytics** : collecter des données d'utilisation anonymes (écrans consultés, fréquence d'utilisation, pays). Ces données sont utilisées uniquement pour améliorer l'application.

Ces données sont traitées par Google conformément à la [politique de confidentialité de Google](https://policies.google.com/privacy).

### Données non collectées

TransMemo **ne collecte pas** :

- Nom, adresse email ou toute autre information d'identité
- Données de localisation précise
- Contacts, photos ou fichiers présents sur l'appareil
- Données biométriques (l'authentification biométrique est gérée par le système Android ; l'application ne stocke ni n'accède aux empreintes digitales)

## Compte utilisateur

TransMemo **ne nécessite aucun compte utilisateur** et aucune inscription.

## Partage de données

Les données saisies par l'utilisateur ne sont partagées avec aucun tiers.

Seules les données techniques collectées par Firebase Crashlytics et Firebase Analytics sont transmises à Google dans le cadre du fonctionnement de ces services.

## Stockage et sécurité

- Les données sont stockées localement sur l'appareil dans une base de données Room (SQLite) et un DataStore de préférences.
- L'utilisateur peut protéger l'accès à l'application par authentification biométrique (empreinte digitale, code PIN ou schéma du système).
- L'utilisateur peut activer un mode discret qui modifie l'icône et le nom de l'application sur l'écran d'accueil.

## Export et import de données

L'utilisateur peut exporter l'intégralité de sa base de données sous forme de fichier `.db` et la réimporter ultérieurement. Cette opération est entièrement manuelle et locale. L'utilisateur est responsable du stockage et de la sécurité du fichier exporté.

## Suppression des données

L'utilisateur peut supprimer ses données à tout moment en :

- Supprimant les produits, prises ou notes individuellement dans l'application
- Vidant les données de l'application depuis les paramètres Android
- Désinstallant l'application

La désinstallation supprime définitivement toutes les données locales.

## Autorisations utilisées

| Autorisation | Utilisation |
|---|---|
| Notifications | Envoyer des rappels de prise, alertes de stock et de péremption |
| Alarmes exactes | Déclencher les rappels de prise à l'heure précise configurée |
| Biométrie | Protéger l'accès à l'application (optionnel) |
| Démarrage automatique | Reprogrammer les alarmes après un redémarrage de l'appareil |

## Mineurs

TransMemo n'est pas destinée aux enfants de moins de 13 ans et ne collecte pas sciemment de données auprès de mineurs.

## Modifications

Cette politique de confidentialité peut être mise à jour. La date de dernière mise à jour est indiquée en haut du document. Les modifications prennent effet dès leur publication.

## Contact

Pour toute question relative à cette politique de confidentialité, vous pouvez contacter l'association Chrysalide Lyon à l'adresse suivante : duxmuxxy.dev@proton.me
