 # NOTES POUR LE C:


---

## Voir dans un fichier:

### strings

```c
strings mon_programme
```
Affiche tout ce que est visible comme string parmi le binaire.

### objdump:

objdump = object dump = "vide le contenu d'un fichier objet"
Traduction conceptuelle : Montre le contenu brut de ton programme compilé.

```bash 
objdump -s programme
```

**Option -s :**
-s = --full-contents = affiche toutes les sections du fichier en hexadécimal

- code machine ( instructions CPU en hexadecimal)
- données statiques ( strings, varibales globales)
- les sections du binaire

**autres options : **

```bash 
objdump -d programme
```

Montre l'assembleur avec de l'aide.
