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
