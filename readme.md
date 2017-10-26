# NOTATKA Z WYKLADU

## 1. Przygotowanie srodowiska pracy
- instalacja VirtualBox
- instalacja systemu Ubuntu

## 2. Powtórzenie podstawowych komend systemu linux
- *pwd*
- *clear*
- *ls -al*
- *pwd*
- *cd* 
- *cd ..*
- *mkdir First_repo*
- *mkdir 1 2 3 4*
- *rm -d 1 2 3 4*

## 3. Instalacja systemu do zarządzania repozytorium `git`
-  *sudo apt install git*
-  *git --version *
-  *git --help* 
  
## Inicjacja oraz obsluga git
-  *cd First_repo/*
-  *touch test.txt*
-  *vim test.txt* 
-  *git init*     
 
-   *git status*
-   *git add test.txt*
-   *git config --global user.email "konnio@gmail.com"*
-   *git config --global user.name "konnio"*
-   *git commit -m "utworzenie nowego katalogu"*
-   *git status*
-   *git log*
-   *git add .*
-   *git commit -m "Pierwsza zmiana w pliku"*
-   *vim test.txt*	
-   *git add test.txt*
-   *git commit -m "Druga zmiana w pliku"*

Polaczenie ze zdalnym repozytorium
  git remote add origin https://github.com/konnio/First_repo.git
  git push -u origin master
  vim test.txt 
  git add test.txt 
  git commit -m "Trzecia zmiana w pliku"
  git push -u origin master
  git add .
  git commit -m "To już czwarta zmiana"
  git push

