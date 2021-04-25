# Playbook

Erstellt von **Thomas Arend** am *2019-07-13*

# Kurzbeschreibung

Dieses Playbook-Verzeichnis enthält folgende Playbooks:

- pb_install.yaml: Installiert und Konfiguriert ein Debina-Linux auf der Basis einen minimalen debian mit *ssh* und *system-tools*.
-
Das Playbook enthält dazu folgende Rollen:

- ansible-compatible: Installiert fpr Ansible erforderliche Packete und Nutzer
- common: Installiert ein alles Host gemeinsames Grundsystem
- gre-tunnel: Intalliert GRE Tunnel zu anderen Rechnern
- mailserver: Installiert einen Mail-Server
- ntpserver: Richtet den Host als NTP-Server ein
- samba: Installiert und richtet Samba ein
- webserver: Richtet apache2 als Web-Server ein
- test: Test der Installation

**Näheres** zu den *Rollen* findest du **im README.md** im Verzeichnis *roles*.

Aufruf:

    ansible-playbook playbooks/pb_playbook.yaml

