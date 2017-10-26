# NOTATKA Z WYKLADU

## 1. Przygotowanie srodowiska pracy
- instalacja VirtualBox
- instalacja systemu Ubuntu

## Powtórzenie podstawowych komend systemu linux
- *pwd*
- *clear*
- *ls -al*
- *pwd*
- *cd* 
- *cd ..*
- *mkdir Firs_repo*
  
- *mkdir 1 2 3 4*
- *rm -d 1 2 3 4*

## Instalacja systemu do zarządzania repozytorium `git`
-  sudo apt install git
-  git --version 
-  git --help 
  
## Inicjacja oraz obsluga git
-  First_repo/   
-  touch test.txt
-  vim test.txt 
-  git init     
 
-   *git status
-   git add test.txt 
-   git config --global user.email "konnio@gmail.com"
-   git config --global user.name "konnio"
-   git commit -m "utworzenie nowego katalogu"
-   git status 
-   git log*
  
126  git add .
  127  git commit -m "Pierwsza zmiana w pliku"
  128  git log 
  129  vim test.txt 
  130  git status 
  131  git add test.txt
  132  git commit -m "Druga zmiana w pliku"
  133  git log
  134  git status 
  135  ls -al
  136  mc
  137  ls
  138  git remote add origin https://github.com/konnio/First_repo.git
  139  git push -u origin master
  140  vim test.txt 
  141  git add test.txt 
  142  git commit -m "Trzecia zmiana w pliku"
  143  git push -u origin master
  144  git status 
  145  vim test.txt
  146  git add .
  147  git commit -m "To już czwarta zmiana"
  148  git push
  149  ls
  150  ls -al
  151  cat /var/log/
  152  cat /var/log/syslog 
  153  cat /var/log/kern.log 
  154  tail /var/log/kern.log 
  155  git logh
  156  git log
  157  tail /var/log/kern.log 
  158  history > readme.md
