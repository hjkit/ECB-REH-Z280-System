# RS232Adapter
Das CPU280-Board sollte mit einem 20-poliger Wannenstecker für die serielle Schnittstelle bestückt werden.
Unglücklicherweise ist die Pinbelegung nicht so ausgeführt das man direkt Flachbandkabel mit 9-poligen angepressten D-SUB-Buchsen verwenden kann.

Man muß ein Kabel für die serielle Verbindung löten. Die Verbindung muss wie folgt aussehen.

![RS232Cable](images/RS232Cable.png)

### Alternative Serielle Verbindung

Da solche gelöteten Kabelverbindungen immer wieder zu Problemen führen, vor allem wenn das CPU-Board im Test häufig umkonfiguriert wird, habe ich eine Alternative entwickelt bei der man mit Hilfe eines Adapters eine stabile angepresste Flachbandkabelverbindung nutzt.

Auf der eine Seite eines 20-poligen Flachbandkabels wird ein 20-poliger Pfostenstecker anpresst.
Auf der anderen Seite wird das Kabel aufgesplittet in zwei 10-polige Stänge.\
Der erste Draht eines jeden 10-poligen Strangs, von PIN 1 des 20-poligen Steckers aus gezählt, wird nicht benutzt und kann abgekniffen werden (siehe Bild).

An die verbleibenden 9 Drähte des Flachbandkabelstrangs wird eine 9-poliger D-SUB-Buchse angepresst. Das kann aber auch nach Bedarf ein 9-poliger D-SUB-Stecker sein.

Die folgenden Bilder zeigen den Aufbau.

![AdapterTopView](images/SerAdapterTopView1.png)<br>
Blick auf den Adapter

![AdapterBottomView](images/SerAdapterBottom2.png)<br>
Blick von unten

![AdapterSideView](images/SerAdapterSide3.png)<br>
Blick von der Seite

![AdapterOnBoard](images/SerAdapterOnBoard4.png)<br>
Adapter ins CPU-Board eingesteckt

![D-SUBConnector](images/SerCable5.png)<br>
Die angepressten D-SUB Buchsen. **Bitte den grünen, nicht benutzten Draht beachten**

![Board with Serial Cable](images/Board+Cable.png)<br>
CPU-Board mit seriellem Kabel
