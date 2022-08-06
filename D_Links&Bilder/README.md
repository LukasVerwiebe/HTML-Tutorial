# HTML-Links & Bilder

Auf einer Webseite können Hyperlinks eingefügt werden, dazu wird das "a" Tag verwendet. Dieses dient als Verbindung zwischen zwei Dokumenten bzw. als Anker innerhalb eines Dokuments. Zwischen dem Tag dürfen Text und HTML.Konstrukte stehen. Das Attribut "href" bezeichnet eine URL, wohin an dieser Stelle verzweigt wird. Mit dem "target" Attribut des Tags können Sie veranlassen, dass das Verweisziel nicht im eigenen Fenster geöffnet wird sondern in einem anderen Fenster / Tab / Sidebar / eingebettetes Frame Fenster. Existiert kein Ziel mit dem entsprechenden Namen, so wird ein neues Browser Fenster geöffnet, das ab jetzt mit diesem Namen angesprochen wird. 

Zielnamen sind für besondere Aktionen in Verbindung mit Dokumenten reserviert. Dies sind:
- _blank: Wird target=_blank gesetzt, so wird ein Dokument immer in einem neuen, unbenannten Fenster geöffnet.
- _self: Lädt das Dokument in dem selben Fenster, in dem auch der Link aufgerufen wurde -> Standardwert.
- _parent: Lädt das Dokument in dem Fenster, in dem sich der Link befunden hat, der zur Darstellung des eigenen Dokuments geführt hat.
- _top: Lädt das Dokument in die oberste Fensterebene.

Für graphisch anspruchsvolle Dokumente werden Pixelgrafiken benötigt. Hierfür steht das "img" Tag zur Verfügung. In der Praxis unterstützen Browser die Formate GIF, JPEG und PNG. Die Grafik wird an der Stelle platziert, an der das Element notiert wird -> keine neue Zeile. Das "src" Attribut ist obligatorisch und enthält die URL des zu ladenden Bildes. Mit "height" und "width" können Sie ein Bild entsprechend skalieren. Das "alt" Attribut enthält den sogenannten Fallback Text, falls die Grafik nicht geladen oder nicht angezeigt werden kann.

## 1. ![image](https://user-images.githubusercontent.com/63674539/183225471-e416a624-bcfc-4599-869d-06642415d1b2.png)
Über diesen Link wird die Google Startseite in einem neuen Fenster geöffnet.

## 2. ![image](https://user-images.githubusercontent.com/63674539/183225558-98b6be7d-9551-4d1f-931d-c7d26615505a.png)
Über diesen Link wird ein Download einer hinterlegten Datei gestartet, die Datei erhält den Namen "Test".

## 3. ![image](https://user-images.githubusercontent.com/63674539/183225613-84742f0f-9f29-41c2-8235-1e1027d9112b.png)
Bei betätigung dieses Links wird das Standard Email Programm auf dem PC geöffnet und als Betreff die angegebe Emailadresse eingetragen. Über das Attribut "title" wird ein Text angezeigt wenn den Mauszeiger über den Link setzt. 

## 4. ![image](https://user-images.githubusercontent.com/63674539/183225749-0bcd0083-6a74-4224-aae3-f037d286da8c.png)
Mittels dieses "img" Tags wird ein Bild von einem Ordner aus aufgerufen.

## 5. ![image](https://user-images.githubusercontent.com/63674539/183225759-4b16af00-911e-4d3f-bd24-bd50579ab49d.png)
Mit diesem "img" Tag wird ein Bild von einer anderen Webseite abgerufen.

## 6. ![image](https://user-images.githubusercontent.com/63674539/183225769-fa4537ea-141b-4938-9a9d-2a857dd0743e.png)
Einem Hyperlink wurde ein "img" Tag hinzugefügt. Wenn auf das Bild geklickt wird, wird eine Webseite aufgerufen.

## Beispiel

![image](https://user-images.githubusercontent.com/63674539/183225066-2bffd5be-d501-4b68-8879-a5588e6f5f2d.png)

![image](https://user-images.githubusercontent.com/63674539/183225087-5b8c77ac-ade8-40ba-89e0-2644ea5f79c3.png)
