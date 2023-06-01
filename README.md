# git-excercise

Git excercises

1. skapat repo på github.
2. för att ladda upp projektet gjorde jag följande:
   git init
   git add . (sätter allt som staged)
   git commit -m "<ett meddelande>"
   git remote add <https länken till mitt repo>
   råkade därefter skapa en ny branch kallad master: $ git branch --set-upstream-to=main master
   git push -u origin master
   pushade till den nya branchen:
   git push -u origin master
   sedan mergade jag main och master:
   git checkout main
   git merge master
   git add .
   git commit -m

   Eftersom det blev fel med skapadet av brancherna och mina commits mergade jag genom:
   git pull origin main --allow-unrelated-historires
   git push --set-upstream origin main

För att återgå till en tidigare version ta SSHS från commit historiken i github (eller kör git log) till den version du vill återgå till och kör git checkout < sshs >

För att merga flera branches till samma kör git checkout på den branch man vill merga till sedan gör git merge branch1 > git merge branch2 > git commit -m "meddelande" > git push origin main

genom att ta bort det lokala och clona repot så laddar man ner ett projekt för att kunna arbeta med det lokalt och innehåller git historiken från det clonade repot.

Om jag forkar ett annat projekt så arbetar jag inte mot det ursprungliga repot jag tog det från utan har min egna kopia på mitt egna repo som har sin enga git historik.
