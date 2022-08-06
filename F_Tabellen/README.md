# HTML-Tabellen

Tabellen werden durch das "table" Tag begonnen und durch dieses beendet. Mit "tr" wird eine neue Tabellenreihe begonnen, "th" definiert einen Tabellenkopf (Zeilen bzw. Spalten Kopf), "td" geben die Inhalte der Tabellenzellen an. "caption" legt den Tabellentitel bzw. die Tabellenüberschrift fest -> muss das erste Element direkt hinter dem einleitenden "table" Tag sein. Formatierung der Tabelle, Reihen, Zellen und Titel werden über CSS gesteuert. 

Man kann eine Tabelle in einen Kopfbereich, einen oder mehrere Datenbereiche und einen Fußbereich aufteilen. Der Kopfbereich wird mit "thead" ausgezeichnet, er sollte eine oder mehrere Zeilen der Tabelle enthalten. Wollen Sie einen Fußbereich verwenden, so wird dieser mit dem "tfoot Element vor dem Tabellenkörper Element angegeben, er
sollte eine oder mehrere Zeilen der Tabelle enthalten. Sie dürfen einen oder mehrere Tabellenkörper Bereiche mit dem "tbody" Element definieren, in ihm notieren Sie den Datenbereich mit einer oder mehreren Tabellenzeilen. Die Verwendung von "thead", "tfoot" und "tbody" ist optional und hat keine sichtbare Wirkung. Pro Tabelle darf nur ein Kopf und ein Fuß aber mehrere Tabellenkörper definiert werden. 

Genauso wie man per Tabellenkopf, körper und fuß eine horizontale Gruppierung vornehmen können, kann man dies auch vertikal mit einzelnen Spalten ("col") oder Gruppen von Spalten ("colgroup") machen, "col" und "colgroup" müssen vor allen Elementen  "thead", "tfoot" und "tbody" sowie "tr" stehen. 

Mit den Attributen colspan und rowspan der Elemente "colspan" bzw. "td" geben Sie an, wie viele Zellen in vertikaler bzw. horizontaler Richtung zu einer einzigen Zelle
zusammengeführt werden sollen.


## Beispiel

![image](https://user-images.githubusercontent.com/63674539/183226414-906c15af-ddca-4461-89a4-87727c37c56c.png)

![image](https://user-images.githubusercontent.com/63674539/183226420-63dd94c4-61e9-4da8-9222-0ce727e69054.png)
