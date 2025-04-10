# Einrichten eines Jupyterhubservers auf der Basis von Debian Trixie und Conda

Dieses Github-Projekt beschreibt, wie man einen Jupyterhubserver auf der Basis von Debian Trixie und Conda für ein schulisches Intranet einrichten kann. Der Server soll eine Benutzerauthentifizierung besitzen, so dass jeder Schüler seine eigene Jupyterlabumgebung vorfindet. Der Adminuser kann Nutzer im Linuxsystem automatisch mit Hilfe von Shellscripten anlegen. Es ist mit Shellscripten auch möglich, Dateien in die Nutzerverzeichnisse zu verteilen bzw. sie wieder einzusammeln. Weiterhin soll es möglich sein, für alle Nutzer zusätzliche Pytthonpakete (z.B. ipycanvas, matplotlib ...) installieren.

Bei der Linuxdistribution viel die Wahl auf resourcenschonendes Komandozeilensystem auf der Basis von Debian Trixie. Conda wurde als systemweite Pythonumgebung konfiguriert, weil es so möglich ist, pip-Pakete für alle Nutzer zu installieren. Als Hardware dient derzeit ein Lenovo Thinkpad E470 von 2017 (Intel(R) Core(TM) i5-7200U CPU @ 2.5 GHz, 8 GB RAM). Dieser Rechner reicht für ein Computerkabinet völlig aus.



[Schritt 1: Installation von Debian Trixie](01_InstallDebianTrixie.md)
[Schritt 2: Installation von Conda](02_InstallConda.md)
