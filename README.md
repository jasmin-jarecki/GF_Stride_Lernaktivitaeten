## _Informatik Stunden-Dokumentation_

#### **Inhalt**
[1. GF_Stride_Lernaktivitäten](#GF_S._L.)

[2. Unser Spiel **Das Halunken Scenatrio**](#HalScen)

###GF_Stride_Lernaktivitäten<a name="GF_S._L."></a>
  
  _Donnerstag, **22.09.2016**:_
  Linda und ich haben weiter darüber nachgedacht, welches Projekt wir machen. Wir haben uns bereits dafür entschieden, dass wir     mit der Lehrumgebung „Greenfoot“ arbeiten wollen. Nachdem wir uns die verschiedenen Möglichkeiten angeguckt haben, entschieden     wir uns letzten Endes für die GF_Stride_Lernaktivitaeten.
  In dieser Stunde haben wir dann auch angefangen, an der ersten Lernaktivität zu arbeiten. Die dazugehörigen Arbeitsblätter         bearbeiten wir beide auf unseren iPads und sobald wir sie durchgearbeitet haben, werde ich diese zusätzlich hochladen.
  
  _Montag, **26.09.2016**:_
  Linda und ich haben weiter an der ersten Lernaktivität gearbeitet. Dabei haben wir uns bisschen genauer mit den einzelnen         Befehlsblöcken beschäftigt und ein geguckt, wie sie geschrieben sind und wie man diese und mit welchen Folgen verändern kann.     Allerdings haben wir die Aktivität noch immer nicht ganz durchgeschafft.

  _Donnerstag, **29.09.2016**:_
  Linda und ich haben heute die erste Lernaktivität beendet und die zweite angefangen. Das erste Arbeitsblatt wird als nächstes     hochgeladen.
  
  _Montag, **03.10.2016**:_ Tag der Deutschen Einheit → **kein Unterricht**
  
  Donnerstag, **06.10.2016**:
  Auch heute haben Linda und ich an den Lernaktivitäten weitergearbeitet. Die zweite haben wir beendet (das AB wird hochgeladen)   und die dritte haben wir angefangen. Da es für diese keine auszufüllendes AB mehr gibt beschreibe ich von nun an hier drin,    was   wir gemacht haben.
  Lernziele der Aktivität:
  1. Sicherheit darin gewinnen, Methoden aufzurufen
  2. Lernen, den if-Befehl zu verwenden 
  
  In der dritten Aufgabe arbeitet man noch immer mit der Fatcat. Wie es verlangt war, haben wir zunächst die Katze ein paar       Dinge machen lassen, z. B. sollte sie essen. Dafür gab es diesmal keine Befehle mehr die wir aus dem public void commands( )  Feld in das public void act ( ) Feld ziehen mussten. Die Befehle schrieben wir mehr oder weniger selber in der dort angewandten   Sprache. Der fünfte Unterpunkt verlangte, dass wir uns eine eigene Routine für die Katze ausdenken sollten. (Weiter unten ist   eine beigefügte Grafik unseres Programms(?).) 
  Im zweiten der Teil der dritten Aktivität ging es dann darum, den if-Befehl kennenzulernen. Zunächst sollten wir sie schlafen   lassen, falls sie müde ist. Das haben wir gemacht, indem wir den Befehl gaben: 


  if(isSleepy())
  
	  sleep(5)
    
    
 Da Stride-Editor vorgeschrieben war, dass die Katze nicht müde ist, hat diese dann auch nicht geschlafen. Das Gleiche haben   wir dann gemacht mit Tanzen, wenn sie gelangweilt ist und mit Essen, falls die hungrig ist. Uns ist aufgefallen, dass die Katze   auf jeden Fall gelangweilt ist und deswegen tanzt. Nach dem tanzen ist sie dann aber auch hungrig und müde, sodass sie danach   auch isst und schläft, obwohl zunächst formuliert ist, dass sie weder  hungrig noch müde ist.
  Die übrig gebliebenen Unterpunkte müssen wir dann in der nächsten Stunde bearbeiten, da wir sie noch nicht geschafft haben.
  
_Montag, **10.10.2016**:_

_Montag, **31.10.2016**:_

_Donnerstag, **04.11.2016**:_

_Montag, **07.11.2016**:_

_Donnerstag, **10.11.2016**:_

_Montag, **14.11.2016**:_
Aufgrund des anstehenden Abgabetermins der ersten Arbeit entschlossen Linda und ich uns, fürs erste nicht weiter an den Lernaktivitäten zu arbeiten. Wir wollten uns darum bemühen, dass wir eine vorläufig abgeschlossene Form unseres Spiels zu erreichen. 

_Montag, **21.11.2016**:_
Wir waren weiter dabei, eine Lösung für unser "Fässer-Problem" zu finden, allerdings verstrich die Stunde ohne verwertbare Ergebnisse.

_Donnerstag, **25.11.2016**:_
Auch in dieser Stunde bemühten wir uns darum, dass unsere _actors_ nicht durch die Fässer ("barrels") durch können, allerdings gab es auch dieses Mal keine richtigen Erfolge zu verzeichnen. Wir gucken in der nächsten Stunde noch ein bisschen weiter, aber vermutlich verschieben wir dieses Vorhaben doch nach hinten, um uns erstmal um andere Dinge, die für uns leichter zu bewältigen sind, zu kümmern. Hoffentlich lernen wir dann in der Zeit auch, wie wir das Problemmit den Fässern lösen können. Trotz der Schwierigkeiten war die Stunde dennoch nicht komplett ergebnislos. Abgesehen davon, dass wir ein wenig mehr gelernt haben, haben wir unsere Spieloberfläche vergrößert, wofür nur die Werte .... verändert werden mussten.

###Das Halunken Scenatrio<a name="HalScen"></a>

Hierbei handelt es sich um eine Welt die wir eigenständig bei Greenfoot angelegt haben. Ursprünglich wollten wir nur nebenbei damit rumprobieren, was wir mittels der Lernaktivitäten bereits gelernt haben. Da es aber mit der Zeit immer mehr wurde, brauchten wir eine Ziel bzw. eine Richtung, um etwas einigermaßen Sinnvolles zu "programmieren". So entschieden wir, dass wir aus dem Szenario eine Art Spiel machen würden, mit den Werkzeugen, die wir uns mit der Zeit zulegen. Zudem überlegten wir uns Aspekte, die unser Spiel spannender bzw. attraktiver machen sollen in der Hoffnung, dass wir in Zukunft lernen diese Ziele umsetzen zu können.
Folgende Ideen haben wir:
* In dem Spiel soll es darum gehen, dass ein _actor_ einen weiteren [jagen](#Lsg1) soll und diesen letzten Endes _(fr)isst_
* Die _actors_ sollen über die Tastatur gesteuert werden, sodass das Spiel für zwei Spieler sein wird
* Damit es für den Jagenden nicht so leicht ist, soll es noch einen weitereren _actor_ sich geben, der sich willkürlich bewegt und die Blume (fr)isst, wenn er sie berührt
* Um allen Gejagten eine größere Überlebenschance zu ermöglichen, wollen wir so eine Art Hindernisse bzw. Mauer aus Objekten die von den _actors_ nicht überquert werden können, sodass man sich dahinter sozusagen verstecken kann

Ein _actor_ jagt den anderen<a name="Lsg1"></a>:


  [Lernaktivität 1]:



