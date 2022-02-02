# tarent-manjaro

Alternative zum tarent Ubuntu 



Todos aus offiziellem Dokument:

Titel                                                                        | Ticket vorhanden? 
|:----------------------------------------------------------------------------|--------------------:|
Festplatten partitionieren: Geführt - gesamte Platte mit verschlüsseltem LVM | X 
Hostname config: 
    ```
    editiere: /etc/hostname → nb-bn-123
    editiere: /etc/hosts → nb-bn-123.lan.tarent.de nb-bn-123
    editiere: /etc/mailname → nb-bn-123.lan.tarent.de
    ```
    | dsad 
Dem Benutzer sind lokale sudo-Rechte zu vergeben. (benötigt root-User) | 
Sicherstellen, dass /home/$user da ist | 
Festplattenpasswort austauschen: 
    ```
    Befehl: cryptsetup luksAddKey /dev/verschlüsseltePartition
    Neues Passwort durch Abfrage des alten Passwortes hinzufügen
    Befehl: cryptsetup luksDelKey /dev/verschlüsseltePartition
    Altes Passwort entfernen
    ```
    |
Standardsoftware installieren (Mozilla Firefox, Google Chrome bzw. Chromium, RocketChat, LibreOffice, Thunderbird | 
WLAN mit tarent Zertifikat installiert | 


