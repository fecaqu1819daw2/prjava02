# prjava02
Primera part:

1. wget http://www.collados.org/daw2/m08/uf4/m08uf4pr3/prjava02.zip
5. git checkout master 
  git status
  git log
  Que a la branca master no surt el commit que hem fet a la branca00.
6. No puc veure la útlima lína afegida degut a que estic a una altra branca i no estan fusionades encara, per tant, si faig un canvi a la branca00 no el podré veure a la branca master.
7. Si que el puc veure degut a que torno a estar a la branca on he modificat l'arxiu.
  
Segona part:
10. git checkout master
    git merge branca00
    Ara al estar fusionades les branques master i branca00 el contingut de Prjava02.java s'ha modificat afegint-t'hi la línia de codi que hem afegit a la branca00.
12. git push -u orgin master
    Només s'ha actualitzat la branca master degut a que a l'hora de fer el push li hem dit que el faci sobre la branca master però veurem el fitxer Prjava02.java modificat degut a que les branques master i branca00 estan fusionades.
14. git push -u origin branca01
