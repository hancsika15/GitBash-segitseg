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
git push -u origin main #feltölti az origin nevű repoba a commitokat
git pull origin main

További terminál parancsok:
git pull origin main #a friss repo letöltése
git remote -v #aktuális repo lekérdezése
git status #change,stage,commit állapot lekérdezése
git config --global --list #globális beállítások listázása
cd <directory name> #Change Directory
cd.. #egy mappával feljebb lép
mkdir<directory name> #makedirectory
rmdir<directory name> #remove directory
ls #list -könyvtár listázása
git commit -am "messeage" #összes változtatást és commit egy lépésben