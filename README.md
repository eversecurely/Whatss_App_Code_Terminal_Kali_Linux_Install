# Whatss_App_Code_Terminal_Kali_Linux_Install
Install_Whatsapp_Kali_Linux

# Schritt 1: WhatsApp Desktop herunterladen
wget https://github.com/Aluxian/WhatsApp-Desktop/releases/download/v2.2130.9/WhatsApp-linux-2.2130.9.zip

# Schritt 2: WhatsApp Desktop entpacken
unzip WhatsApp-linux-2.2130.9.zip

# Schritt 3: WhatsApp Desktop in den gewünschten Ordner verschieben
mv WhatsApp-linux-2.2130.9 ~/whatsapp

# Schritt 4: Startmenü-Icon erstellen
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

Viel Spass
