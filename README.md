Le projet Libft de l'École 42 consiste à recréer une bibliothèque standard en langage C, en implémentant un ensemble de fonctions essentielles utilisées couramment en programmation. Ce projet a pour but de consolider les bases du langage C, d’approfondir la compréhension des mécanismes bas niveau, et de développer des compétences en gestion de mémoire, en manipulation de pointeurs, et en création de structures de données personnalisées.

Objectifs pédagogiques :
Reproduire des fonctions standard de la bibliothèque C (<stdlib.h>, <string.h>, etc.).
Comprendre les mécanismes internes du langage C (allocation dynamique, manipulation de chaînes de caractères, gestion des tableaux).
Développer une approche rigoureuse pour écrire un code modulaire, lisible et bien documenté.
Apprendre à gérer des projets complexes avec une attention particulière au debugging et aux tests unitaires.

Compétences acquises :

Programmation en C :
Implémentation de fonctions basiques comme strlen, strcpy, atoi, etc.
Création et manipulation de structures de données comme les listes chaînées (linked lists).

Gestion de mémoire :
Utilisation de fonctions telles que malloc, free, pour la gestion dynamique.
Prévention des fuites de mémoire grâce à des tests rigoureux.

Écriture d'une bibliothèque réutilisable :
Organisation et modularité du code source pour faciliter la réutilisation.

Debugging et tests unitaires :
Identification et résolution des erreurs de segmentation ou de comportement inattendu.
Mise en place de tests pour valider le bon fonctionnement de chaque fonction.

Points forts à valoriser :
Approche méthodique : La rigueur dans la mise en œuvre des fonctions standard permet de garantir un code robuste et performant.
Code réutilisable : La bibliothèque libft constitue une base solide qui peut être intégrée dans de nombreux projets futurs.
Polyvalence : Ce projet démontre une capacité à travailler sur des fonctions diverses allant de la manipulation de chaînes à la gestion des structures de données.

Partie 1 : Fonctions de la bibliothèque standard C
ft_memset : Initialise une zone mémoire avec une valeur donnée.
ft_bzero : Initialise une zone mémoire à 0.
ft_memcpy : Copie une zone mémoire dans une autre.
ft_memmove : Déplace une zone mémoire, utile pour les zones qui se chevauchent.
ft_memchr : Recherche un caractère spécifique dans une zone mémoire.
ft_memcmp : Compare deux zones mémoire.
ft_strlen : Calcule la longueur d'une chaîne de caractères.
ft_strchr : Trouve la première occurrence d'un caractère dans une chaîne.
ft_strrchr : Trouve la dernière occurrence d'un caractère dans une chaîne.
ft_strncmp : Compare deux chaînes sur un nombre limité de caractères.
ft_strlcpy : Copie une chaîne avec une gestion sécurisée des débordements.
ft_strlcat : Concatène deux chaînes avec gestion des débordements.
ft_strnstr : Trouve une sous-chaîne dans une chaîne, avec une limite.
ft_atoi : Convertit une chaîne de caractères en entier.
ft_isalpha : Vérifie si un caractère est une lettre.
ft_isdigit : Vérifie si un caractère est un chiffre.
ft_isalnum : Vérifie si un caractère est une lettre ou un chiffre.
ft_isascii : Vérifie si un caractère appartient à la table ASCII.
ft_isprint : Vérifie si un caractère est imprimable.
ft_toupper : Convertit un caractère en majuscule.
ft_tolower : Convertit un caractère en minuscule.

Partie 2 : Fonctions supplémentaires
ft_strdup : Duplique une chaîne de caractères.
ft_calloc : Alloue une zone mémoire initialisée à 0.

Partie 3 : Fonctions bonus (Listes chaînées)
ft_lstnew : Crée un nouvel élément de liste chaînée.
ft_lstadd_front : Ajoute un élément au début d'une liste chaînée.
ft_lstsize : Calcule le nombre d'éléments dans une liste chaînée.
ft_lstlast : Renvoie le dernier élément d'une liste chaînée.
ft_lstadd_back : Ajoute un élément à la fin d'une liste chaînée.
ft_lstdelone : Supprime un élément d'une liste chaînée.
ft_lstclear : Supprime tous les éléments d'une liste chaînée.
ft_lstiter : Applique une fonction à chaque élément d'une liste chaînée.
ft_lstmap : Crée une nouvelle liste en appliquant une fonction à chaque élément.
