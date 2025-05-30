# Repunctuation_ancient_Chinese

Ce projet vise à explorer différentes méthodes de reponctuation automatique pour des textes en chinois classique, en comparant des approches d’étiquetage de séquence et de génération de séquence.

- **dataset/** : Contient les sous-dossiers `train`, `dev`, `test` ,`brut` etc. --> les fichiers textes utilisés pour l'entraînement et l'évaluation
- **LSTM.ipynb** : Implémentation d'un modèle d'étiquetage de séquence (BiLSTM), où chaque caractère du texte reçoit une étiquette de ponctuation
- **generator.ipynb** : Implémentation d’un modèle sequence-to-sequence à attention pour générer la version ponctuée d’une séquence non ponctuée (encoder-decoder GRU avec attention).
- **generator_abandonné.ipynb** : Ancienne version ou essai non retenu du générateur
- **nettoyage.ipynb** : Scripts de nettoyage, prétraitement et structuration des corpus (suppression de ponctuation, split, etc.)