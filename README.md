# Ambisonics

**Ambisonics** (auch Ambisonic) ist ein Verfahren zur Aufnahme und Wiedergabe eines Klangfeldes. Diese Audiotechnologie wurde in den 1960er und 1970er Jahren in [Großbritannien](https://de.wikipedia.org/wiki/Vereinigtes_K%C3%B6nigreich) entwickelt und im Wesentlichen von [Michael A. Gerzon](https://de.wikipedia.org/wiki/Michael_Gerzon) und [Peter Fellgett](https://de.wikipedia.org/wiki/Peter_Fellgett) vorangetrieben. Im Unterschied zu den kanalorientierten Übertragungsverfahren ist für die Wiedergabe keine feste Anzahl von Lautsprechern vorgegeben. Die jeweiligen Signale werden nach mathematischen Vorgaben aus den übertragenen Werten für Schalldruck- und Schallschnelle für jede einzelne Lautsprecherposition berechnet.

## Physikalisches Prinzip

In der Basisversion, bekannt als *First Order Ambisonics B-Format*, wird die Information in den Kanälen W, X, Y und Z übertragen. Dabei enthält W die reine [Schalldruckkomponente](https://de.wikipedia.org/wiki/Schalldruck), aufgenommen mit einem ungerichteten (Kugel)-Mikrofon. Die Signale X, Y und Z sind die [Druckgradientenkomponenten](https://de.wikipedia.org/wiki/Druckgradientenmikrophon) in den zugehörigen Raumachsen.

![equation](http://latex.codecogs.com/gif.latex?\large&space;{\displaystyle&space;W=1})

![equation](http://latex.codecogs.com/gif.latex?\large&space;{\displaystyle&space;X={\sqrt&space;{2}}\cos&space;\phi&space;})

![equation](http://latex.codecogs.com/gif.latex?\large&space;{\displaystyle&space;Y={\sqrt&space;{2}}\sin&space;\phi&space;})

Aufgenommen werden sie mit Mikrofonen, deren Acht-Charakteristik in der entsprechenden Achse ausgerichtet ist. Das Verfahren zielt darauf ab, beim Zuhörer aus diesen Signalen an seinem Abhörplatz wieder den aufgezeichneten Schalldruck mit dem zugehörigen Vektor der Schallschnelle zu rekonstruieren. Für eine rechteckige Lautsprecheranordnung in der horizontalen Ebene werden die einzelnen Lautsprechersignale aus den Winkeln zur Mittelachse abgeleitet:

![equation](http://latex.codecogs.com/gif.latex?\large&space;{\displaystyle&space;P_{n}=W&plus;X/({\sqrt&space;{2}}\cos&space;\theta&space;_{n})&plus;Y/({\sqrt&space;{2}}\sin&space;\theta&space;_{n})\,})

Die virtuellen Positionen der Schallquelle können aber nicht nur mit dem Soundfield-Mikrofon aufgenommen werden, ein Ambisonics-Coder kann das Monosignal an frei wählbaren Positionen im dreidimensionalen Schallfeld darstellen.

## Vorteile des Verfahrens

Ein Vorteil des Verfahrens ist, dass auch die Elevationsebene nach mathematischen Beziehungen für jede beliebige Lautsprecherposition dekodiert werden kann. Dadurch wird schon mit vier Übertragungskanälen ein dreidimensionales Schallfeld erzeugt. In diesem Schallfeld ist keine Raumachse bevorzugt, alle Lautsprecher tragen ihren Anteil bei. Herkömmliche Raumklang-Verfahren sind selbst bei sechs Übertragungskanälen noch zweidimensional.

Mit steigender Zahl der dekodierten Lautsprecherkanäle gewinnt das Schallfeld an Stabilität. Es kann dann sogar von Zuhörern außerhalb der Lautsprecheranordnung wahrgenommen werden. Die Lautsprecher müssen nicht an fest vorgegebenen Positionen in einem regulären Rechteck positioniert werden. Das erlaubt eine bessere Anpassung an die praktischen Wiedergabebedingungen.

Mit zusätzlichen Übertragungskanälen kann die Stabilität der räumlichen Abbildung weiter gesteigert werden. Dabei bleibt das Verfahren immer abwärtskompatibel. Es kann einfach auf die Dekodierung einzelner Kanäle verzichtet werden. Um eine Kompatibilität für die Wiedergabe auf Mono- und Stereosystemen zu gewährleisten, wurde die UHJ-Hierarchie entwickelt. Diese umfasst ein Format mit vier Kanälen, welches das gesamte B-Format abbildet, ein ausschließlich horizontales 3-Kanal-Format, ein 2½-Kanal-Format bei dem der dritte Kanal nur die halbe Bandbreite umfasst und ein 2-Kanal-Format. Schon mit zwei Übertragungskanälen ist es dabei möglich, eine horizontale Raumklang-Wiedergabe zu etablieren, wobei die Wiedergabe ohne Dekoder stereokompatibel bleibt. Heute wird UHJ in der Regel mit dem 2-Kanal-Format (eigentlich BHJ) gleichgesetzt.

Aufzeichnungen im Ambisonics-G-Format sind auf herkömmlichen Raumklang-Anlagen abspielbar. Der Dekoder wird dabei aufnahmeseitig in den Übertragungsweg geschaltet. Dabei wird eine Dekodierung auf die Standardpositionen üblicher Raumklang-Lautsprecher in Wohnräumen dekodiert. Die Vorzüge des Verfahrens werden dabei nur eingeschränkt genutzt. Zunehmend soll sich dieses Verfahren im Aufnahmebereich auch bei konventionellen Produktionen für eine verbesserte Raumabbildung durchsetzen.

## Verbleibende Probleme

Der Durchbruch des Verfahrens konnte bisher nicht gelingen; Ambisonics ist heute weitgehend unbekannt.

In größeren Wiedergaberäumen sind vier Lautsprecher in der Azimutebene für eine stabile Wiedergabe nicht ausreichend. Beim Zuhörer muss ein relativ hoher Direktschallanteil eintreffen, damit die Vorzüge des Verfahrens erkannt werden können.

## Forschung und Marktreife

Obwohl die meisten Patente auf das Verfahren inzwischen ausgelaufen sind, ist die Weiterentwicklung des Ansatzes weiterhin Gegenstand der Forschung.
Dabei werden vor allem die High Order Ambisonics (HOA)-Verfahren zu größerer Perfektion weiterentwickelt. Inzwischen sind diese Dekoder auf Softwarebasis implementierbar. Wie auch das verwandte Verfahren der Wellenfeldsynthese WFS, so hat Ambisonics möglicherweise Aussichten, die konventionellen kanalgebundenen Prozeduren abzulösen. Bis heute blieb jedoch der kommerzielle Erfolg des Systems aus.
