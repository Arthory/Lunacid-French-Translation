[README-EN.txt](https://github.com/user-attachments/files/34269167/README-EN.txt)
LUNACID — UNOFFICIAL FRENCH TRANSLATION
Patch version: 1.0-BETA — 31 October 2026

REQUIREMENTS
You must own Lunacid. Supports the verified Windows 2.2.0 original files only.
The installer checks exact SHA-256 hashes, not just a displayed version number.
Uses Windows PowerShell 5.1 and .NET supplied with Windows. No Python, Node.js,
mod loader, external binary, or additional download is required.

INSTALLATION
1. Close Lunacid.
2. In Steam, right-click Lunacid > Manage > Browse local files.
3. Extract the ENTIRE ZIP there. Installer-FR.bat and Patch-FR must be beside
   LUNACID.exe. Do not run the BAT from inside the archive.
4. Double-click Installer-FR.bat and wait for the SUCCES message.
5. Launch the game normally. Keep English selected in the language settings.

Both English files are backed up before replacement. French files are rebuilt
locally and verified against the tested translation. Only these files change:
  LUNACID_Data\resources.assets
  LUNACID_Data\Resources\TXT\ENG\COMM.txt
Keep the Lunacid-FR-Sauvegardes folder. Progress/save-game data is not accessed.

RESTORE ENGLISH
Close the game, then double-click Restaurer-Anglais.bat. The saved originals
and current files are verified before replacement. Backups remain available.
You can reinstall French afterwards with Installer-FR.bat.

TROUBLESHOOTING
An incompatible version, another mod changing the same files, a corrupted patch,
an invalid backup, or a running game causes installation to stop with an error.
Restoration refuses files changed since installation. Restore compatible original
files first; Steam verification retrieves the currently available game version,
which may no longer be 2.2.0 after a future update.
An existing installation made with this kit is detected without overwriting it.
A manually translated copy without this kit's English backups must first be
returned to compatible originals. This delta kit does not contain those originals.
Ensure the game directory is writable. Managed Windows systems that prohibit
scripts may block the installer. Do not edit the expected hashes to bypass checks.

COVERAGE AND BETA STATUS
1,813 translated I2 keys, 214 intentionally unchanged values, and 34 translated
COMM.txt lines. Covers menus, UI, weapons, items, spells, dialogue, books,
cutscenes, lore, and endings handled by these resources.
Proper names, puzzle clues, and technical elements are preserved. The author's
pronoun system is preserved; some pronouns intentionally remain in English.
The hard-coded Health: label may also remain English. Notes is French as well.

The translation works in game, including accents, but has NOT undergone
exhaustive human proofreading. French text and scripts were produced with help
from OpenAI Codex; the project owner tested integration in game. Please report
issues with context and, when possible, a screenshot. This is an unofficial
fan project, not an official or endorsed localization.

DISTRIBUTION
The archive contains two binary deltas, readable installer scripts and docs.
It includes no game executable, DLL, complete resources.assets or complete
COMM.txt. Required original data is read from your compatible game installation.
A delta format does not automatically grant distribution rights. The script
license does not cover Lunacid's writing or assets. See the credits/license files.



LUNACID — TRADUCTION FRANÇAISE NON OFFICIELLE
Version du patch : 1.0-BETA — 31 octobre 2026

PRÉREQUIS
Posséder Lunacid. Version Windows 2.2.0 vérifiée, avec ses fichiers originaux
compatibles. Windows PowerShell 5.1 et .NET fournis avec Windows suffisent.
Aucun Python, Node.js, mod loader ou téléchargement supplémentaire requis.
Le kit contrôle les SHA-256 des fichiers : le seul numéro « 2.2.0 » ne suffit pas.

INSTALLATION
1. Fermez Lunacid.
2. Dans Steam : clic droit sur Lunacid > Gérer > Parcourir les fichiers locaux.
3. Extrayez TOUT le ZIP dans ce dossier. Installer-FR.bat et le dossier Patch-FR
   doivent être à côté de LUNACID.exe. Ne lancez pas le BAT depuis le ZIP.
4. Double-cliquez sur Installer-FR.bat. Attendez le message SUCCÈS.
5. Lancez le jeu normalement et conservez la langue English.

Le kit sauvegarde les deux originaux avant remplacement, reconstruit les fichiers
français localement et contrôle leurs empreintes. Il ne touche qu'à :
  LUNACID_Data\resources.assets
  LUNACID_Data\Resources\TXT\ENG\COMM.txt
Ne supprimez pas Lunacid-FR-Sauvegardes si vous souhaitez restaurer l'anglais.
Les sauvegardes de progression ne sont ni lues ni modifiées.

REVENIR À L'ANGLAIS
Fermez le jeu et double-cliquez sur Restaurer-Anglais.bat.
La restauration vérifie les originaux sauvegardés et les fichiers actuels avant
de les remplacer. Les sauvegardes anglaises sont conservées après restauration.
Vous pouvez ensuite réinstaller avec Installer-FR.bat.

EN CAS DE REFUS
- Fichiers incompatibles : autre version ou mod touchant aux mêmes fichiers.
  Restaurez d'abord vos fichiers originaux compatibles. Une vérification Steam
  récupère la version actuellement disponible ; elle ne garantit pas 2.2.0 si
  une mise à jour plus récente a été publiée.
- Traduction déjà installée par ce kit : elle est reconnue sans écrasement.
- Copie déjà traduite manuellement, sans sauvegardes créées par ce kit :
  rétablissez les originaux avec Steam ou votre propre sauvegarde avant usage.
  Le patch différentiel ne contient pas les originaux anglais.
- Jeu ouvert, fichier verrouillé ou accès refusé : fermez le jeu et les outils
  qui utilisent ses fichiers, puis vérifiez les droits d'écriture du dossier.
- Patch endommagé : téléchargez et extrayez à nouveau l'archive complète.
Les configurations qui interdisent les scripts Windows peuvent empêcher le kit.
Les fichiers modifiés après installation sont refusés par la restauration.

CONTENU ET ÉTAT DE LA TRADUCTION
1 813 clés I2 traduites, 214 valeurs volontairement conservées, 34 répliques
dans COMM.txt. Couverture : menus, interface, armes, objets, sorts, dialogues,
livres, cinématiques, lore et fins gérés par ces ressources.
Les noms propres, indices et éléments techniques nécessaires sont conservés.
Le système de pronoms de l'auteur reste intact ; certains pronoms restent
en anglais. Le libellé Health: inscrit dans le code peut aussi rester anglais.
Le titre Notes est correct en français et reste identique à l'anglais.

La traduction fonctionne en jeu, accents compris, mais n'a pas bénéficié d'une
relecture humaine exhaustive. Les textes français et les scripts ont été
réalisés avec l'aide d'OpenAI Codex ; l'intégration a été testée en jeu par le
porteur du projet. Merci de signaler les erreurs avec le contexte et, si possible,
une capture. Cette BETA n'est ni officielle ni approuvée par les créateurs du jeu.

DISTRIBUTION
L'archive contient uniquement deux différences binaires, les scripts lisibles
et leur documentation. Aucun exécutable du jeu, DLL, fichier resources.assets
complet ou COMM.txt complet n'est inclus. Les données d'origine nécessaires
sont reprises depuis votre propre installation compatible.
Le format différentiel ne constitue pas une autorisation de redistribution.
La licence des scripts ne couvre ni les textes ni les ressources de Lunacid.
Voir CREDITS-Lunacid-FR.txt et LICENCE-SCRIPTS.txt.

Après une mise à jour du jeu, attendez un patch compatible. Ne forcez pas le
remplacement des empreintes attendues dans le manifeste.


[README-FR.txt](https://github.com/user-attachments/files/34269175/README-FR.txt)

