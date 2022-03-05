---
layout: blog
title: Tipps zu Algorithmen
date: 2022-02-01T18:40:31.265Z
---
In diesem Abschnitt werden praktische Tipps zu bestimmten Themen aus dem Bereich der Algorithmen und Datenstrukturen gegeben, die häufig in Codierungsfragen vorkommen. Viele Algorithmusfragen beinhalten Techniken, die auf Fragen ähnlicher Art angewendet werden können. Je mehr Techniken Sie in Ihrem Arsenal haben, desto höher sind die Chancen, das Interview zu bestehen. Sie können Sie dazu bringen, Eckfälle zu entdecken, die Sie vielleicht übersehen haben, oder Sie können Sie sogar zum optimalen Ansatz führen!

Zu jedem Thema werden Links zum Lernen empfohlen, die Ihnen helfen, das Thema zu beherrschen. Es gibt eine Liste mit empfohlenen allgemeinen Fragen zum Üben, die meiner Meinung nach sehr wertvoll ist, um die Kernkonzepte des Themas zu beherrschen.

Wenn Sie daran interessiert sind, wie Datenstrukturen implementiert werden, sollten Sie sich Lago ansehen, eine Bibliothek für Datenstrukturen und Algorithmen für JavaScript. Sie befindet sich noch in der Entwicklungsphase, aber ich habe vor, sie zu einer Bibliothek zu machen, die in der Produktion verwendet werden kann und auch als Referenzquelle für die Überarbeitung von Datenstrukturen und Algorithmen dient.

### **Allgemeine Tipps** 

Klären Sie alle Annahmen, die Sie unbewusst gemacht haben. Viele Fragen sind absichtlich unterspezifiziert.

Überprüfen Sie immer zuerst die Eingabe. Prüfen Sie auf ungültige/leere/negative/andersartige Eingaben. Gehen Sie nie davon aus, dass Sie die gültigen Parameter erhalten haben. Klären Sie alternativ mit dem Interviewer, ob Sie von einer gültigen Eingabe ausgehen können (in der Regel ist dies der Fall), was Ihnen das Schreiben von Code zur Eingabevalidierung ersparen kann.

Gibt es zeitliche/räumliche Komplexitätsanforderungen/Einschränkungen?

Prüfen Sie auf Ausschlussfehler.

In Sprachen, in denen es keine automatische Typenzwangskontrolle gibt, prüfen Sie, ob die Verkettung von Werten vom gleichen Typ ist: int/str/list.

Verwenden Sie nach Fertigstellung Ihres Codes einige Beispieleingaben, um Ihre Lösung zu testen.

Soll der Algorithmus mehrfach ausgeführt werden, z. B. auf einem Webserver? Wenn ja, sollte die Eingabe vorverarbeitbar sein, um die Effizienz bei jedem Aufruf zu verbessern.

Verwenden Sie eine Mischung aus funktionalen und imperativen Programmierparadigmen:

* Schreiben Sie so oft wie möglich reine Funktionen.
* Reine Funktionen sind leichter zu verstehen und können helfen, Fehler in Ihrer Implementierung zu reduzieren.
* Vermeiden Sie es, die an Ihre Funktion übergebenen Parameter zu verändern, insbesondere wenn sie als Referenz übergeben werden, es sei denn, Sie sind sich sicher, was Sie tun.
* Allerdings ist die funktionale Programmierung aufgrund der Nicht-Mutation und der wiederholten Zuweisung neuer Objekte in der Regel teuer in Bezug auf die Raumkomplexität. Andererseits ist imperativer Code schneller, weil er auf bereits vorhandenen Objekten arbeitet. Daher müssen Sie ein Gleichgewicht zwischen Genauigkeit und Effizienz herstellen, indem Sie das richtige Maß an funktionalem und imperativem Code verwenden, wo es angebracht ist.
* Vermeiden Sie es, sich auf globale Variablen zu verlassen und diese zu verändern. Globale Variablen führen einen Zustand ein.
* Wenn Sie sich auf globale Variablen verlassen müssen, stellen Sie sicher, dass Sie sie nicht versehentlich verändern.

### Empfohlene Kurse

1.  **   ​​<https://techdevguide.withgoogle.com/>** 
2. **\    [https://www.pramp.com](https://www.pramp.com/#/)** 
3.  **   Check educative.io website**