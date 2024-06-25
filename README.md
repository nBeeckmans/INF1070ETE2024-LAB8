# INF1070ETE2024-LAB8

## Partie 1 : 

Préparation du pdf :

Téléchargement : 
```sh
wget https://gitlab.info.uqam.ca/inf1070/labs/-/raw/master/labo08/professeurs.pdf
```

Conversion : 
```sh 
pdftotext professeurs.pdf 
```

Utilisation de grep :

```sh
$ cat professeurs.txt | grep -oE "\w*(\.\w*)+@uqam.ca"
```

`-E` : utilisation d'expression régulière étendue. 
`-o` : met en output la partie trouvée par `grep`. 


## Partie 2, 3, 4: 

Regexone offre une solution pour chaque exercice. 

Mot croisé : Il est difficile pour moi de faire un corrigé... désolé. 

Golf : 
`?!` => negation : ex (?!.*abba) => ne contient pas abba 

