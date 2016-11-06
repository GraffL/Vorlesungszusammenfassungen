<h1>Ergebnisse der <a href="http://math.stanford.edu/~vakil/threethings.html">Drei-Fragen-Challenge</a></h1>

<h2>Wichtige Ideen/Motivationen/Konzepte</h2>
* Ziel der Algerbaischen Topologie: Finde Funktor A: TOP -> GRP
* Ziel der Homotpie Theorie: Finde algebraische Konstruktion A wie oben, die invariant unter bestimmten Homotoien ist
	Dann berechne A auf einfachen top. R�umen und Abbildungen und deformiere die eigentlich interessanten R�ume zu diesen einfacheren.
* F�hrt man kategorientheoretische Beweise �ber Hom-Mengen (-> Yoneda) statt �ber die Objekte selbst, arbeitet man automatisch in _Set_ (und kann also zu recht nur �ber Mengen nachdenken)
	(muss man daf�r dann aufpassen, dass die Hom-Mengen auch immer Mengen bleiben? Au�erdem m�sste man _Set_ kennen! ^^)
	

<h2>Besonders erinnerungsw�rdige Definitionen</h2>


<h2>Besonders erinnerungsw�rdige S�tze</h2>
* Die Pfade in einem topologischen Raum (modulo Homotopie) bilden (als algebraisches Objekt) einen Gruppoid, den Fundamentalgruppoid
* f, g: S^1->S^1: deg fg = deg f + deg g, denn: deg f = k => f homotop exp(2pi i k), deg g = l => ... =(Blatt 1/A4)=> fg homotop exp(2pi i (k+l)) => deg fg = k+l
* Eckmann-Hilton Argument: ...
* F�r eine ategorie C, x \in Ob C, definiere \pi_1(C,x) := Aut_C(x). Der Beweis des "konkreten" Theorems von van Kampen aus dem abstrakten Theorem geht dann v�llig analog.
* RP^1 hom�omorph S^1, f�r h�here Dimensionen stimmt das aber nicht mehr


<h2>Besonders erinnerungsw�rdige Beispiele</h2>
* Berechnen der Fundamentalgruppe von Torus, Kleinscher Flasche und Projektivem Raum �ber Proposition aus dem Theorem von van Kampen. Die verschiedenen Verklebungen f�hren direkt zu den verschiedenen Relationen, die man am Ende aus Z*Z herausteilt.
* Der Beweis der Existenz einer Lebesgue-Zahl ist auch konstruktiv m�glich (was "explizit" eine Lebesgue-Zahl liefert): F�r �berdeckung V_j einer kompakten Menge K setze \varepsilon := min_{x \in K} max_{j \in J} dist(x, K \\ V_j) (min/max existieren wg. Stetigkeit von dist und Kompaktjeit von K (-> J endl.))


<h2>Fragen</h2>
* Was beweist man die Existenz und Eindeutigkeit des Liftes eines Pfades (evtl. auch allgemeiner einer Abbildung)?
* Sind die Funktoren einer Kategorien�quivalenz adjungiert.
* ist ___-Adjunktion transitiv? (Set <-> Grp <-> Ab => Set <-> Ab ?) Ist das Linksadjungierte zu einem Rechtsadjungierten eindeutig? (Set -> Grp -> Ab = Set -> Ab ?)
* Gilt: B zusammenziehbar => f.a. f,g: A -> B: f homotop g?


<h1>ToDos</h1>
* Definition von Adjunktion (v. Funktoren) einf�gen, Adjunktion verstehen
* alternative (Ko-)Limes-Definition verstehen (und anwenden!)
* Universelle Eigenschaften anschaulich verstehen (z.B. bei Tensorprodukten, Produkten, Limites...)

* �bersicht der Zusammenhangsbegriffe erstellen. Done: https://github.com/GraffL/Man-sieht-leicht.../blob/master/Topologie/Zusammenh%C3%A4nge%20von%20Zusammenhangsbegriffen.pdf
