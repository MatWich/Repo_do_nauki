# Repo_do_nauki

"Pierwszy commit napisany samemu w konsoli a zarazem pierwsza zmiana :D "

Podstawowe komendy  do gita:

1. git status

Pokazuje nowo utworzone pliki nie znajduj�ce si� jeszcze w repozytorium 
ponadto jesli w jakim� pliku zasz�a zmiana te� nas o tym poinformuje :D

2. git log 

Pokazuje commity, mail, nazw� autora commita oraz tre�� je�li jaka� zosta�a umieszczona

3. git add nazwa_pliku

Pakujemy w pude�ko plik , kt�ry zamierzamy wys�a� do repozytorium

4. git commit -m "Nazwa wiadomo�ci mo�e by� co kolwiek"

Naklejamy nalepke z adresem i (opcjonalna) wiadomo�ci�

5. git push origin nazwa_brancha

I posz�o do repo :D na brancha tego, kt�rego podali�my :D




Fajna komenda :

git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'


