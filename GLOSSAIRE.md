# Glossaire

Termes retenus pour la traduction. À la première occurrence d'un terme dans un module, le terme anglais figure entre parenthèses. Les termes ci-dessous sont employés de la même façon dans tous les modules.

## Termes traduits

| Anglais | Français retenu | Remarque |
|---|---|---|
| program | programme | « programme informatique » (computer program) pour éviter l'ambiguïté avec le programme au sens de planning |
| instruction | instruction | |
| operator | opérateur | Premier élément d'une instruction, par exemple `mov`. |
| operand | opérande | Données sur lesquelles agit une instruction. |
| CPU, Central Processing Unit | processeur (CPU) | L'acronyme CPU est conservé. |
| register | registre | Premier usage : « registre (register) ». |
| general purpose register | registre à usage général | |
| special register | registre particulier | Par exemple `rip`, `rsp`. |
| register file | banc de registres | Ensemble des registres du processeur. |
| immediate value | valeur immédiate | Valeur écrite directement dans l'instruction. |
| assembly language | langage d'assemblage | Langage de l'assembleur. |
| assembler (outil `as`) | assembleur | Désigne l'outil qui transforme le code d'assemblage en binaire. |
| assembly (code) | code d'assemblage | Le code d'assemblage est écrit en langage d'assemblage. |
| assembly syntax | syntaxe (Intel, AT&T) | Par exemple « syntaxe Intel (Intel Syntax) ». |
| linker | éditeur de liens | Outil `ld`. |
| object file | fichier objet | Résultat de l'assemblage, avant l'édition de liens. |
| executable | exécutable | |
| binary (fichier, code) | binaire | Par exemple « exécutable binaire ». |
| operating system | système d'exploitation | |
| system call | appel système | Premier usage : « appel système (system call) ». |
| syscall number | numéro d'appel système | |
| exit code | code de retour | |
| interpreter | interpréteur | |
| compiler | compilateur | |
| JIT compiler | compilateur JIT | Traduit à la volée, à l'exécution. |
| bytecode | bytecode | Terme conservé. |
| bit | bit | |
| byte | octet | |
| nibble | quartet | Quatre bits. |
| word | mot | Sur x86, un mot vaut 16 bits. Voir l'ambiguïté signalée dans la fiche de cours. |
| double word (dword) | double mot | 32 bits. |
| quad word (qword) | quadruple mot | 64 bits. |
| most significant bit | bit de poids fort | |
| least significant bit | bit de poids faible | |
| sign bit | bit de signe | |
| two's complement | complément à deux | |
| integer overflow | dépassement de capacité | |
| endianness | boutisme | Mentionné seulement dans la fiche de cours, pas encore traité. |
| memory | mémoire | |
| cache | cache | Terme conservé. |
| stack | pile | |
| stack pointer | pointeur de pile | Registre `rsp`. |
| instruction pointer | pointeur d'instruction | Registre `rip`. |
| label | étiquette | |
| directive (assembleur) | directive | |
| flag (défi) | flag | Terme conservé, voir ci-dessous. |
| kernel | noyau | |
| floating point | virgule flottante | |
| shift | décalage | |
| rotation | rotation | |
| hexadecimal | hexadécimal | |
| octal | octal | |
| binary (number system) | binaire | Système de numération en base 2. |
| decimal | décimal | |
| ASCII | ASCII | Terme conservé. |
| control character | caractère de contrôle | |
| extended character | caractère étendu | |
| challenge | défi | Un « défi » est un exercice du dojo. |
| module | module | |
| dojo | dojo | Terme conservé. |
| lecture | cours | Ressource de type cours avec vidéo et diapositives. |
| slides | diapositives | |
| header (ressource) | en-tête | |

## Termes conservés en anglais

Ces termes ne sont pas traduits, car les francophones du domaine les emploient tels quels, ou car ils se tapent au clavier :

- flag, shell, shellcode, buffer overflow, dojo, cache, bytecode, ASCII, UTF-8, Intel, AT&T
- toutes les commandes, les noms de fichiers, les registres, les instructions, les appels système, les options d'outils, les invites de commande (`hacker@dojo:~$`)
- les messages affichés par les programmes de vérification, lorsqu'ils sont cités (voir la règle de traduction entre parenthèses)

## Noms de modules et de défis

Le nom traduit précède le nom anglais entre parenthèses, par exemple « Votre premier registre (Your First Register) ». Les identifiants restent en anglais, comme dans l'original.

## Choix discutables

- « programme » est employé pour *program*. La traduction de *program* par « programme » ne pose pas de difficulté dans ce cours.
- « registre à usage général » et « registre particulier » : les deux expressions sont courantes en français.
- « défi » pour *challenge* : préférable à « exercice » ou « challenge », qui ne reflètent pas la vérification automatique par `/challenge/check`.
- « mot » pour *word* : terme ambigu, précisé à chaque occurrence dans la fiche de cours.

## Termes ajoutés pour les modules 2 à 8

| Anglais | Français retenu | Remarque |
|---|---|---|
| file descriptor | descripteur de fichier | |
| standard input, output, error | entrée standard, sortie standard, erreur standard | |
| string | chaîne de caractères | |
| memory address | adresse mémoire | |
| address space | espace d'adressage | |
| pointer | pointeur | |
| dereference | déréférencer | Verbe, par exemple « déréférencer un pointeur ». |
| offset | décalage | |
| little endian | petit-boutisme | Nom : « boutisme » (endianness). |
| big endian | gros-boutisme | |
| debugger | débogueur | |
| breakpoint | point d'arrêt | |
| syscall tracer | traceur d'appels système | |
| timer | minuteur | |
| hint | indice | |
| mnemonic | moyen mnémotechnique | |
| level (défi) | niveau | Pour les défis de type « level-N ». |
| control flow | flot d'exécution | |
| zero flag (ZF) | indicateur de zéro (ZF) | Les indicateurs (flags) du processeur gardent leur nom anglais en majuscules. |
| flags (processeur) | indicateurs | |
| stack frame | cadre de pile | |
| calling convention | convention d'appel | |
| callee-saved register | registre préservé par l'appelé | |
| process | processus | |
| parent, child (fork) | parent, enfant | |
| PID | PID | Terme conservé. |
| socket | socket | Terme conservé. |
| backlog | file d'attente (backlog) | |
| port | port | |
| trampoline | trampoline | Terme conservé. |

## Termes ajoutés pour les modules de la source actuelle

| Anglais | Français retenu | Remarque |
|---|---|---|
| caller-saved register | registre non préservé par l'appelé | Aussi appelé registre sauvegardé par l'appelant. |
| callee-saved register | registre préservé par l'appelé | |
| calling convention | convention d'appel | |
| jump table | table de sauts | |
| switch | aiguillage (switch) | |
| zero flag (ZF), carry flag (CF), overflow flag (OF), sign flag (SF) | indicateur de zéro (ZF), de retenue (CF), de débordement (OF), de signe (SF) | Les indicateurs (flags) du processeur. |
| byte low, byte high | octet de poids faible, octet de poids fort | |
| shared library | bibliothèque partagée | |
| size directive (`BYTE PTR`) | directive de taille | |
| null byte, NUL terminator | octet nul, terminateur NUL | |
| RIP-relative addressing | adressage relatif à rip | |
| load effective address (`lea`) | chargement d'adresse effective | |
| network byte order | ordre des octets du réseau | |
| file descriptor (fd) | descripteur de fichier (fd) | |
| disassembly | désassemblage | |
| cooperative debugging | débogage coopératif | |
| stepi | avancer d'une instruction (`stepi`) | |
| censored | censuré | |
| sign extension | extension de signe | |
| bit shift | décalage de bits | |
| mask | masque | |
| XOR | ou exclusif (XOR) | |
| format string | chaîne de format | |
| formatter | formateur | |
| escape sequence | séquence d'échappement | |
| environment variable | variable d'environnement | |
| struct | structure | |
| calculator | calculatrice | |
| byte, word, dword, qword | octet, mot, double mot, quadruple mot | |
| short | short (16 bits) | |
| stack frame | cadre de pile | |
| trampoline | trampoline | Terme conservé. |
| jump | saut | |
| level (défi) | niveau | |
