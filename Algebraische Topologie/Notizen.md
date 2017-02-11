<h1>Ergebnisse der <a href="http://math.stanford.edu/~vakil/threethings.html">Drei-Fragen-Challenge</a></h1>

<h2>Wichtige Ideen/Motivationen/Konzepte</h2>
* Ziel der Algerbaischen Topologie: Finde Funktor A: TOP -> GRP
* Ziel der Homotpie Theorie: Finde algebraische Konstruktion A wie oben, die invariant unter bestimmten Homotoien ist
	Dann berechne A auf einfachen top. Räumen und Abbildungen und deformiere die eigentlich interessanten Räume zu diesen einfacheren.
* Führt man kategorientheoretische Beweise über Hom-Mengen (-> Yoneda) statt über die Objekte selbst, arbeitet man automatisch in _Set_ (und kann also zu recht nur über Mengen nachdenken)
	(muss man dafür dann aufpassen, dass die Hom-Mengen auch immer Mengen bleiben? Außerdem müsste man _Set_ kennen! ^^)
* "wesentlich surjektiv" ist "Surjektivität" für Funktoren, aus "Volltreuheit" folgt "Injektivität" für Funktoren (im Beweis von F(f) = F(g) => f=g benötigt man "voll" um Morphismen zu finden, die auf einen Isomorphismus abgebildet werden, ud "treu" um zu zeigen, dass dieser ebenfalls ein Iso ist (F(f)=id -> f=id)). 
	Inwiefern ist Volltreuheit _mehr_ als Injektivität und warum braucht man das?
* Die Asymetrie der Topologien auf Produkt- und Koproduktraum stammt von der Asymmetrie des Verhaltens von offenen Mengen und Schnitten bzw. Vereinigungen (nur endliche vs. beliebige)
	

<h2>Besonders erinnerungswürdige Definitionen</h2>
* Das CW in CW-Komplex steht für "closure-finite weak-topology"


<h2>Besonders erinnerungswürdige Sätze</h2>
* Die Pfade in einem topologischen Raum (modulo Homotopie) bilden (als algebraisches Objekt) einen Gruppoid, den Fundamentalgruppoid
* f, g: S^1->S^1: deg fg = deg f + deg g, denn: deg f = k => f homotop exp(2pi i k), deg g = l => ... =(Blatt 1/A4)=> fg homotop exp(2pi i (k+l)) => deg fg = k+l
* Eckmann-Hilton Argument: ...
* Für eine ategorie C, x \in Ob C, definiere \pi_1(C,x) := Aut_C(x). Der Beweis des "konkreten" Theorems von van Kampen aus dem abstrakten Theorem geht dann völlig analog.
* RP^1 homöomorph S^1, für höhere Dimensionen stimmt das aber nicht mehr
* Untergruppen von Index 2 sind immer normal (warum?)
* X k-Raum und schwach hausdorffsch (also kompakt erzeugt). Dann gilt: A \subseteq X abgeschlossen <=> \forall K \subseteq X komp: A \cap K abg (und analog für offen). D.h. in _kompakt erzeugten_ Räumen reicht es Abgeschlossenheit/Offenheit auf Kompakta zu testen.
* Ist in einer kurzen exakten Sequenz von Gruppen die mittlere abelsch, so sind es auch die anderen beiden
	-> Das ist auch der Grund, warum für die Folgerung "rechter Pfeil hat Rechtsinverses => Sequenz zerfällt" gefordert wird, dass _alle_ Gruppen abelsch sind, obwohl für den Beweis nur Kommutativität der mittleren Gruppe benötigt wird.
* Offen-/Abgeschlossenheit einer Teilmenge eines CW-Komplexes kann man testen, indem man Offen-/Abgeschlossenheit in allen (abgeschlossenen) Zellen testet (der Beweis dazu steckt im Grunde in der Lösung zu B12/A2,3). 
Es genügt hingegen _nicht_ es auf den offenen Zellen zu testen (siehe z.B. S^1 in D^2)
* Eine Abbildung aus einem CW-Komplex heraus ist stetig genau dann, wenn sie stetig auf allen (abg.) Zellen ist (d.h. verknüpft mit den charakteristischen Abbildungen). Folgt aus vorheriger Aussage.


<h2>Besonders erinnerungswürdige Beispiele</h2>
* Berechnen der Fundamentalgruppe von Torus, Kleinscher Flasche und Projektivem Raum über Proposition aus dem Theorem von van Kampen. Die verschiedenen Verklebungen führen direkt zu den verschiedenen Relationen, die man am Ende aus Z*Z herausteilt.
* Der Beweis der Existenz einer Lebesgue-Zahl ist auch konstruktiv möglich (was "explizit" eine Lebesgue-Zahl liefert): Für Überdeckung V_j einer kompakten Menge K setze \varepsilon := min_{x \in K} max_{j \in J} dist(x, K \\ V_j) (min/max existieren wg. Stetigkeit von dist und Kompaktjeit von K (-> J endl.))


<h2>Besonders erinnerungswürdige Beweise</h2>
* Den Beweis für (hat Links/Rechts-Inverses) => (Sequenz zerfällt) kann man mit Hilfe des 5er-Lemmas deutlich verkürzen (nur einfache Richtung des Isos definieren - andere erhält man aus dem Lemma)


<h2>Fragen</h2>
* Was beweist man die Existenz und Eindeutigkeit des Liftes eines Pfades (evtl. auch allgemeiner einer Abbildung)?
* Sind die Funktoren einer Kategorienäquivalenz adjungiert.
* ist ___-Adjunktion transitiv? (Set <-> Grp <-> Ab => Set <-> Ab ?) Ist das Linksadjungierte zu einem Rechtsadjungierten eindeutig? (Set -> Grp -> Ab = Set -> Ab ?)
* Gilt: B zusammenziehbar => f.a. f,g: A -> B: f homotop g?
* Wie genau ist der Zusammenhang zwischen Überlagerungstheorie und Galoistheorie?
* Was heißt "endlich erzeugte Gruppe"?
* Was genau ist der Zusammenhang zwischen Currying und kartesisch abgeschlossenen Kategorien? (möglicherweise ist die Frage hier nur, wie man diese Frage sinnvoll stellen sollte?)
* Wie kann der (topologische) Quotientenraum als Kolimes verstanden werden?
* Was ist die "ad hoc"-Definition von d_1 im Komplex für die zelluläre Homologie?


<h1>ToDos</h1>
* Definition von Adjunktion (v. Funktoren) einfügen (DONE), Adjunktion verstehen
* alternative (Ko-)Limes-Definition verstehen (und anwenden!)
* Universelle Eigenschaften anschaulich verstehen (z.B. bei Tensorprodukten, Produkten, Limites...)
* Zusammenhangsübersicht um schwache Versionen ergänzen (Bspw. in "Topologie" von Jänich) + halb/semi lokal einfach zusammenhängend
* Gegenbeispiel zu lokal hausdorffsch => hausdorffsch finden (sonst würde der Begriff lokal kompakt und hausdorffsch keinen Sinn ergeben)
* Beweis aufschreiben für: X schw. hd.: A \subseteq X komp. abg <=> \forall K \subseteq X komp.: A \cap K abg in X (existiert bereits in handschriftlicher Form, verwendet, dass in hd-Räumen disjunkte abgeschlossene Teilmengen durch offene Umgebungen getrennt werden können).
* 5er-Lemma beweisen

* Übersicht der Zusammenhangsbegriffe erstellen. DONE: https://github.com/GraffL/Man-sieht-leicht.../blob/master/Topologie/Zusammenh%C3%A4nge%20von%20Zusammenhangsbegriffen.pdf
