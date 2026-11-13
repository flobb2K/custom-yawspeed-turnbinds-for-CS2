# flobb's Turnbinds
# Turnbinds mit anpassbaren Turnspeeds für CS2/CSGO

Diese Config nutzt einen Workaround, um die alten Convars `cl_yawspeed` und `cl_pitchspeed` aus ***Counter-Strike: Source*** auch in dem neuen Game ***Counter-Strike 2*** und dessen Vorgänger ***Counter-Strike: Global Offensive*** verfügbar zu machen – <ins>ausschließlich mit Konsolenbefehlen</ins>, wie in guten alten Zeiten.  
Zusätzlich bietet sie eine Vielzahl <ins>verschiedener Binds und Anpassungsmöglichkeiten</ins>, die die volle Nutzung dieser verloren geglaubten, aber nicht vergessenen Konsolenbefehle ermöglichen.

## Features:
### cl_yawspeed
Mit dieser Config kann man ***yawspeed ändern***, indem man `cl_yawspeed_[Wert]` in die <ins>Entwicklerkonsole</ins> eingibt.
>[!IMPORTANT]
>`cl_yawspeed` kann jeden Wert von 1 bis 300 annehmen. Nur ganze Zahlen sind erlaubt!

### cl_pitchspeed
Mit dieser Config kann man ***pitchspeed ändern***, indem man `cl_pitchspeed_[Wert]` in die <ins>Entwicklerkonsole</ins> eingibt.
>[!IMPORTANT]
>`cl_pitchspeed` kann jeden Wert von 1 bis 45 annehmen. Nur ganze Zahlen sind erlaubt!

### Feste Binds
Belege so viele Tasten mit verschiedenen cl_yawspeed-/cl_pitchspeed-Befehlen, wie du willst!  

`bind "[Taste]" "cl_yawspeed_[Wert]"`  
`bind "[Taste]" "cl_pitchspeed_[Wert]"`

### Toggle/Cycle Binds
- ***Wechsle zwischen*** zwei, drei oder vier verschiedenen `cl_yawspeed` Werte mit <ins>einer einzigen Taste</ins>.
- ***Wechsle zwischen*** zwei oder drei verschiedenen `cl_pitchspeed` Werte mit <ins>einer einzigen Taste</ins>.
- ***Feste Binds können mit den Toggle/Cycle Binds gekoppelt werden***, damit sie ebenfalls den Cycle-Alias beeinflussen.
- Option, den `cl_yawspeed` Cycle-Alias ***zusammen mit der Stage/dem Run zurückzusetzen***.

### Hold-to-Activate Binds
***Hold-to-Activate-Binds*** <ins>müssen gehalten werden</ins>, um den `cl_yawspeed` Wert zu ändern.
<ins>Wird keine dieser Tasten gehalten bzw. losgelassen</ins>, wird eine ***vorher festgelegter*** `cl_yawspeed` Wert aktiviert.
Diese Config unterstützt ***bis zu drei Hold-to-Activate Binds***, die zusammen insgesamt vier verschiedene `cl_yawspeed` Werte ermöglichen.
>[!WARNING]
>Diese Art von Bind ***funktioniert nicht zusammen mit Festen oder Toggle/Cycle Binds***!

### Visuelles Feedback
- Wechsel der ***HUD-Farbe***
- Wechsel der ***Fadenkreuzfarbe***
- Wechsel von ***sowohl HUD- als auch Fadenkreuzfarbe***
- 9 verschiedene Farben für alle oben genannten Optionen
>[!NOTE]
>Die in der config enthaltenen Befehle für die Fadenkreuzfarbe **funktionieren nicht in CS:GO***!

### Soundeffekte
- ***Soundeffekte bei Betätigung der Binds***
- 21 verschiedene Sounds

### Gute Nachvollziehbarkeit
Der Sinn und Zweck jeder Config-Datei wird kurz und knapp erklärt. Ich halte hier nichts geheim. Außerdem habe ich Wert darauf gelegt, dass alles ***gut verständlich*** ist.

### Ganz nach deinem Geschmack!
Mithilfe der Config-Datei `turnbinds\settings.cfg` kannst du im Handumdrehen ***die richtigen Einstellungen für dich*** zu finden.
Erfahrene Nutzer, die selbst Features hinzufügen möchten, sollten unbedingt einen Blick in die Datei `turnbinds\setup\setup.cfg` werfen.

## Installationsanleitung:
1. Lade die `.zip`-Datei mit den Config-Dateien herunter. (rechte Seite unter „Releases“)
2. Entpacke alle Dateien aus dem `.zip`-Archiv.
3. Verschiebe den Ordner `turnbinds` inklusive seinem gesamten Inhalt nach
   `[Laufwerk]:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
4. Richte die Config mithilfe der `settings.cfg` im Ordner `turnbinds` ein.
5. Um die Config auszuführen, gib `exec turnbinds\exec.cfg` in die Entwicklerkonsole ein. Der Screenshot zeigt, wie es danach aussehen könnte.
6. Du kannst `exec turnbinds\exec.cfg` auch in deine `autoexec.cfg` einfügen.
<img width="2040" height="1440" alt="20261105122006_1" src="https://github.com/user-attachments/assets/eb13515b-b6db-443e-acdf-5f1b239f2249" />

>[!NOTE]
>Die Konsole zeigt beim Start von Counter-Strike 2 den Bestätigungstext nicht an, wenn du die Config über die autoexec ausführst.

## Wie schlägt sich diese Config im Vergleich mit externer Turnbind-Software?
### Die Vorteile
- deutlich mehr Möglichkeiten um Binds zu erstellen
- visuelles Feedback
- Soundeffekte
- Einstellungen können über Entwicklerkonsole geändert werden
- mit der Config wirst du niemals gebannt (funktioniert sogar bei FACEIT lol)

### Der Nachteil
Da cl_yawspeed/cl_pitchspeed im Spiel nicht tatsächlich als Convars existieren, können sie durch diese Config lediglich „emuliert“ werden. Das wird durch Modifikation der Befehle turnleft/turnright bzw. turnup/turndown erreicht. Der negative Effekt dabei ist, dass die Drehgeschwindigkeit nicht direkt verändert wird. Das hat zur Folge, dass man ganz kurz aufhören muss seine Turnbinds zu verwenden, um die Drehgeschwindigkeit zu ändern.

## Besonderer Dank gilt INSPECTRO von Cybershoke, der mir dabei geholfen hat, diese Config zu erstellen.
<img width="4100" height="475" alt="banner_shoke_anthrazit" src="https://github.com/user-attachments/assets/01df9424-7de2-40b0-8295-f4221597aebe" />
Wenn du in CS2 surfen möchtest, empfehle ich dir dringend, das auf den Servern von Cybershoke zu tun. Diese haben eine umfassende Liste an Features zu bieten und ganz im Gegensatz zu anderen Serveranbietern werden diese ausgiebig getestet. Außerdem sind die Server und Bestenlisten voll mit guten Spielern.

## Demnächst:
- Steam-Guide
