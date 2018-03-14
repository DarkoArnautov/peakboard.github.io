---
layout: article
lang: de
ref: Der_Peakboard-Designer_�_Die_Basics
---

Dieses Tutorial ben�tigt keinerlei Vorkenntnisse. Es zeigt die allerersten Schritte mit Peakboard und erkl�rt einige theoretische Basics, die man verstanden haben muss, um dann sp�ter komplexere Visualisierungen zu bauen. Die grunds�tzliche Vorgehensweise ist aber immer dieselbe: Die Visualisierung wird mit Hilfe des Peakboard-Designers gestaltet. Ein Design � oder auch Board genannt � wird dann auf eine oder mehrere Peakboard-Boxen �bertragen, auf dem es autark l�uft. Alle Artefakte wie Bilder, Videos usw. werden zur �bertragung in ein Package gepackt. Diesen Vorgang nennt man Deployment. Den kompletten Ablauf zeigt dieses Tutorial. F�r den Fall, dass Sie noch keine Peakboard-Box besitzen, reicht auch erstmal die Designer-Software, die Sie auf unserer Homepage runterladen k�nnen. Das �bertragen des Designs auf die Box f�llt dann nat�rlich weg � macht aber nichts, weil man es auch einfach als Preview auf dem eigenen Rechner betrachten kann.

Das Installationsprogramm funktioniert wie jedes andere Installationsprogramm auch und legt das Designer-Programm im Installationsordner ab. Um den Designer zu starten, k�nnen Sie auf das Programm-Icon klicken oder auf die Windows-Taste und dann �peak� eintippen. Windows 10 findet den Verweis dann. Achtung! Starten Sie bitte nicht Peakboard.Runtime-App. Dazu kommen wir sp�ter.

![image_1](/assets/images/TutorialBasics01.png)

Im gestarteten Designer sehen Sie nun auf der linken Seite den Package-Explorer, also alle Elemente, die sp�ter auf die Peakboard-Box �bertragen werden. In der Mitte ist das leere Panel, das wir nun mit Leben f�llen wollen. Der rechte obere Bereich sind Controls oder visuelle Elemente, die aus der Toolbox per Drag and Drop auf das Panel gezogen werden k�nnen. Rechts unten k�nnen Sie Eigenschaften des Panel-Elements ver�ndern, das gerade markiert ist.

![image_1](/assets/images/TutorialBasics02.png)

Wir wollen mit einem einfachen Textblock starten. Ziehen Sie mit der Maus ein Text-Control aus der Toolbox auf das Panel.

![image_1](/assets/images/TutorialBasics03.png)

Unten rechts k�nnen Sie im Eigenschaftsfeld nun den Textblock anpassen, z.B. den Font ausw�hlen (wie man einen neuen Font hinzuf�gt erfahren Sie sp�ter) und noch viel wichtiger: Den Inhalt mit einer sinnvollen Nachricht f�llen.

![image_1](/assets/images/TutorialBasics04.png)

Um das Panel um ein Bild zu erg�nzen, m�ssen wir das Bild als Ressource hinzuf�gen. Im Package Explorer auf der linken Seite mit der rechten Maustaste auf Resources klicken und dann auf Add Resource. Sie k�nnen nun ein Bild von ihrem lokalen PC aussuchen, z.B. ein sch�nes Urlaubsfoto, ein Firmenlogo oder ein Hundewelpe. Das Bild erscheint dann als Eintrag unter dem Ressourcen-Zweig.

![image_1](/assets/images/TutorialBasics05.png)

![image_1](/assets/images/TutorialBasics06.png)

Um das Bild nun auf das Panel zu bekommen, ziehen Sie per Drag and Drop ein Image-Control von der Toolbox auf das Panel, so wie wir das mit dem Textfeld gemacht haben. Markieren Sie das neue erstellte Image-Control und klicken Sie auf die drei Punkte in den Eigenschaften unten rechts. Dann �ffnet sich der Dialog zum Aussuchen einer Ressource so wie im Screenshot gezeigt. Sie haben nun das Image-Control mit der Ressource verkn�pft.

![image_1](/assets/images/TutorialBasics07.png)

Alternativ dazu k�nnen sie auch direkt die Ressource auf das Panel ziehen.

Sie k�nnen nun die beiden Elemente � das Textfeld und das Bild � noch etwas h�bscher anordnen. Die Hilfslinien, die automatisch eingeblendet werden, helfen Ihnen dabei die Elemente so zu platzieren, dass es gut aussieht.

![image_1](/assets/images/TutorialBasics08.png)

Um nun zu erfahren, wie ihr fertiges Design sp�ter auf dem Monitor aussieht, klicken Sie in der Toolbar auf Preview. Es �ffnet sich das Preview-Fenster. In unserem Fall ist das noch nicht ganz so spannend, weil wir ja nur unver�nderliche Inhalte benutzt haben. Aber in sp�teren Beispielen werden wir Boards bauen, die Interaktion oder dynamische Daten enthalten. Um die Dynamik zu sehen und auszuprobieren, braucht man entweder die Preview-Ansicht oder muss das Board auf eine Box �bertragen.

![image_1](/assets/images/TutorialBasics09.png)

Unter dem folgenden Link erfahren Sie mehr dar�ber, wie das neu erstellte Design auf die Peakboard-Box �bertragen und aktiviert wird:

Erste Schritte mit der Peakboard-Box

