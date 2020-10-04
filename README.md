# Guidelines

## Einleitung
Dieses ist eine öffentliche GitHub-Organisation mit dem Namen **ModifiedCommunityModules**. Durch diese GitHub-Organisation können kostenlose Module für die [modified eCommerce Shopsoftware](https://www.modified-shop.org) veröffentlicht werden. Alle Modul-Repositories sollen die Sichtbarkeitsrechte `public` erhalten. 

Diese Guidelines sollen dazu beitragen, dass es einen fairen Umgang mit dem geistigen Eigentum von Entwicklern gibt, die hauptsächlich kostenlos einen Beitrag für die [modified eCommerce Shopsoftware](https://www.modified-shop.org) leisten. Das Ziel dieser Guidelines ist, dass der Beitrag jedes Contributors in angemessener und üblicher Weise gewürdigt werden kann. Oft behinhaltet dieses die namentliche Nennung und die damit verbundene Möglichkeit, dem richtigen Adressarten für seinen Beitrag Dank und Anerkennung zukommen lassen zu können.

Die hier aufgeführten Regeln gelten für Dritte, die ein kostenloses Modul auf GitHub und im [MMLC](https://module-loader.de) veröffentlichen möchten, für die sie selbst nicht die Vertretungsbefugnisse haben. Oft handelt es sich hierbei um ein kosntenloses Modul aus dem [modified Forum](https://www.modified-shop.org/forum/). Eine Veröffentlichung muss im Einklang mit der Lizenz erfolgen, unter der ein Modul veröffentlicht wurde. Vertretungsberechtige Autoren, die selbst ein Modul entwickelt haben, müssen ihr Modul nicht unter **ModifiedCommunityModules** veröffentlichen, um dieses Modul auch im [MMLC](https://module-loader.de) veröffentlichen zu dürfen. Ihnen steht es aber weiterhin frei, auch ihr Modul unter **ModifiedCommunityModules** zu veröffentlichen. Informationen zur Veröffentlichung von Modulen im [MMLC](https://module-loader.de) gibt es unter folgendem Link: https://module-loader.de/docs/publish_module.php

Durch eine Veröffentlichung auf GitHub, kann jeder von den Änderungen und Verbesserungen profitieren, die am Programmcode von Modulen gemacht werden. Es wird zudem eine einfache Möglichkeit angeboten, an der Weiterentwicklung von Modulen mitzuwirken. Git und im speziellen GitHub stellt einen moderner Ansatz bei der gemeinschaftlichen Entwicklung von Modulen für [modified](https://www.modified-shop.org) bereit, der von einer großen Anzahl der OpenSource-Entwickler bevorzugt wird. Eine veröffentlichung auf GitHub soll einen Anreiz für neue Entwickler schaffen, die sich diesen modernen Ansatz bei ihrer Arbeit als Entwickler wünschen. Auch kann damit schnell und einfach in der Commit-History nachvollzogen werden, welcher Contributor Programmcode verändert hat und welcher Programmcode verändert wurde. Das kann zusätzlich für eine höhere Sicherheit und eine bessere Programmcodequalität sorgen.

Module die hier unter **ModifiedCommunityModules** veröffentlicht werden, können auch weiterhin ohne den [MMLC](https://module-loader.de) heruntergeladen und wie üblich per Hand installiert werden. Das gilt, solange es hierfür keine technischen Hindernisse gibt. Module die für den MMLC umgebaut wurden, können von anderen Modulen abhängen. In diesem Fall müssen auch die Abhänigkeiten händisch installiert werden.

Eine Veröffentlichung findet unter folgendem Link auf GitHub statt. `https://github.com/ModifiedCommunityModules/MODUL_NAME`. Durch diesen generischen GitHub-Organisations-Namen, beinhalten die Links und Pfade zu den Repositories der Module auf GitHub nicht mehr den Namen eines einzelnen GitHub-Users, welcher möglicherweise wenig am Modul selbst beigetragen hat. Dadruch soll verhindert werden, dass ungewollt ein GitHub-User in den Mittelpunkt gestellt wird, der wenig zu einem Modul beigetragen hat, keine offiziellen Vertretungsbefugnisse hat und lediglich ein kostenloses Modul auf GitHub für eine moderne gemeinschaftliche Weiterentwicklung veröffentlichen möchte.

Die Veröffentlichung unter **ModifiedCommunityModules** schließt nicht aus, dass ein Repository zu einem späteren Zeitpunkt einem anderen GitHub-User übertragen werden kann, der das Modul berechtigt für sich beansprucht. Das geht jedoch nur, solange das Modul nicht umfangreich durch weitere Contributor bearbeitet wurde. Dem Ursprünglichem Autor des Moduls steht es jedoch frei, das Repository zu kopieren und es unter seinem eigenen Namen weiterzuentwickeln. Die Regeln der jeweiligen Lizenz gilt es einzuhalten. Oft beinhaltet dieses auch die Nennung der neuen und alten Contributor.

## Regeln
1. Jeder, der einen positiven Beitrag an den Modulen leisten möchte, kann Mitglied der GitHub-Organisation **ModifiedCommunityModules** werden. Sollte es Zweifel daran geben, dass der User mit positiven Absichten handelt, kann die Teilnahme verweigert werden. Das kann auch Rückwirkend geschehen. Ein Ausschluss findet immer mit einer Begründung statt.

2. Die Contributor an Modulen achten auf die Nennung aller Contributor an der von der Lizenz dafür vorgesehenen Stelle und versuchen die Entwicklingsgeschichte des Moduls nicht zu verbergen. Die Contributor beachten die Regeln der Lizenz unter dem ein Modul veröffentlicht wurde.

3. Die Module weisen auf ihren Ursprung hin, soweit dieser bekannt ist. Sollte ein Modul beispielsweise aus dem [modified Forum](https://www.modified-shop.org/forum/) stammen, muss ein Link zum entsprechenden Forums-Thread angegeben werden, soweit dieses möglich ist.

4. Als Modul-Icon sollte ein generisches Icon verwendet werden, dass auf modifed schließen lässt, dass von modified freigeben wurde, für das die Nutzungsrechte vorliegen und das bei allen kostenlosen modified Module verwendet werden darf, die unter **ModifiedCommunityModules** veröffentlicht werden. Sollte es kein Modul-Icon geben, welches diese Anforderungen erfüllt, kann das Standard Modul-Icon aus dem [MMLC](https://module-loader.de) oder auch kein Modul-Icon verwendet werden.

5. Die unter **ModifiedCommunityModules** veröffentlichten Module dürfen nur kostenlos im [MMLC](https://module-loader.de) veröffentlicht werden.

6. Soll ein Modul im [MMLC](https://module-loader.de) veröffentlicht werden, müssen diese technisch angepasst werden. Für diese Anpassungen werden folgende generische Bezeichnungen verwendet: 
- VendorName (lisp-case):	`modifiedcommunitymodules`
- VendorPrefix:	(snake_case):	`mcm`
- Namespace	(PascalCase):	`ModifiedCommunityModules`
- vendor-no-composer (PascalCase): `ModifiedCommunityModules`

Mehr Information hierzu gibt es unter: https://module-loader.de/docs/naming_convention.php

7. In den jeweiligen Dateien müssen je nach Lizenz die Contributor/Autoren genannt werden. Sollte das nicht möglich sein, wird das Modul mindestens mit einer Datei **CONTRIBUTORS.md** ausgeliefert, in der alle Contributor/Autoren in angemessener üblicher OpenSoruce-Weise erwähnt werden, es sei denn, eine Erwähnung wird nicht gewünscht oder ist technisch nicht möglich.

8. Kommt ein Modul aus dem [modified Forum](https://www.modified-shop.org/forum/), wird im entsprechendem Forums-Thread der Modul-Entwickler darüber informiert, dass sein Modul auf GitHub unter **ModifiedCommunityModules** veröffentlicht wurde und zukünftig auch kostenlos im [MMLC](https://module-loader.de) veröffentlicht werden kann. Hierzu wird der Link zu GitHub und falls möglich zum Modul im [MMLC](https://module-loader.de) mit angegeben.

9. Es muss in der Modulbeschreibung auf folgendes hingewiesen werden: *Für dieses Modul kann Support freundlich im [modified Forum](https://www.modified-shop.org/forum/) erfragt werden. Ein Anspruch auf Support besteht jedoch nicht. Alternativ kann ein Dienstleister für Support (auch kostenpflichtig) beauftragt werden.*

10. Werden an einem Modul neue nicht triviale Funktionen oder erhebliche Änderungen am Code vorgenommen und eine eigene Schöpfungshöhe ist ersichtlich, darf das Modul auch kostenlos unter dem eigenen Account veröffentlicht werden. Die Nennung der Contributor/Autoren wie aus Punkt 7 muss weiterhin erfolgen. Oft wird das bereits von der Lizenz verlangt, unter dem ein Modul veröffentlicht wurde.

11. Jedes Modul, dass unter **ModifiedCommunityModules** veröffentlicht wird, muss eine **README.md** Datei beinhalten, in der auf diese Guidelines verwiesen wird.

## Tipps

### Umgang mit der GPL 2.0 Lizenz

Die GPL 2.0 ist eine Lizenz die sich auf ein Gesamtwerk bezieht. Das bedeutet, dass es technisch nicht notwendig ist, dass ein Lizenz-Header pro Datei angegeben werden muss. Viele Projekte die unter der GPL 2.0 veröffentlicht wurden, wie GIT, Linux oder phpMyAdmin sind deswegen dazu übergegangen keinen Lizenz-Header pro Datei zu verwenden und liefern den Quellcode nur mit einer zentralen `COPYING` oder `LICENSE` Datei aus, sowie einer Datei `AUTORS` oder `CONTRIBUTORS.md`. Diese Entscheidung ist unter anderem aus dem Grund getroffen worden, da sich mitlerweile Änderungen am Quellcode durch Systeme wie GIT oder SVN genau auf einen Contributor zuordnen lassen.

Um dem original Autor und den weiteren Mitwirkenden jedoch die Möglichkeit zu geben, dass sie durch dritte einfach mit ihren Werken identifiziert werden können, lässt sich beispielsweise der folgende GPL 2.0 Header pro Datei verwenden.

#### Beispiel für eine PHP Datei

```
<?php
/**
 * Name of your Module
 *
 *  Copyright 2012 by ...
 *  Copyright 2011 by Erika Mustermann <erika.mustermann@example.com>
 *  Copyright 2010 by Max Mustermann <max.mustermann@example.com>
 * 
 *  Licensed under GNU General Public License 2.0 or later. 
 *  Some rights reserved. See LICENSE, CONTRIBUTORS.md.
 *
 * @license GPL-2.0+ <https://www.gnu.org/licenses/old-licenses/gpl-2.0-standalone.html>
 */
```

Stand 4.10.2020
