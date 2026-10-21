# Pegolotti GPT — téléchargements

Ce dépôt public distribue uniquement les installateurs et les mises à jour Windows de Pegolotti GPT. Le code source reste dans un dépôt privé.

Pegolotti GPT fonctionne localement sur le poste Windows, avec Codex. GitHub sert au téléchargement du logiciel ; les conversations ne passent pas par GitHub.

La [version 0.1.26](https://github.com/creezio/pegolotti-gpt-releases/releases/tag/v0.1.26) est disponible depuis le bouton **Mettre à jour et redémarrer** de Pegolotti. Pour une première installation : [télécharger l’installateur Windows](https://github.com/creezio/pegolotti-gpt-releases/releases/latest/download/PegolottiGPT-Setup.exe).

La version 0.1.26 corrige l’ouverture de l’interface locale : le bouton Windows, l’icône et le raccourci utilisent le navigateur et le profil mémorisés, comme les connexions des plugins. Vérifié dans la version installée avec Chrome / Fidus « Profile 32 », en utilisant la sélection existante de Switcher. La mise à jour intégrée 0.1.25 → 0.1.26 a passé en 42 secondes, avec le même compte et les mêmes processus Codex.

Le catalogue, ses descriptions et ses logos sont embarqués. L’actualisation complète travaille en arrière-plan, avec un statut léger ; la liste reste consultable pendant l’extraction.

La mise à jour 0.1.24 → 0.1.25 a été vérifiée sur Fidus le 21 octobre 2026 : une seule demande à l’API locale, téléchargement GitHub, fermeture et redémarrage automatiques en 51 secondes. Le compte et les processus Codex ouverts sont conservés. Aucun compte GitHub n’est nécessaire pour télécharger les mises à jour.

Le correctif 0.1.26 a passé 2 426 contrôles Windows et 32 contrôles ciblés du navigateur. L’interface JavaScript et le catalogue restent ceux de 0.1.25. Les performances complètes de l’interface installée restent en qualification : le premier affichage du catalogue dépasse encore l’objectif de 3 secondes. La disponibilité sur le canal de téléchargement ne vaut pas validation de cette recette de performance.

Le canal public est [windows-channel.json](https://github.com/creezio/pegolotti-gpt-releases/releases/latest/download/windows-channel.json). Les versions et leurs sommes de contrôle sont conservées dans [Releases](https://github.com/creezio/pegolotti-gpt-releases/releases).
