CD Githubgit
CD fornamn-vaxthyllan
git status
git add GIT-KEDJA.md
git status
Git commit -m "GIT-KEDJA.md added, Guram"
git push

cd "C:\Users\goran\OneDrive\Skrivbord\Mjukvaruutveckling Folkuniversitet\Frontend\GithubGit\fornamn-vaxthyllan"

git init <!--¨Behöver ej skapa nytt mapp/repo"--> "istället change directory till GIThubGit och sedan fornamn-vaxthyllan"

git add . <!--"Tar med allt i filen, inte den specifika filen"--> "Tar med alla filer behövs ej, ändrar till Git add GIT-KEDJA.md"

git commit -m "Initial commit" <!--Dålig meddelande, säger ingenting om vad jag gjort--> "Istället gjort commit -m "GIT- KEDJA.MD added,Guram"

git branch -M main <!--Behöver inte skapa branch från main-->

git remote add origin https://github.com/DITT_ANVÄNDARNAMN/REPO-NAMN.git <!--Detta är inte adressen till mitt repo-->
git push -u origin main <!--pushar men till main-->
"Gör git push då det är förinställt vart git ska skicka/pusha by default"
