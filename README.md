Dieses Projekt wurde als Abschlussprojekt im Rahmen einer Weiterbildung im Bereich Data Analytics erstellt. Ziel war es, einen beliebigen Datensatz auszuwählen und interessante Korrelationen zur Analyse zu finden. Ich habe zwei Datensätze ausgewählt, die sich auf Songs von Spotify beziehen: einen mit den Top 10.000 Songs von 1950 bis heute (Stand: Ende 2024) und einen weiteren, sehr umfangreichen Datensatz mit nahezu 1.000.000 Songs inklusive Songtexten.
<br>
Im ersten Teil der Datenanalyse habe ich die Datensätze bearbeitet, aufgeräumt, versucht, fehlende Daten zu beschaffen, Duplikate gelöscht und Datentypen angeglichen. Im zweiten Teil habe ich eine eine explorative Datenanalyse der Hits vorgenommen, um vor Allem die Entwicklung in den verschiedenen Zeiten und die Verteilung von Songeigenschaften wie Tempo, Tonarten und Songlänge zu bestimmen. Dann habe ich Gemeinsamkeiten und Unterschiede zwischen diesen Datensätzen anhand der Spotify-Attribute analysiert, um herauszufinden, was einen Hit-Song ausmacht. Zusätzlich habe ich die Datensätze kombiniert, um die Texte der Hit-Songs mit denen aller Songs zu vergleichen und zu untersuchen, was einen Hit-Song besonders macht, dann habe ich die Texte analysiert.
<br>
Im dritten Teil bin ich mit der Textanalyse leider nicht fertig geworden, da die große Menge an Songs in allen Textverarbeitungsschritten meinen privaten Computer überfordert. Ich habe jedoch eine Textanalyse der Hit-Songs vorgenommen und habe vor, die große Datei Stück für Stück auch noch zu analysieren.
<br>
Ergebnisse:
<br>
Die Analyse der Spotify-Features ergab, dass diese nicht sehr unterschiedlich sind. Es lässt sich jedoch beobachten, dass die Valence (Wert für Stimmung) eines Hit-Songs tendenziell höher ist. Weitere Attribute wie Danceability, Loudness und Energy sind ebenfalls bei den Hits höher, jedoch nur in einem sehr geringen Maße. Im Gegensatz dazu sind die Werte Speechiness, Acousticness, Instrumentalness und Liveness niedriger. Die Track-Dauer (etwa 2:30), das Tempo (rund 120 BPM) und die Lautstärke sind in beiden Datensätzen nahezu identisch. Die Hits sind noch stärker in Dur, als die Vergleichsgruppe, außerdem ist die Verteilung der Tonarten etwas unterschiedlich, jedoch nicht grundsätzlich anders. Hits sind noch stärker in C geschrieben, die vorherrschenden Tonarten sind jedoch bei beiden C und G und dann mit etwas Abstand D und A.
<br>
Songtexte:
<br>
Die Sentiment-Analyse zeigte, dass Hit-Songs überwiegend positive Texte enthalten.
<br>
Die Themenanalyse ergab, dass Hit-Songs häufig folgende Themen behandeln:
<br>
- Liebe (touch, feel, believe, tell, fall, forever)
- Gute Gefühle (life, good, think)
- Körperbezogenes (body, feel, need, want, somebody)
- Tanzen (dance, everybody, man, girl, hey)
Die für die Analyse verwendeten Dateien können hier heruntergeladen werden:
<br>
https://www.kaggle.com/datasets/joebeachcapital/top-10000-spotify-songs-1960-now
<br>
und hier
<br>
https://www.kaggle.com/datasets/bwandowando/spotify-songs-with-attributes-and-lyrics
<br>
<img width="1000" height="500" alt="wordcloud_3" src="https://github.com/user-attachments/assets/2fc11a3d-8225-48b8-9ba1-cb9746709944" />
