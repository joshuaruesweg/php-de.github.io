---
layout:    guide
permalink: /jumpto/editors-ide/
root:      ../..
title:     "Editoren und IDEs"
creator:   tr0y
group:     "Entwicklungsumgebung"
orderId:   2

author:
    -   name: tr0y
        profile: 21125

    -   name: hausl
        profile: 21246

    -   name: mermshaus
        profile: 15041

inhalt:
    -   name:   "Editoren"
        anchor: php-editoren
        simple: ""

    -   name:   "Integrierte Entwicklungsumgebungen (IDEs)"
        anchor: integrierte-php-entwicklungsumgebungen-php-ide
        simple: ""

    -   name: Sonstige
        anchor: sonstige
        simple: ""
---

Dieser Beitrag bietet eine Übersicht über Editoren und Entwicklungsumgebungen, die für die Arbeit mit PHP geeignet sind. Wer seine Wahl ebenfalls äußern möchte, ist in [diesem Beitrag](http://www.php.de/php-einsteiger/101627-editor-ide-let-me-tell-you-something.html) herzlich dazu eingeladen.


### Editoren
{: #php-editoren}

Ein Editor ist eine Anwendung, die grundlegende Funktionen zur Text- und Quellcodebearbeitung bereitstellt, die aber nicht direkt mit PHP oder anderen Tools interagiert und die auch keine weiterführenden sprachspezifischen Features enthält. Editoren erleichtern die Arbeit, indem sie beispielsweise per Syntax-Highlighting auf Typos oder andere Syntaxfehler hinweisen.

* **Sublime Text** - **empfohlen**{: style="color: #006400"}
    <br>Webseite: [http://www.sublimetext.com](http://www.sublimetext.com)
    <br>UI-Sprache: Englisch
    <br>Features: Viele - Siehe Webseite
    <br>Erweiterbar: Ja - Scriptbasiert (LUA), XML-basiert
    <br>Kostet: 70 $
    <br>Plattform: Windows, Linux, Mac
    <br>Benutzer: **Twitter**

    Sublime Text 2 ist ein Editor mit vielen Features für den Performance auch bei großen Dateien kein Problem ist. Die Download-Version ist voll funktionsfähig, die 70 $ für die Vollversion Entfernen lediglich ein Popup, das alle 30-60 Minuten beim Speichervorgang erscheint, aber sofort schließbar ist.

* **Kate**
    <br>Webseite: [http://kate-editor.org](http://kate-editor.org)
    <br>UI-Sprache: sehr viele
    <br>Features: Viele - Siehe Webseite und [Wikipedia](http://de.wikipedia.org/wiki/Kate_(KDE))
    <br>Erweiterbar: Ja
    <br>Kostet: **kostenlos; freie Software**
    <br>Plattform: Windows, Linux, Mac

    Kate ist ein Editor der KDE Software Compilation. Er ist vergleichbar mit Notepad++ und Sublime Text, allerdings nicht so „feature-rich“ wie Sublime Text.

* **Notepad++**
    <br>Webseite: [http://notepad-plus-plus.org/](http://notepad-plus-plus.org/)
    <br>UI-Sprache: lokalisierbar, Deutsch, Englisch, ...
    <br>Features: Einige - Siehe Webseite
    <br>Erweiterbar: Ja - Plugins (C-basiert)
    <br>Kostet: **kostenlos**
    <br>Plattform: Windows

    Notepad++ ist ein solides Meisterwerk der Opensource Community und wird stetig weiterentwickelt. Grundsätzlich genauso zuverlässig wie Sublime Text 2, leider nicht so funktionsreich und von der Handhabung her auch etwas umständlicher.

* **Coda**
    <br>Webseite: [https://panic.com/coda/](https://panic.com/coda/)
    <br>UI-Sprache: Englisch
    <br>Features: Viele - Siehe Webseite
    <br>Kostet: 99 $
    <br>Plattform: Mac

    Coda ist brilliant und wäre eine echte Konkurrenz für Sublime Text, allerdings nur für den Mac.

* **ActiveState Komodo Edit** - **empfohlen**{: style="color: #006400"}
    <br>Webseite: [http://komodoide.com/](http://komodoide.com/)
    <br>UI-Sprache: Englisch
    <br>Features: Siehe Webseite
    <br>Kostet: **kostenlos**
    <br>Plattform: Windows, Linux, Mac

    Komodo Edit ist wohl der ausgereifteste Editor, man merkt aber schnell das er der kleine Bruder von Komodo Studio ist, was ihm keine Nachteile beschert, man aber doch hier und da Funktionen findet, die eigentlich IDE-spezifischer sind.

* **Bluefish**
    <br>Webseite: [http://bluefish.openoffice.nl/index.html](http://bluefish.openoffice.nl/index.html)
    <br>UI-Sprache: Englisch
    <br>Features: [http://bluefish.openoffice.nl/features.html](http://bluefish.openoffice.nl/features.html)
    <br>Kostet: **kostenlos**
    <br>Plattform: Windows, Linux, Mac

    Bluefish ist aus der Produktfamilie der Content Editing Environments der Open Office Foundation und ebendso wie Notepad++, Sublime Text 2 und Coda ein leistungsfähiger Editor, der hier und da mit der ein oder anderen Gehirnwindung Gassi geht.


### Integrierte Entwicklungsumgebungen (IDEs)
{: #integrierte-php-entwicklungsumgebungen-php-ide}

Integrierte Entwicklungsumgebungen interagieren immer mit PHP und vernetzen eure Scripts so das ihr jederzeit (auch grafisch) durch die Scripts navigieren könnt und schon beim Autocomplete seht wo die Funktion die ihr gerade benutzt definiert wurde und welche Parameter sie hat. Qualitätssicherung steht nicht bei jeder IDE im Vordergrund, wird jedoch in jeder IDE zumindest Ansatzweise implementiert.

* **JetBrains PhpStorm** - **empfohlen**{: style="color: #006400"}
    <br>Webseite: [http://www.jetbrains.com/phpstorm/](http://www.jetbrains.com/phpstorm/)
    <br>UI-Sprache: Englisch
    <br>Features: [http://www.jetbrains.com/phpstorm/features/index.html](http://www.jetbrains.com/phpstorm/features/index.html)
    <br>Kostet: 89 € + Steuern Vollversion / 44 € + Steuern Upgrade pro Entwickler
    <br>Plattform: Windows, Linux, Mac
    <br>Benutzer: **Valve, Paypal, MediaWiki**

    Eine der umfangreichsten IDEs auf dem Markt aus dem Hause JetBrains, Java-basiert.

* **ActiveState Komodo IDE**
    <br>Webseite: [http://www.activestate.com/komodo-ide](http://www.activestate.com/komodo-ide)
    <br>UI-Sprache: Englisch
    <br>Features: Siehe Webseite
    <br>Kostet: 382 $

    Eine etwas teurere IDE aus dem Hause ActiveState.

* **NetBeans**
    <br>Webseite: [https://netbeans.org/](https://netbeans.org/)
    <br>UI-Sprache: lokalisierbar
    <br>Features: [https://netbeans.org/features/index.html](https://netbeans.org/features/index.html)
    <br>Kostet: **kostenlos**

    NetBeans ist die Basis einiger IDEs und natürlich als Ur-Element auch nicht zu verachten. Basiert auf Java und ist erweiterbar.

* **Eclipse**
    <br>Webseite: [http://www.eclipse.org/](http://www.eclipse.org/)
    <br>UI-Sprache: Englisch
    <br>Features: Siehe Webseite
    <br>Kostet: **kostenlos**

    Eclipse ist die Basis einiger weiterer IDEs wie beispielsweise ZendStudio.

* **Zend's ZendStudio**
    <br>Webseite: [http://www.zend.com/de/products/studio/](http://www.zend.com/de/products/studio/)
    <br>UI-Sprache: lokalisiert
    <br>Features: [http://www.zend.com/de/products/studio/features](http://www.zend.com/de/products/studio/features)
    <br>Kostet: 299 € (ab und zu sind Rabatt-Aktionen, siehe Webseite)
    <br>Specials: Hoch kompatibel mit dem PHP-Stack aus eigenem Hause (Zend Server)

    ZendStudio ist ziemlich nah an PHP entwickelt und basiert auf Eclipse.

* **Aptana Studio** - **empfohlen**{: style="color: #006400"}
    <br>Webseite: [http://aptana.com/](http://aptana.com/)
    <br>UI-Sprache: Englisch
    <br>Features: [http://aptana.com/products/studio3](http://aptana.com/products/studio3)
    <br>Kostet: **kostenlos**

    Aptana Studio ist das Sublime Text unter den IDEs, aber nicht ganz so funktionsreich wie PhpStorm, dennoch die kostenlose Empfehlung für Einsteigende und Fortgeschrittene PHP-Entwickler.

* **CSE HTML Validator**
    <br>Website: [http://www.htmlvalidator.com/](http://www.htmlvalidator.com/)
    <br>UI-Sprache: Englisch
    <br>Features: [http://www.htmlvalidator.com/htmlval/comparisonchart.html](http://www.htmlvalidator.com/htmlval/comparisonchart.html)
    <br>Kostet: abhängig von der Version - Kostenlos als Lite-Version, 299 € als Enterprise-Version, siehe Compairson-Chart

    CSE HTML Validator ist ein ausgereifter Mix-Type aus Editor, Validator und IDE mit Fokus auf Validierung. Ob dieser Typ Anwendung den Anforderungen entspricht hängt wie bei jeder anderen IDE oder Editor vom Entwickler ab. CSE HTML Validator ist definitiv einen Blick wert.

* **phpDesigner 8**
    <br>Website: [http://www.mpsoftware.dk/](http://www.mpsoftware.dk/)
    <br>UI-Sprache: Englisch
    <br>Features: [http://www.mpsoftware.dk/phpdesigner.php](http://www.mpsoftware.dk/phpdesigner.php)
    <br>Kostet: abhängig von der Version - Personal für 29 €, Commerical für 69 €

    phpDesigner ist eine der kostengüstigeren IDEs, nicht ganz so umfangreich wie PhpStorm, dennoch mit allem gerüstet was den täglichen Einsatz als Software-Entwickler leichter macht.


### Sonstige

Einige Editoren werden es nicht in diese Übersicht schaffen, da sie entweder nicht PHP-spezifisch und wenn zwar nicht oder zu wenig verbreitet in der PHP-Welt sind. Da diese Editoren nicht gänzlich ungenannt bleiben sollten, findet ihr sie in der folgenden Liste:

* [TextPad](http://www.textpad.com/products/textpad/index.html) - Wenig verbreitet
* [Vim](http://www.vim.org/index.php) - Zwar verbreitet, aber nur geringe Anfänger-Tauglichkeit
* [Emacs](http://www.gnu.org/software/emacs/) - Verbreitet, aber auch geringe Anfänger-Tauglichkeit - Sehr hohe Erweiterbarkeit
