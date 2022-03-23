# Dash Dashboards

Nachfolgend werden alle nötigen Schritte beschrieben, um dieses Projekt mit Beispiel-Dashboards nutzen zu können.

Zu Beginn soll wieder eine virtuelle Umgebung angelegt werden. Dies geschieht im Terminal mit folgendem Befehl:

```python
python -m venv DashboardEnv
```
Danach sollte ein Ordner mit dem Namen __DashboardEnv__, in dem die virtuelle Umgebung gespeichert wird. Um nicht alle Files der Virtuellen Umgebung mit in Github speichern zu müssen, kann eine Datei erzeugt werden, die genau dies verhindert. 

Erstellen Sie die Datei ".gitignore" in Ihrem Projekt. In diese Datei schreiben sie folgden Text:
```
DashboardEnv/
```
und speichern danach die Datei über STRG+s ab. Dadurch wird Git vermittelt, den Ordner DashboardEnv beim Upload zu github nicht zu beachten. 

Wählen Sie nun in der Zeile oben am Bildschirmrand das Feld __Anzeigen__ aus und danach die __Befehlspalette__. In dem Feld sollte nun eine Eingabe möglich sein. Geben Sie dort "Interpreter" ein und wählen Sie diesen aus (siehe folgende Bilder)
![Select Interpreter](images/interpreter.png) 
Danach wählen Sie den Python Interpreter mit Ihrer virtuellen Umgebung "DashboardEnv" aus.
![Select Environment](images/DashEnv.png)

Wenn Sie ihre virtuelle Umgebung ausgewählt haben, sollten Sie im unteren Rechten Eck folgendes sehen:

![Env Activated](images/activated.png)

Danach können Sie mit der Installation des "requirements.txt"-Files beginnen. Dafür geben Sie folgenden Code in das Termin ein:
``` python
pip install -r requirements.txt
```

Danach sollten alle packages installiert sein und die python Datei "BarChart.py" ist ausführbar. Im Terminal wird Ihnen nach dem Ausführen eine https- Adresse ausgegeben, welche Sie mit STRG + "Click" in ihrem Browser öffnen können. 

Sehen Sie sich nun auch die anderen Besipiele an, um einen ersten Eindruck der Möglichkeiten von Dash in Python zu bekommen. 


