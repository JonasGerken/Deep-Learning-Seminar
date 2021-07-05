# Deep-Learning-Seminar

Für das Projekt "Detect user emotions based on social networks" wird das Programm sklearn und jupyter lab verwendet. 
Sklearn ist eine Software-Bibliothek zum maschinellen Lernen für die Programmiersprache Python. Mit diesem Befehl 
pip install numpy pandas sklearn wird über die Windows Console sklearn installiert.
Die pandas Programmbiblithek für Python wird verwendet, um die Daten zu Verwalten und zu analysieren.

JupyterLab ist eine webbasierte interaktive Entwicklungsumgebung für Jupyter-Notebooks, -Code und -Daten. JupyterLab muss zunächst über die Website heruntergeladen und installiert werden und kann dann über den Speicherort ausgeführt werden C:\Users\DataFlair\jupyter lab.

Dieses Python-Projekt zur Erkennung von Emotionen befasst sich mit verschiedenen Emotionen, die in Social Media Netzwerken auftreten können. Mit sklearn wird ein TfidfVectorizer auf unserem Datensatz erstellt. Dann wird ein PassiveAggressive Classifier initialisiert und dann wird das Modell angepasst. Am Ende sagt ein Genauigkeitswert und eine Confusion Matrix an, wie gut das Modell ist.

Was ist ein TfidfVectorizer?
TF (Begriffshäufigkeit): Die Häufigkeit, mit der ein Wort in einem Dokument vorkommt, ist seine Begriffshäufigkeit. Ein höherer Wert bedeutet, dass ein Begriff häufiger vorkommt als andere. Daher ist das Dokument eine gute Übereinstimmung, wenn der Begriff Teil der Suchbegriffe ist.
IDF (Inverse Document Frequency): Wörter, die in einem Dokument häufig vorkommen, aber auch in vielen anderen häufig vorkommen, können irrelevant sein. IDF ist ein Maß dafür, wie wichtig ein Begriff im gesamten Dataset (Korpus) ist.
Der TfidfVectorizer konvertiert eine Sammlung von Rohdokumenten in eine Matrix von TF-IDF-Funktionen.

Was ist ein PassiveAggressiveClassifier?
Passive Aggressive Algorithmen sind Online-Lernalgorithmen. Ein solcher Algorithmus bleibt für ein korrektes Klassifizierungsergebnis passiv und wird im Falle einer Fehlberechnung, Aktualisierung und Anpassung aggressiv. Im Gegensatz zu den meisten anderen Algorithmen konvergiert er nicht. Sein Zweck besteht darin, Aktualisierungen vorzunehmen, die den Verlust korrigieren und eine sehr geringe Änderung der Norm des Gewichtsvektors bewirken.

In eine Exel Tabelle wird ein Dataset mit verschiedenen Texten (1.Spalte) und deren Zugehörige Emotion, wie happy, neutral und sad (2. Spalte) erstellt. Das Dataset wird in einer .csv Datei gespeichert.
