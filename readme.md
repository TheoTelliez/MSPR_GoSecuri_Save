# MSPR GoSecuri - Sauvegarde des données

## CONTEXTE DU BESOIN – CAHIER DES CHARGES :

Le but de cette demande est de concevoir une solution Web permettant de consulter les fiches des agents et
des équipements en leur possession. Ce site constitué de pages statiques sera généré à partir des fichiers du
dépôt Git dont l’arborescence et le format des fichiers sont définis en annexe.
Ce site sera utilisé pour vérifier l’accès au local sécurisé.


Seuls les agents dont la fiche sera présente sur le site auront accès au local.
Ainsi, la réalisation de ce projet nécessite de concevoir et de développer une solution permettant l’utilisation
des scans et informations disponibles sur le dépôt git de sauvegarde.
En plus de l’identité, sur la fiche de l’agent s’affichera le matériel qu’il utilise durant la mission d’intervention en
cours.


Pour faciliter la maintenance par l’informaticien SysOps de l’entreprise, le choix de la solution minimisera les
solutions applicatives. Il se portera sur le développement en java d’applications console qui génèrent du html.
Elles seront construites et orchestrées par des pipelines Jenkins.
Quant au choix du système d’exploitation sur lequel fonctionnera l’application, il reste libre (Windows, Linux,
MacOs), ainsi que le matériel (Ordinateur portable, Raspberry, PC Fixe …).

## Références couleurs

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Noir | ![#000000](https://via.placeholder.com/10/000000?text=+) #000000 |
| Vert | ![#659224](https://via.placeholder.com/10/659224?text=+) #659224 |
| Bleu | ![#379EC1](https://via.placeholder.com/10/379EC1?text=+) #379EC1 |


## Contributeurs

- [@Théo TELLIEZ](https://github.com/TheoTelliez)
- [@Rémi DAVID](https://github.com/Upsulone)
- [@Loïc LAMAILLE](https://github.com/LoicLamailleEpsi)

