#Hello
or create a new repository on the command line
echo "# Teszt" >> README.md #fájl létrehozása, az első sorba "#teszt" kerül
git init #git mappa inicializálása
git add README.md #stagig changes, azaz a változások mentése
git commit -m "first commit" #változások jóváhagyása,és megjelölés beküldésre
git branch -M main #a fejlesztéési ág megnevezése main-re
git remote add origin https://github.com/hancsika15/Teszt.git #távoli repo hozzáadása origin néven
git push -u origin main #a fejlesztési ág feltültése első alkalommal
…or push an existing repository from the command line
git remote add origin https://github.com/hancsika15/Teszt.git
git branch -M main
git push -u origin main
