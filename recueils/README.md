# Recueils

Pour l'instant juste le recueil de la première année : "recueil1718.pdf"

Indications pour la compilation : il suffit de compiler recueil1718.tex.

Pour modifier les exercices (y compris les indications et solutions), il faut le faire dans les fichiers chap[...].tex.
Les fichiers preambule.tex et macros_answers.tex contiennent les macros.

Le package "answers" extrait automatiquement les indications et solutions des exercices, va créer les fichiers latex supplémentaires recueil1718_hints.tex, recueil1718_hints2.tex et recueil1718_sol.tex, puis les inclure à la volée lors de la compilation pour avoir les indications et solutions à la fin du document. On ne doit pas toucher à ces fichiers; en particulier on ne doit pas modifier les indications et solutions dans ces fichiers latex, mais uniquement dans le fichiers "chap[...].tex". (Toute modification dans ces fichiers annexes sera perdue lors de la compilation suivante, qui va les écraser.)

