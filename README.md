# Whatss_App_Code_Terminal_Kali_Linux_Install
Install_Whatsapp_Kali_Linux

# Schritt 1: WhatsApp Desktop herunterladen

Führe den Befehl sudo apt update aus, um die Paketliste zu aktualisieren.

Führe den Befehl sudo apt install snapd aus, um Snapd zu installieren, falls es noch nicht installiert ist.

Nachdem die Installation abgeschlossen ist, kannst du den Befehl snap version ausführen, um zu überprüfen, ob Snapd erfolgreich installiert wurde.

Sobald Snapd installiert ist, kannst du WhatsApp for Linux mit dem Befehl sudo snap install whatsapp-for-linux installieren. Stelle sicher, dass du während der Installation mit dem Internet verbunden bist.

wget https://github.com/Aluxian/WhatsApp-Desktop/releases/download/v2.2130.9/WhatsApp-linux-2.2130.9.zip

# Schritt 2: WhatsApp Desktop entpacken
unzip WhatsApp-linux-2.2130.9.zip

# Schritt 3: WhatsApp Desktop in den gewünschten Ordner verschieben
mv WhatsApp-linux-2.2130.9 ~/whatsapp

# Schritt 4: Startmenü-Icon erstellen)(für die Taskleiste bitte)
(speichern als whatsapp.desktop)
echo "[Desktop Entry]
Version=1.0
Name=WhatsApp
Comment=WhatsApp Desktop
Exec=/home/<dein_benutzername>/whatsapp/WhatsApp
Icon=/home/<dein_benutzername>/whatsapp/WhatsApp-linux-2.2130.9/resources/app/icon.png
Terminal=false
Type=Application
Categories=Network;InstantMessaging;" > ~/.local/share/applications/whatsapp.desktop

# Schritt 5: WhatsApp starten
/home/<dein_benutzername>/whatsapp/WhatsApp

Easy und alles ist auch als Symbol auf der Taskleiste .

Hier noch mal alles:
Öffne das Terminal. Du kannst das Terminal normalerweise über die Anwendung "Terminal" oder durch Drücken von "Strg + Alt + T" öffnen.

Aktualisiere die Paketliste, um sicherzustellen, dass du die neuesten verfügbaren Pakete erhältst. Gib den folgenden Befehl ein und drücke die Eingabetaste:

sql

sudo apt update

Dieser Befehl lädt die neuesten Informationen zu den verfügbaren Paketen aus den Paketquellen herunter.

Installiere Snapd, das Paketverwaltungssystem für Snaps, falls es noch nicht installiert ist. Gib den folgenden Befehl ein und drücke die Eingabetaste:

sudo apt install snapd

Snapd ermöglicht die Installation von Softwarepaketen, wie zum Beispiel WhatsApp for Linux.

Überprüfe, ob Snapd erfolgreich installiert wurde, indem du den Befehl snap version ausführst. Dieser Befehl zeigt die aktuelle Version von Snapd an. Falls keine Fehlermeldung angezeigt wird, ist Snapd ordnungsgemäß installiert.

Installiere WhatsApp for Linux, indem du den folgenden Befehl eingibst und die Eingabetaste drückst:
    sudo snap install whatsapp-for-linux
    
   Dieser Befehl lädt und installiert die WhatsApp for Linux Anwendung über Snap.

   Stelle sicher, dass du während der Installation mit dem Internet verbunden bist, da Snap die erforderlichen Dateien aus dem Internet herunterlädt.

   Nach Abschluss der Installation kannst du WhatsApp for Linux in der Anwendungsliste deines Betriebssystems finden und ausführen. Du kannst entweder nach "WhatsApp" suchen oder das WhatsApp for Linux Symbol anklicken, um die Anwendung zu starten.

Das war's! Du hast WhatsApp for Linux erfolgreich installiert und kannst es nun verwenden, um mit deinen Kontakten zu chatten.

Viel Spass
