# Movie Review Analyzer
![Hello World](/images/mra-demo.png?raw=true "sample image")

[english text](#english)
## Deutsch
Der Movie Review Analyzer ist eine Webanwendung, die eine Filmkritik verarbeitet, und dann ermittelt ob es sich um eine positive oder negative Kritik handelt. Ein Liniendiagramm zeigt wie das jeweilige Wort zu der letztlichen Einordnung beigetragen hat. Wenn das Wort einen großen Durchmesser hat und höher gelegen ist, war es mit ausschlaggebend für die Klassifizierung.

### Hintergrund
Im Kaptiel 18 von [Deep Learning for Coders](http://tiny.cc/fastaibook) verwendet man die Class Activation Map (aus dem Paper ["Learning Deep Features for Discriminative Localization"](https://arxiv.org/abs/1512.04150)) auf einem Deep Learning Model zur Klassifizierung von Tierbildern. Diese Methode sollte auf ein Natural Language Processing Model (NLP Model) übertragen werden. Daraus entstand dann letztlich der Movie Review Analyzer. Dieser geht wie folgt vor
 - Filmkritik aus Textfeld oder aus IMDB Datenset einlesen
 - Filmkritik Wort für Wort mit NLP Model klassifizieren
 - Je Wort die Stärke (Class Activation) wie sehr das NLP Model auf das Wort angesprochen hat speichern
 - Die gesammelten Daten in ein Diagramm überführen

### Webanwendung
Per Klick auf den nachfolgenden Button wird ein Server gestartet und die Anwendung kann getestet werden. **Dies kann bis zu fünf Minuten dauern.**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jack-Byte/Movie-Review-Analyzer/master?urlpath=%2Fvoila%2Frender%2Fmovie-review-analyzer.ipynb)
----------------------------------------------------------------------------------
## English
Movie Review Analyzer is a web application that processes a movie review, and then determines whether it is a positive or negative review. A line graph shows how the particular word contributed to the final classification. If the word has a large diameter and is located higher, it was one of the deciding factors for the classification.

### Context
In Chapter 18 of [Deep Learning for Coders](http://tiny.cc/fastaibook), the Class Activation Map (from the paper ["Learning Deep Features for Discriminative Localization"](https://arxiv.org/abs/1512.04150)) is used on a Deep Learning Model which classifies animal images. A research task was to transfer the method to a Natural Language Processing Model (NLP Model). The Movie Review Analyzer is the result of my approach to this task. It works as follows
 - Read movie review from text field or from IMDB dataset
 - Classify movie review word by word with NLP Model
 - Store the Class Activation for each word
 - Transfer the collected data into a plot

### Web Application
The following button brings you to the app. But you'll have to wait until a server is up and running. **This can take up to five minutes!**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jack-Byte/Movie-Review-Analyzer/master?urlpath=%2Fvoila%2Frender%2Fmovie-review-analyzer.ipynb)


