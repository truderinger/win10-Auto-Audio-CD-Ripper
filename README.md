Hallo,

hier zeige ich wie ein einfacher Audio-Musik-Server mit CD-Rip-Funktion zu realisieren ist. Die Frage stellte sich, eine Ausführung in Linux oder Windows. Linux kann mit Preempt-Kernel (Echtzeit) installiert werden. Jedoch hatte ich mit UDEV und einem Script für den Autostart von "abcde" (Der CD-Ripper für Linux) Probleme. Daher zuerst mal in der Windowsversion.  Für mich war es nicht nötig einen DAC in den Server einzubauen, da ich einen über USB laufenden DAC nutze. Auch wichtig war, dass ich den Server am Gehäuse einschalte und dieser dann in die Automatic-CD-Rip-Funktion (CD in Schublade, wird ausgelesen und wirft die CD wieder aus) geht. Nach Nutzung wieder auf den Gehäuseschalter und der Server fährt runter.

Was ist für die Hard- und Software nötig?

>Bestücktes Motherboard (bei mir: Mini-ATX Asrock J4105 mit 8 GB und 2TB SSD, sowie ein CD/DVD-Schubladen-Laufwerk). 
 Bitte beachten, dass Slotin-Laufwerk sehr oft die Audio-CD aufgrund deren mechanischen Beschaffenheit verkratzen. 
 Auch ist ein externes USB Laufwerk möglich. Ich hatte noch Restbestände und musste nur noch ein Alugehäuse wg. der optischen
 Gründe kaufe.

>Für die Software wird z.B. Win10-PRO, dbpoweramp und z.B. Twonky-Server benötigt. Win-PRO wegen RDP für die Einrichtung
 und die Netzwerkzugriffsmöglichkeit. Ich habe mir ein Billigst-Version von der Bucht geholt. 
 dbpoweramp: 	https://www.dbpoweramp.com/cd-ripper.htm
 Twonky-Server: https://www.lynxtechnology.com/twonky-server?msclkid=f5a266d1a6ca11ecb45ffec005fc0cb0
 Kosten ca. € 100

 Win10: Installieren des WinOS, alles updaten, Autologin einrichten, Energiesparbetrieb für Sperrbildschirm und
 	HDD/SSD ausschalten
        Sinn ist, dass ich ohne Monitor, Maus und Tastatur bei längerer Nichtnutzung zugreifen kann ohne dass ich ein Passwort
        eingeben muss. Geben Sie für das Netzwerk einen Ordner für die späteren Musikdaten frei. Ich nutze z.B "media"

dbpoweramp: Vorab kann eine bestimmte Zeit ohne Lizenz getestet werden. Ich habe mir die Privat-Lizenz geholt (Kosten: ca. € 40). 
		dbpoweramp-Software CD-Ripper installieren, im Anschluss dann das kostenfreie "CD-Ripp batch", ebenfalls von dbpoweramp
		installieren. Die Datei "CD-Ripper batch" in den Autostartordner mit Link einfügen (Win+R und mit „shell:startup“). Eigenschaften 		  vom Link aufrufen und nach nach den Gänsefüsschen der "...batch.exe" -autorip einfügen. 

Twonky-Server: Installation ist einfach und erklärt sich von selbst. Bitte Ordner nutzen, der bei Schritt Win10-Installation 
	       gewählt wurde.   
	       
Für dieie Schritte der Konfiguartation für den CD-Ripper und CD-Ripper-batch bitte selbst sorgen.
