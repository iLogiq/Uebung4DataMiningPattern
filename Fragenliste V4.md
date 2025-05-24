## Versuch 4 - Naive Bayes

1. Wie wird ein Naive Bayes Classifier trainiert? Was muss beim Training für die spätere Klassifikation abgespeichert werden?

(Siehe ipynb (Versuch_DocumentClassification(1).ipynb))

2. Wie teilt ein Naiver Bayes Classifier ein neues Dokument ein? 

(Siehe ipynb (Versuch_DocumentClassification(1).ipynb))

3. Welche naive Annahme liegt dem Bayes Classifier zugrunde? Ist diese Annahme im Fall der Dokumentklassifikation tatsächlich gegeben? 

(Siehe ipynb (Versuch_DocumentClassification(1).ipynb))

4. \[Bild von Formeln des Naive Bayes Classifiers\] Betrachten Sie die Formeln für die Berechnung von 𝑃(𝐺|𝐷) und 𝑃(𝐵|𝐷). Welches Problem stellt sich ein, wenn in der Menge 𝑊(𝐷) ein Wort vorkommt, das nicht in den Trainingsdaten der Kategorie 𝐺 vorkommt und ein anderes Wort aus 𝑊(𝐷) nicht in den Trainingsdaten der Kategorie 𝐵 enthalten ist? Wie könnte dieses Problem gelöst werden?
(Siehe ipynb (Versuch_DocumentClassification(1).ipynb))

(Siehe ipynb (Versuch_DocumentClassification(1).ipynb))

5. \[Code einer einfachen `getwords()`\-Methode\] 

Wie könnte die Klassifikationsgüte durch Modifikation der `getwords()`\-Methode verbessert werden?
Siehe

(Siehe ipynb (Versuch_DocumentClassification(1).ipynb)) -> Siehe ganz unten

6. \[Bild der bedingten Wahrscheinlichkeiten und a-priori Wahrscheinlichkeiten\] 

Für einen Beispielsatz erhalten Sie die bedingten sowie die a-priori Wahrscheinlichkeiten. Berechnen Sie für die gegebenen Wahrscheinlichkeiten die dazu gehörige Klasse?
(Siehe ipynb (Versuch_DocumentClassification(1).ipynb)) -> Siehe Test Abteil

7. \[Bild einer Confusion Matrix\] Gegeben ist ein Bild einer Confusion Matrix. Berechnen Sie für die gegebenen Werte die Accuracy (Recall, Precision). Schreiben Sie dafür erst die Formel auf und berechnen Sie diese dann.
(Siehe ipynb (Versuch_DocumentClassification(1).ipynb)) -> Letze Aufgabe

8. Beschreiben Sie in Worten was die Accuracy-Metrik (oder Recall und Precision) aussagt bzw. wie diese zu interpretieren ist?
- Accuracy misst den Anteil korrekt klassifizierter Beispiele an allen Beispielen.
- Precision ist der Anteil korrekt positiver Vorhersagen an allen positiven Vorhersagen.
- Recall ist der Anteil korrekt positiver Vorhersagen an allen tatsächlich positiven Fällen.
- F1 Score: Der F1-Score fasst Precision und Recall zu einer Zahl zusammen und misst so die Balance zwischen Genauigkeit und Vollständigkeit bzw. es ist eine Bewertung wie gut ein Modell ist.