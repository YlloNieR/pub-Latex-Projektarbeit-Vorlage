# Latex-Projektarbeit-Vorlage
Eine in Latex geschriebene Vorlage für die Projektdokumentation vom Fachinformatiker Systemintegration oder Anwendungsentwickler

#### notwendige Software
- [TeXstudio](https://www.texstudio.org/) = Compiler & IDE

#### installiere Updates
- Starte MiKTeX Console
![0](./0.png)
- Drücke auf "Check for Updates" und folge den Anweisungen auf den Screenshots
![1](./1.png)
- Nachdem Updates gefunden wurden können diese bei updates installiert werden
![2](./2.png)
![3](./3.png)

#### Konfiguration
###### um ein Glossar erstellen zu können:
- [installiere Perl](https://www.activestate.com/products/perl/downloads/) mit CMD auf Windows
```cmd
powershell -Command "& $([scriptblock]::Create((New-Object Net.WebClient).DownloadString('https://platform.activestate.com/dl/cli/w20598w01/install.ps1'))) -activate-default ActiveState/Perl-5.32"
```
- manuelles erstellen des Glossars
![4](./4.png)
- automatisches erstellen des Glossars beim Kompelier Vorgang
*Diese Einstellung sollte nicht notwendig sein, aber falls das Glossar nicht erstellt wird siehe Screenshot.*
![5](./5.png)

###### um ein Literaturverzeichnis erstellen zu können:
![11](./11.png)

#### IDE starten & LaTex Datei kompelieren
- Starte TeXstudio
- Öffne "rootOfProject.tex"
- Drücke F5 oder drücke auf den grünen Play Pfeil

#### hilfreiche Links
- [Geometry Hilfe](https://www.namsu.de/Extra/pakete/Geometry.html)
- [Tabellen erstellen Hilfe](https://www.tablesgenerator.com/)

## Wie verwende ich:
#### Abkürzungsverzeichnis / Acronyme
![6](./6%20-%20acronym.png)
#### Abbildungsverzeichnis / List of Figures
![7](./7%20-%20List%20of%20Figures.png)
#### Tabellenverzeichnis / List of tables
![8](./8%20-%20List%20of%20tables.png)
#### Glossar
![9](./9%20-%20Glossary.png)
#### Literatur
![10](./10%20-%20Literature.png)
