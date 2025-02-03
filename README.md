# Übung zu Python und Flask

In dieser Übung soll ein einfacher Webserver mit Python und Flask implementiert werden. Dabei soll ein kleiner "Webshop" entstehen, der eine Liste von Produkten anzeigt und die Möglichkeit bietet, diese im Detail zu betrachten.

## Vorbereitung

Klonen Sie dieses Repository mit 

    git clone https://github.com/fhgr-stud/pro2-flask-uebung-webshop.git

## Aufgabenstellung

Implementieren Sie zwei Funktionen in der Datei `shop.py` - Sie finden dort Anweisungen in den Kommentaren (mit TODO markiert). Die Funktionen sollen die folgenden Aufgaben erfüllen:

- `home` zeigt das Template `home.html` an. Dieses Template soll eine Liste von Produkten anzeigen. Die Liste soll aus dem Dictionaty `produkte` kommen, das in der Datei `shop.py` definiert ist. Die Liste soll den Namen und den Preis der Produkte enthalten. Der Name soll ein Link sein, der auf die Detailseite des Produkts verweist.

- `details(id)` zeigt das Template `details.html` an. Dieses Template soll die Details eines Produkts mit der Nummer `id` anzeigen. Die Details sollen aus dem Dictionary `produkte` kommen, das in der Datei `shop.py` definiert ist. Die Details sollen den Namen, den Preis und ein Bild des Produkts enthalten. Falls die Nummer `id` nicht existiert, soll eine Fehlermeldung angezeigt werden und der Status Code 404 zurückgegeben werden.

Darüber hinaus müssen Sie die Templates `home.html` und `details.html` ergänzen. Sie finden dort Anweisungen in den Kommentaren (mit TODO markiert).

## Bonusaufgaben

- Fügen Sie dem Projekt eine weitere Route hinzu, über welche es möglich wird, dem Shop weitere Produkte hinzuzufügen.
- Ermöglichen Sie es, Produkte aus dem Shop zu löschen.
- Fügen Sie eine Route hinzu, welche es erlaubt Produkte zu bearbeiten.
