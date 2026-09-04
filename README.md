# DPI factice — page de test

Un faux dossier patient informatisé, pour tester l'extension **Documenter EHR Bridge** sans toucher à un vrai dossier.

**→ [Ouvrir la page de test](https://ftomma.github.io/dpi-factice/)**

Le patient et tout le contenu sont inventés. La page ne contient aucun appel réseau, n'enregistre rien et n'envoie rien nulle part : écrivez ce que vous voulez dedans.

Les champs reprennent les onze sections d'un rapport de consultation Documenter — Motif de consultation, Anamnèse, Antécédents, Allergies, Traitement actuel, Examen clinique, Examens complémentaires, Diagnostic, Discussion, Propositions, Suivi — pour que chaque section proposée par l'extension ait un champ à mapper.

Elle couvre les cas qui comptent : champs vides, champ déjà rempli (le texte existant doit survivre), champ verrouillé, texte enrichi, un champ dans un cadre séparé, et un champ « Allergies » contenant une négation — si le rapport mentionne une allergie, elle doit être ajoutée, jamais ignorée.

Les limites connues sont listées en bas de la page : inutile de les signaler.
