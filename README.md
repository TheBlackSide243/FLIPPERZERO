# FLIPPERZERO BADKB ITA
salve questi sono i miei scipt per installare vari software via flipper zero sul pc 
includono powertoys,discord,brave,steam,epicgames,notepad++ e molto altro
include lo script per fare il debloating su windows 11 

vi lascio un example per creare un comando vostro :

```
REM "app che volete"
REM Author: "nome dell autore"
DELAY 2000
GUI x
DELAY 2000
STRING a
DELAY 2000
LEFTARROW
DELAY 2000
ENTER
DELAY 4000
STRING Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
DELAY 2000
ENTER
DELAY 15000
STRING choco install "app che volete"
DELAY 2000
ENTER
DELAY 10000
STRING A
DELAY 2000
ENTER
REM "messaggio finale"
```

PER TROVARE IL NOME IN CHOCOLATEY DELL APP APRIRE IL TERMINALE(ADMIN) E METTERE 
CHOCO FIND "INIZIALI DELL APP DA INSTALLARE"


# FLIPPERZERO BADKB ENG
Hi, these are my scripts for installing various software via Pinball Zero on your PC
include powertoys, discord, brave, steam, epicgames, notepad++ and more
includes the script for debloating on windows 11

I leave you an example to create your own command:

```
REM "NAME OF THE APP U WANT"
REM Author: "NAME OF AUTHOR"
DELAY 2000
GUI x
DELAY 2000
STRING a
DELAY 2000
LEFTARROW
DELAY 2000
ENTER
DELAY 4000
STRING Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
DELAY 2000
ENTER
DELAY 15000
STRING choco install "NAME OF THE APP U WANT"
DELAY 2000
ENTER
DELAY 10000
STRING A
DELAY 2000
ENTER
REM "FINAL TEXT"
```

TO FIND THE NAME IN CHOCOLATEY OF THE APP OPEN THE TERMINAL (ADMIN) AND PUT
CHOCO FIND "INITIALS OF THE APP TO BE INSTALLED"
