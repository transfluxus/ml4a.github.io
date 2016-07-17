---
layout: chapter
title: "Introduction"
---

**Introduction: Harold Cohen**
**Machine learning: 00000**
**Neural networks: Lovelace**
**Looking inside neural nets: Brainbow**
**How neural nets are trained: Topographic map**
**Convnets: Convnets are everywhere**
**Looking inside convnets: Visualization/**
**Deepdream: Mike Tyka**
**Style transfer: Mona Lisa series**
**Generative models: Tom White VRAE**
**Recurrent neural nets: MC Escher**




\"Artificial intelligence is anything computers [can\'t do yet](https://en.wikipedia.org/wiki/AI_effect)\" - Douglas Hofstadter, re: Tesler theorem 

\"Machine learning is applied computational statistics.\" - Chris Wiggins


Selbstverständlich bedeutet der Begriff _Künstliche Intelligenz_ und Maschinelles Lernen_ etwas anderes je nach dem wen man fragt.

Der Begriff Künstliche Intelligenz tauchte in [den 1950 auf](https://en.wikipedia.org/wiki/History_of_artificial_intelligence) und wurde von ___ eingeführt. Die Begeisterung für das Thema schwankte zwischen Perioden großer Popularität und Pessimismus und [geringem Interesse](__ai winter__), der Teilweise dadurch ausgelöst wurde, das es die Techno-utopischen Prognosen von Opportunistischen Spekulanten [opportunistic speculators] (https://en.wikipedia.org/wiki/The_Singularity_Is_Near) nicht so früh erreichen konnte wie erwartet.

Pamela McGoldrick erklärt die periodischen Einbrüche damit das \"Verwendbare Erfolge durch KI, Computerprogramme die tatsächlich intelligentes Verhalten aufweisen schnell in die Anwendungsdomänen in denen sie sich als nützlich erwiesen haben integriert wurden und neben anderen Problemlösenden Ansätzen zu stille Helfern wurden, was die KI Forscher, mit den reinen
Fehlschlägen alleine ließ.
\"


In ähnlicher weise geht die Verwendung des Begriffs \"Maschinelles Lernen \" zurück bis zu den 1980, aber die Grundkonzepte reichen wesentlich weiter in die Vergangenheit als der Begriff selber. Als eigenständiges Forschungsfeld bekam es breitere Aufmerksamkeit als Ansätze der Statistik, insbesondere als man begann Daten-driven computational statistic für Probleme in der KI zu verwenden.

Maschinelles Lernen ist in der KI Forschung vorherrschend, so das die beiden Begriffe in der Forschung und außerhalb oft Synonym verwendet werden.

## Die Entstehung von Tiefem Lernen


In den 2010er Jahren fingen viele ML Forscher, die mit mehrschichtigen (\"deep\") Architekturen arbeiteten — insbesondere mehrschichtigen neuronalen Netzen — den Begriff \deep learning\ (Tiefes Lernen) zu verwenden.

Tiefe neuronale Netze setzten im Jahr 2009 im Bereich Spracherkennung neue Maßstäbe und im Bereich Bilderkennung im Jahre 2012 – wobei sie die Ergebnisse der besten Systeme der letzten Jahre weit hinter sich ließen und sind seitdem leitgebend was die meisten modernen ML Techniken angeht. In den letzten 5 Jahren haben die wichtigsten wissenschaftlichen Institute ihre finanziellen Mittel für ML Forschung und insbesondere tiefem Lernen erhöht. Der größte Teil der Forschung bewegte sich weg von den Universitäten hin zu den großen Konzernen der Technologie Industrie unter anderem Facebook, Google, Microsoft und Amazon.
Der typischen Geheimhaltung verdankend [Apple weit zurück gelassen (ENG)](http://www.bloomberg.com/news/articles/2015-10-29/apple-s-secrecy-hurts-its-ai-software-development).


Im Jahr 2015 schrieb [Jürgen Schmidhuber](http://people.idsia.ch/~juergen/) [\"A
Critique of Paper by \'Deep Learning Conspiracy\'\"] (http://people.idsia.ch/~juergen/deep-learning-conspiracy.html) und deutet darauf hin das die neusten Fortschritte im Bereich des Tiefen Lernens auf frühere Arbeiten mehrschichtiger neuronaler Netze, die Jahrzehnte zurückgehen. Seine Veröffentlichung provozierte eine Menge von Kommentaren von einer Vielzahl von Leuten und unter anderem von bekannten Forschern und löste den einen harten Streit (flamewar) im Internet unter Akademikern jemals aus (ENG)(https://plus.google.com/100849856540000067209/posts/9BDtGwCDL7D).

## Deep learning shmeep learning
WHAT ??? 

Keiner Dieser Begriffe eine klare definierte Bedeutung und die Konnotationen wechseln unstetig, insbesondere in der wissenschaftlichen Gemeinde selber. Wir sind an Maschinen, die interessante Sachen _machen_, interessiert und daran, was sie _jetzt_ können— oder zumindest in der Nahen Zukunft.

## Kernprinzipien dieses Buches

### Magische Mathematik


Es existieren bereits viele akademische Kurse. Dieses Buch versucht nicht diese zu ersetzen, sondern versucht eher zwischen den Seiten Wissenschaft und Magie zu stehen.


## Software

Dieses Buch versucht einen Mittelweg zu finden. Es versucht Methodisch und die Installationen einfach zu beschreiben. Es werden so viele Beschreibungen und Beispiele vorhanden sein. 

## Aktualisierungen

Maschinelles Lernen ist ein sich schnell veränderndes Feld und ein Viertel des Entwurfes war bereits obsolet als er fertig geschrieben wurde. Wir versuchen das Material auf dem neusten Stand zu halten und sind offen für Tipps und Beiträge [github][twitter][email]. Wenn du Vorschläge, Korrekturen, interessante Links zu relevanten Projekten hast dann poste sie im Issue Tracker oder schreib mir.

## Mathematik

Im allgemeinen versucht dieses Buch den Matheanteil so gering wie möglich zu halten und mit visuellen Hilfsmitteln statt Gleichungen auszukommen. Das kommt daher, das Neuronale Netze visuell sehr verständlich sind und es keine besonderen Qualifikationen benötigt. Dennoch könnte es hilfreich sein, da das Thema Wahrscheinlich und räumliche Geometrie auch vorkommen. Francis Tseng hat einen netten Leitfaden zu KI und ML geschrieben, der ein gutes Grundwissen benötigt (In Englisch)

one of the things we can do away with is some of the details of training deep networks and focus on applications. vindication for me as its all i used to do


etc
 - machine learning as a subject for artistic practice and interdisciplinary research
 - https://docs.google.com/document/d/1wmJtZ8QTeE6nBCT17iWWVwNvhfOm0mPA8smNNGG2Agw/edit

 - These notes and the accompanying course will be less rigorous than CS231n, and others. Those courses assume a certain level of mathematical proficiency and the majority of students have some background, if not a degree, in computer science.
In contrast, this course will make as few assumptions as possible about background preparation. In practice, this necessarily entails some sacrifice; nothing beats having a ___. But many important aspects of machine learning can be well understood with nothing more than high school-level mathematics and good analogies and abstractions. It is both possible and desirable to be able to engage with the subject at this level, whereas they may otherwise not approach it at all. An example of this in practice -- backpropagation
