# odoo19-addons-vendor

## Objet

Ce répertoire accueille les **addons tiers non OCA** nécessaires au sandbox
Odoo local.

Il complète :

- [odoo19-addons-dorevia](/Users/doreviateam/dorevia-saas/odoo19-addons-dorevia) pour les modules Dorevia ;
- [odoo19-addons-oca](/Users/doreviateam/dorevia-saas/odoo19-addons-oca) pour les modules OCA retenus.

## Règle

On ne place ici que des modules externes utiles au sandbox local, mais qui ne
relèvent ni :

- du périmètre Dorevia reconstruit ;
- ni d’un module OCA maintenu dans `odoo19-addons-oca/`.

## Contenu actuel

- `base_account_budget`
- `base_accounting_kit`

## Note importante

`base_accounting_kit` n’est pas un module OCA dans notre environnement courant.
Le manifest observé le rattache à **Cybrosys**.

Il est donc volontairement rangé ici, avec sa dépendance
`base_account_budget`, pour garder une frontière propre dans le workspace.
