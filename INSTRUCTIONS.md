# Comment mettre en place ce wiki

## 1. Créer le repo GitHub

1. Crée un nouveau repository GitHub, par exemple `infinityrp-wiki`.
2. Mets tous les fichiers de ce dossier (SUMMARY.md, README.md, reglement/, guide/) à la racine du repo.
3. Commit + push.

## 2. Connecter GitBook au repo

1. Sur [gitbook.com](https://gitbook.com), crée un nouveau Space.
2. Dans les paramètres du Space → **Git Sync**, connecte ton compte GitHub et sélectionne le repo `infinityrp-wiki`.
3. GitBook va automatiquement lire `SUMMARY.md` pour construire la table des matières, et se synchroniser à chaque push.

## 3. Mettre le thème en violet

GitBook ne lit pas la couleur depuis le code — c'est un réglage visuel dans l'interface :

1. Dans le Space → **Customization** (icône palette dans les paramètres).
2. Section **Colors** / **Theme** → choisis **Accent color** (couleur d'accent).
3. Sélectionne un violet, par exemple `#8B5CF6` (violet moyen) ou `#A855F7` (violet plus vif) — équivalent visuel à la teinte turquoise du site AlyaRP mais en violet.
4. Personnalise aussi le logo et la bannière (image de couverture) dans **Customization → Header/Logo** avec le logo InfinityRP.

## 4. Domaine personnalisé (optionnel)

Dans **Customization → Domain**, tu peux configurer `wiki.infinityrp.fr` (ou ton propre domaine) en pointant un CNAME vers GitBook, comme le fait AlyaRP avec `wiki.alyarp.fr`.
