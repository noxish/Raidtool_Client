


## Raidtool Sync Client

Dieser Client untersützt das Sometimes Prepared Raidtool in dem es Gildenmember und Eigene Berufe über ein World of Warcraft Addon Exportiert und anschließend an
das Raidtool mittels API übermittelt

### Download

- [Download Client](https://github.com/noxish/Raidtools-Client/releases/latest)
- [Download Addon via Curseforge](https://www.curseforge.com/wow/addons/raidtool-export/download/3460120?client=y)

### Vor der Installation

##### Ladet das Addon über Curseforge herunter und Entpackt es dann in euren Interface Ordner oder Installiert das Addon direkt über den Curseforge Client. 
##### Das Addon wird benötigt um die Daten aus World of Warcraft zu Exportieren. Die Exportierten Daten werden im "WTF" Ordner unter dem jeweiligen Charakter gespeichert und sind dort einsehbar.

### Installation

##### Bei der ersten Installation kann es dazu kommen das sich [Windows Smartscreen¹](https://github.com/noxish/Raidtools-Client/blob/gh-pages/index.md#-windows-smartscreen) meldet. Hierzu einfach auf "Weitere Informationen" klicken.
![20-09-_2021_12-34-03](https://user-images.githubusercontent.com/3374229/134125009-6f5d70fc-6bea-4530-ba55-2bce35908e9f.png)

##### Durch einen Klick auf "Trotzdem Ausführen" kann die App Installiert werden
![20-09-_2021_12-34-13](https://user-images.githubusercontent.com/3374229/134124988-7b9bdd5e-9169-4a1f-94c4-e0be1723f76e.png)

### Erster Start

##### Beim ersten Start wird direkt die Seite Einstellungen geöffnet.
![20-09-_2021_13-42-54](https://user-images.githubusercontent.com/3374229/134123607-4aa43a9f-d525-431d-9234-a813721d7f64.png)

##### hier muss dann der Pfad zur World of Warcraft Installation incl. _classic_ ordner angegeben werden. Nach einem klick auf Speicher sollte auf der Rechten Seite
##### anschließend der Servername und der Gildenname erscheinen.
![20-09-_2021_13-44-50](https://user-images.githubusercontent.com/3374229/134123614-a4ded89b-49a0-433c-906c-d053879b34ad.png)

##### anschließend kann auf die Hauptseite gewechselt werden, hier sollten dann die über das Raidtool zugewiesenen Charactere angezeigt werden.
![20-09-_2021_13-44-59](https://user-images.githubusercontent.com/3374229/134123617-b7200855-3307-4d04-8577-af722bb45c2f.png)

### Problemlösungen

##### Sollten keine Charaktere angezeigt werden kann durch einen Klick auf den Reload Button die Liste erneut geladen werden.
![20-09-_2021_13-424-59](https://user-images.githubusercontent.com/3374229/134124243-cc32981e-175b-4322-bb79-96580e2a14eb.png)

##### Sollte einmal garnichts mehr gehen, kann es helfen die App Daten zurückzusetzen
##### hierzu könnt ihr einfach unter C:\Users\Username\Documents\Raidtool Client Data\ die Datei RaidtoolsClient.sqlite3 löschen und die App Neustarten.
![20-09-_2021_13-42-54](https://user-images.githubusercontent.com/3374229/134124949-ce2dcc4d-dfb3-4ccd-88c1-ec6cb1caa6ea.png)

### ToDo

 - App automatisch mit Windows Starten
 - Usereingaben für Berufe und Skillung

###### ¹ Windows Smartscreen
###### Er prüft ob das heruntergeladene Programm bei Microsoft auf einer Liste mit gefährlichen Programmen steht. Findet er den Download in dieser Liste wird die Ausführung des Programms verhindert und der User darauf hingewiesen dass das Programm möglicherweise gefährlich ist.
###### Er prüft ob das heruntergeladene Programm bei Microsoft auf einer List mit häufig heruntergeladenen Programmen steht. Software die häufig von Windowsnutzern heruntergeladen wird, wird als sicher eingestuft. Ein unbekanntes Programm wird als unsicher eingestuft, die Ausführung verhindert und der Benutzer informiert dass das Programm möglicherweise gefährlich ist.


