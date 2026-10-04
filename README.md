# NEGDRUGS — installations et mises à jour / installers and updates

## Français

Ce dépôt public contient les installateurs Windows signés, leurs signatures et
les consignes de livraison. Le code source, le suivi du travail, les dossiers
hospitaliers et les clés privées restent hors de ce dépôt.

La livraison actuelle est **[NEGDRUGS 0.4.3](https://github.com/azempain/Negdrugs-releases/releases/tag/v0.4.3)**,
autorisée par le propriétaire avec une **dérogation limitée à cette version**.
Mme Neolla coordonne l'installation sur les postes gérés. Les exercices exacts
de mise à niveau/récupération, la confiance de chaque poste, la garde des clés hors
ordinateur, la Phase 1 élargie, les accords financiers/opérationnels et la décision
de sécurité #314 restent non vérifiés. L'approbation est distincte des résultats
des contrôles ; voir les fichiers `owner-exception.json` et `release-evidence.json`.

Téléchargez la même famille d'installateur que celle déjà installée : **MSI (.msi)**
ou **NSIS (.exe)**. Vérifiez SHA-256 et la signature **Negdrugs HMS Internal**.
Ce certificat est autosigné et exige une confiance délibérée sur les postes gérés.
Conservez le profil Windows, les données et une sauvegarde chiffrée complète.

La première mise à niveau manuelle ajoute le panneau facultatif. Aucun compte
GitHub n'est nécessaire. La recherche manuelle reste disponible avant connexion ;
les recherches automatiques, si activées, ont lieu au démarrage et toutes les six
heures. Une recherche réussie en 0.4.3 sans version plus récente affiche en vert
**« Vous utilisez la dernière version. »**. Une version plus récente affiche
l'icône bleue : choisissez Télécharger la mise à jour, enregistrez le travail,
puis Redémarrer et mettre à jour. Un échec ne confirme jamais la dernière version.
Les signatures et la récupération intégrée restent obligatoires ; aucun
redémarrage forcé. Les parcours hospitaliers restent hors connexion.

[Installation FR](https://negdrugs-hms-docs.vercel.app/docs/fr/app-guide/administration) ·
[Avancement FR](https://negdrugs-hms-docs.vercel.app/docs/fr/roadmap/project-progress).

## English

This public repository holds signed Windows installers, signatures and delivery
instructions. Source, work tracking, hospital records and private keys stay out
of this repository.

The current delivery is **[NEGDRUGS 0.4.3](https://github.com/azempain/Negdrugs-releases/releases/tag/v0.4.3)**,
authorized by the owner under a **one-release exception**. Mme Neolla coordinates
managed-PC installation. Exact upgrade/recovery drills, per-machine trust,
off-device key custody, broader Phase 1, finance/operational sign-off and #314
security disposition remain unverified. Approval is separate from test results;
see `owner-exception.json` and `release-evidence.json` in the release.

Download the existing installer family: **MSI (.msi)** or **NSIS (.exe)**. Verify
SHA-256 and the **Negdrugs HMS Internal** signature. This certificate is self-signed
and requires deliberate trust enrollment on managed PCs. Preserve the Windows
profile, data and a complete encrypted backup.

The first manual upgrade adds the optional updater. No GitHub account is needed.
Manual checks are available before sign-in; enabled automatic checks run at launch
and every six hours. A successful 0.4.3 check with no newer release shows a green
**“You're using the latest version.”** notice. A newer release shows the blue icon:
choose Download update, save work, then Restart and update. A failed check never
confirms the latest version. Signature checks and runtime recovery stay mandatory;
no forced restart. Hospital workflows remain offline.

[Installation EN](https://negdrugs-hms-docs.vercel.app/docs/en/app-guide/administration) ·
[Progress EN](https://negdrugs-hms-docs.vercel.app/docs/en/roadmap/project-progress).

The preceding 0.4.1 controlled draft is preserved and visible only to maintainers
with repository write access. Temporary draft links can return 404 or change.
Use the published 0.4.3 link above for staff delivery.

La version publiée 0.4.2 reste disponible. / Published 0.4.2 remains available.
