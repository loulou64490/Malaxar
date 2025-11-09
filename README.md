# Malaxar
Simplification of compiling and executing C programs

Utilisation :
A la place de taper gcc prog.c -lm -Wall -Wextra; ./a, utilisez la commande malaxar !
Elle compile le code, l'execute, puis suprimme l'executable à la fin de l'execution.
Syntaxe : malaxar [options] nom_prog.c arg_1 ... arg_n
Options : 
- -f : ajoute les option -Ofast et -DNDEBUG lors de la compilation, rend l'executable plus rapide et ignore les assert
- -v : execute le code dans Valgrind

Installation :
1. Tapez cd pour aller dans le répertoire de base
2. ouvrez le ficher .bash_aliases ou créez-le s'il n'existe pas
3. copiez-collez le code dans ce fichier
4. relancez le terminal ou taper source .bashrc
