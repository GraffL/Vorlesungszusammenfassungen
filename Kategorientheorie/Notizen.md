<h1>Ergebnisse der <a href="http://math.stanford.edu/~vakil/threethings.html">Drei-Fragen-Challenge</a></h1>

<h2>Wichtige Ideen/Motivationen/Konzepte</h2>
* Wenn man Kategorien malt, malt man typischerweise den Köcher, deren freie Kategorie man meint. Wegen der Universalität der freien Kategorie genügt es dann für die Definition eines Funktors aus dieser Kategorie heraus, einen "Funktor" auf dem Köcher zu definieren. 
* Allgemeiner kann man eine Kategorie definieren durch einen Köcher und Relationen.	


<h2>Besonders erinnerungswürdige Definitionen</h2>
* ein Funktor F _bewahrt_ eine Eigenschaft eines Morphismus/Objektes, wenn gilt: f/X hat die Eigenschaft => F(f)/F(X) hat die Eigenschaft
* ein Funktor F _reflektiert_ eine Eigenschaft eines Morphismus/Objektes, wenn gilt: F(f)/F(X) hat die Eigenschaft => f/X hat die Eigenschaft
* ein Funktor F: C -> D _kreiert_ eine Eigenschaft eines Morphismus/Objektes, wenn gilt: g/Y \in D hat die Eigenschaft => es existiert f/X \in C mit dieser Eigenschaft und F(f)=g/F(X)=Y


<h2>Besonders erinnerungswürdige Sätze</h2>


<h2>Besonders erinnerungswürdige Beispiele</h2>

* zu natürlichen Transformationen und die Kategorie 2:
** Haben Kategorie C x 2 (2 ist die Kategorie 0->1). Dann gibt es zwei "natürliche" Einbettungsfunktoren T_0, T_1: C -> C x 2: X \mapsto (X,0) bzw. (X,1) und eine natürliche Transformation \eta: T_0 => T_1: \eta_X = (id_X, (0->1)).
** Haben wir umgekehrt zwei Funktoren F_0, F_1: C -> D und \delta 2 die Kategorie 0  1 (2 ohne den Morphismus zwischen 0 und 1). Dadurch erhalten wir einen Funktor F: C x \delta 2 -> D: (X, i) \mapsto F_i(X). Eine natürliche Transformation \zeta: F_0 => F_1 induziert dann eine Fortsetung von F auf  C x 2 -> D mittels F((f:X->Y), (0->1)) := (F_1(f) \circ \zeta_X = \zeta_Y \circ F_0(f): F_0(X)->F_1(Y))
** Startet man hingegen mit einem Funktor F: C x 2 -> D, so erhält man daraus zwei Funktoren F_0 := F \circ T_0 und F_1 := F \circ T_1 sowie eine natürliche Transformation  F \eta zwischen den beiden. 
** Das ganze entspricht der Anschauung von Homotopien als Füllungen von Quadraten/Zylindern


<h2>Besonders erinnerungswürdige Beweise</h2>
* Im Beweis des Eckmann-Hilton-Argumentes (gilt für zwei Verknüpfungen * und x, dass sie je ein neutrales Element haben und (a * b) x (c * d) = (a x c) * (b x d), so gilt: neutrale Elemente sind gleich, Verknüpfungen sind gleich, und die Verknüpfung(en) kommutier(en)):  
Man kann Verknüpfung * nebeneinander und x untereinander schreiben. Dann bedeutet die vorausgesetzte Identität, dass man das folgende Quadrat sowohl erst zeilen-, dann spaltenweise als auch erst erst spalten- und dann zeilenweise lesen lässt:  
		|---|---|
		| a | b |
		---------
		| c | d |
		|---|---|


<h2>Fragen</h2>


<h1>ToDos</h1>
