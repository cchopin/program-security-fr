*Introduction ajoutée pour cette traduction, hors traduction directe.*

Ce module porte sur l'allocateur mémoire dynamique, c'est-à-dire les fonctions `malloc` et `free`, et sur les erreurs courantes dans leur usage. Les défis suivent une progression : une première utilisation après libération (use-after-free), puis ses variantes avec plusieurs allocations, la corruption des métadonnées du TCACHE, l'usurpation d'adresses de pile, les chevauchements d'allocations, et enfin le safe-linking du TCACHE. Chaque défi existe en deux versions, facile et difficile.
