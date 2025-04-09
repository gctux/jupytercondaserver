# Installation von Debian Trixie

## Inhaltsverzeichnis


- [Grundinstallation](#grundinstallation)
- [Systembenutzer](#systembenutzer)

## Grundinstallation

Von Debian Trixie (derzeit Testing Variante von Debian) soll ein minimales Kommandozeilensystem mit ssh-Server installiert werden. Der Installationsdatenträger (debian-testing-amd64-netinst.iso) kann hier: https://cdimage.debian.org/cdimage/weekly-builds/amd64/iso-cd/ heruntergeladen werden.

Eine Schnell-Installationsanleitung für Debian findet man hier: https://wiki.debian.org/de/QuickInstall.


## Systembenutzer

Beim Punkt tasksel wählt man nur das Basissystem und den ssh-Server aus. Während der Installation wurde bei mir der Nutzer Adminuser (adminuser) angelegt, der später die Nutzerverwaltung administrieren soll. Deshalb soll er mit dem Programm sudo auch zum Administrator gemacht werden können.

### Erste Anmeldung

Wenn man direkt vor dem Rechner sitzt kann man sich direkt anmelden, z.B mit dem Nutzernamen "adminuser" und dem Passwort "passwort". Es ist aber auch möglich, sich von der Windows-Powersshell aus per ssh anzumelden:

**Powershell:**

```
C:\Users\user> ssh adminuser@jupyterserver
```

Nach der Anmeldung sieht man das Linuxprompt:

```
adminuser@jupyterserver:~$
```
Um Administratorrechte zu erlangen gibt man jetzt das Komando su ein. Danach wird man nach dem root-Passwort gefragt. Nach Eingabe dieses Passworts besitzt man Administraorrechte:
```
adminuser@jupyterserver:~$ su
Passwort:
root@jupyterserver:/home/adminuser#
```


