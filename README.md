# NEGDRUGS — livraison Windows / Windows delivery

Ce dépôt public contient uniquement les programmes signés, leurs signatures et
les consignes de livraison. Le code de l’application reste privé ; aucun dossier
patient, secret ni matériel privé de signature n’est publié ici.

## Candidate 0.4.1 — brouillon contrôlé

La candidate signée **0.4.1** reste un **brouillon contrôlé**, sans autorisation
d’installation clinique. Ouvrez la [page Releases](https://github.com/azempain/Negdrugs-releases/releases)
après connexion avec les droits d’écriture pour la consulter. Les visiteurs
déconnectés ne voient pas le brouillon ; un lien direct peut retourner 404.
Cette page permanente reste utilisable lorsque les liens temporaires du brouillon changent.

La révision propre de l’application est `f379e795654b408b675a7c0148dfb0031d24b9e1`.
La vérification locale a réussi 1 785 tests de bureau, 43 tests API et la validation
de 130 documents. Windows/WebView2 a réussi 86/86 contrôles, avec 272 captures
natives FR/EN, clair/sombre, responsive et zoom réel de 200 %. Chaque ligne
présente au plus une action principale et Plus. Les programmes MSI/NSIS et les
signatures de mise à jour sont vérifiés ; ces résultats ne remplacent pas un
essai réel des programmes d’installation.

[Avancement FR](https://negdrugs-hms-docs.vercel.app/docs/fr/roadmap/project-progress) ·
[Guide d’installation FR](https://negdrugs-hms-docs.vercel.app/docs/fr/app-guide/administration).

Mme Neolla coordonne l’inventaire et l’acceptation. Mise à niveau/récupération
avec les programmes exacts, confiance de l’éditeur interne sur chaque poste,
garde des clés hors ordinateur, Phase 1 élargie et acceptations financière et
opérationnelle restent ouvertes. Une alerte haute `braces@3.0.3` concerne les
outils de développement de la documentation ; l’audit de production ne trouve
aucune vulnérabilité. Aucun correctif publié n’était disponible au point du
3 octobre ; la décision de sécurité reste ouverte dans le suivi privé #314.
Aucun flux stable `latest.json` ni release clinique n’est publié.

## English

This public repository holds signed installers, signatures and delivery guidance
only. Application source remains private; no patient records, credentials or
private signing material are published here.

Signed candidate **0.4.1** remains a **controlled draft**, without clinical
installation approval. Open the [Releases page](https://github.com/azempain/Negdrugs-releases/releases)
after signing in with repository write access. Signed-out visitors cannot see
the draft; direct draft links may return 404 and temporary links can change.

Clean application source: `f379e795654b408b675a7c0148dfb0031d24b9e1`.
Local verification passed 1,785 desktop tests, 43 API tests and 130 documents.
Windows/WebView2 passed 86/86 checks with 272 EN/FR native captures covering
themes, responsive widths and actual 200% zoom. Rows show at most one primary
action plus More. MSI/NSIS publisher and updater signatures are verified;
these results do not replace actual installer drills.

[Progress EN](https://negdrugs-hms-docs.vercel.app/docs/en/roadmap/project-progress) ·
[Installation guide EN](https://negdrugs-hms-docs.vercel.app/docs/en/app-guide/administration).

Mme Neolla coordinates inventory and acceptance. Exact installer upgrade/recovery,
per-machine internal publisher trust, off-device signing custody, broader Phase 1
and finance/operational approval remain open. One high `braces@3.0.3` advisory
affects documentation development tooling; the production-only audit is clear.
No patched release was published at the October 3 checkpoint; security disposition
remains open in private tracker #314. No stable `latest.json` or clinical release
is published.

## Managed upgrade / Mise à niveau gérée

Windows 10/11 x64 only. Preserve the installed MSI/NSIS family, Windows profile
and data directories. Keep a complete encrypted off-device backup and verify
recovery on an authorized synthetic copy before clinic deployment. Deliberately
verify internal publisher trust on each managed target; the certificate is
self-signed. Existing machines need the first manual upgrade to gain the updater.
Hospital workflows remain offline. Optional signed updates require separate
download and restart actions, including before sign-in. Current receipts remain in use.

Windows 10/11 x64 uniquement. Conservez famille MSI/NSIS, profil et dossiers de
données. Gardez une sauvegarde chiffrée complète hors ordinateur et vérifiez sa
récupération sur une copie synthétique autorisée avant déploiement clinique.
Vérifiez délibérément la confiance de l’éditeur interne sur chaque poste ; son
certificat est autosigné. La première mise à niveau manuelle apporte le panneau
facultatif. Les parcours hospitaliers restent hors connexion. Téléchargement et
redémarrage restent distincts, même avant connexion. Les reçus actuels sont conservés.
