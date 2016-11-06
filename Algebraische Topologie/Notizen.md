<h1>Ergebnisse der <a href="http://math.stanford.edu/~vakil/threethings.html">Drei-Fragen-Challenge</a></h1>

<h2>Wichtige Ideen/Motivationen/Konzepte</h2>
* Ziel der Algerbaischen Topologie: Finde Funktor A: TOP -> GRP
* Ziel der Homotpie Theorie: Finde algebraische Konstruktion A wie oben, die invariant unter bestimmten Homotoien ist
	Dann berechne A auf einfachen top. Räumen und Abbildungen und deformiere die eigentlich interessanten Räume zu diesen einfacheren.
* Führt man kategorientheoretische Beweise über Hom-Mengen (-> Yoneda) statt über die Objekte selbst, arbeitet man automatisch in _Set_ (und kann also zu recht nur über Mengen nachdenken)
	(muss man dafür dann aufpassen, dass die Hom-Mengen auch immer Mengen bleiben? Außerdem müsste man _Set_ kennen! ^^)
	

<h2>Besonders erinnerungswürdige Definitionen</h2>


<h2>Besonders erinnerungswürdige Sätze</h2>
* Die Pfade in einem topologischen Raum (modulo Homotopie) bilden (als algebraisches Objekt) einen Gruppoid, den Fundamentalgruppoid
* f, g: S^1->S^1: deg fg = deg f + deg g, denn: deg f = k => f homotop exp(2pi i k), deg g = l => ... =(Blatt 1/A4)=> fg homotop exp(2pi i (k+l)) => deg fg = k+l
* Eckmann-Hilton Argument: ...
* Für eine ategorie C, x \in Ob C, definiere \pi_1(C,x) := Aut_C(x). Der Beweis des "konkreten" Theorems von van Kampen aus dem abstrakten Theorem geht dann völlig analog.
* RP^1 homöomorph S^1, für höhere Dimensionen stimmt das aber nicht mehr


<h2>Besonders erinnerungswürdige Beispiele</h2>
* Berechnen der Fundamentalgruppe von Torus, Kleinscher Flasche und Projektivem Raum über Proposition aus dem Theorem von van Kampen. Die verschiedenen Verklebungen führen direkt zu den verschiedenen Relationen, die man am Ende aus Z*Z herausteilt.
* Der Beweis der Existenz einer Lebesgue-Zahl ist auch konstruktiv möglich (was "explizit" eine Lebesgue-Zahl liefert): Für Überdeckung V_j einer kompakten Menge K setze \varepsilon := min_{x \in K} max_{j \in J} dist(x, K \\ V_j) (min/max existieren wg. Stetigkeit von dist und Kompaktjeit von K (-> J endl.))


<h2>Fragen</h2>
* Was beweist man die Existenz und Eindeutigkeit des Liftes eines Pfades (evtl. auch allgemeiner einer Abbildung)?
* Sind die Funktoren einer Kategorienäquivalenz adjungiert.
* ist ___-Adjunktion transitiv? (Set <-> Grp <-> Ab => Set <-> Ab ?) Ist das Linksadjungierte zu einem Rechtsadjungierten eindeutig? (Set -> Grp -> Ab = Set -> Ab ?)
* Gilt: B zusammenziehbar => f.a. f,g: A -> B: f homotop g?


<h1>ToDos</h1>
* Definition von Adjunktion (v. Funktoren) einfügen, Adjunktion verstehen
* alternative (Ko-)Limes-Definition verstehen (und anwenden!)
* Universelle Eigenschaften anschaulich verstehen (z.B. bei Tensorprodukten, Produkten, Limites...)

* Übersicht der Zusammenhangsbegriffe erstellen. Done: https://github.com/GraffL/Man-sieht-leicht.../blob/master/Topologie/Zusammenh%C3%A4nge%20von%20Zusammenhangsbegriffen.pdf
