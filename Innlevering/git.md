# Oppgave 3

- git init
- git checkout -b master
- echo 'testfil' >> test.txt
- git add .
- git commit -am "Inital master commit"
- git push

- git checkout -b dev
- echo 'console.log("hiof") >> hiof.js
- git add .
- git commit -am "Added hiof.js"
- git push
- git fetch
- git pull
- git checkout master
- git merge dev
- git commit -am "Merge dev into master"
- git push
