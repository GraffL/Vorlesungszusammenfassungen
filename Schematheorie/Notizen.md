<h1>Ergebnisse der <a href="http://math.stanford.edu/~vakil/threethings.html">Drei-Fragen-Challenge</a></h1>

<h2>Wichtige Ideen/Motivationen/Konzepte</h2>
* Um einen Raum zu verstehen, betrachten wir den Ring (kommutativ mit 1) der Funktionen auf diesem Raum
	Ziel: Ausgehend von einem Ring, definiere eine Menge mit einer Topologie, sodass der Raum der globalen Funktionen darauf dem urspr�nglichen Ring entspricht -> Schema?
* Schemata sehen lokal aus wie Spec A
* Zeichnet man Bilder von Spec, so zeichnet man jeweils den topologischen Abschluss der Primideale


<h2>Wichtige Beispiele</h2>
* K[X] lokalisiert an {X^n | n \in \IN} ergibt die Laurent-Polynome
	
	
<h2>Besonders erinnerungsw�rdige Definitionen</h2>
* Ist f \in A, p \in Spec A, so bezeichnet man [f] \in A/p als _Wert von f in p_
	Motivation daf�r: A := C(X), p \in X, I_p := {g \in C(X) | g(p)=0} Ideal in A -> C(X)/I_p isomorph zu |R via Einsetzen von p
	d.h. der "Wert" [f] entspricht dem Wert f(p)
  Gilt f \in p, so sagt man _f verschwindet in p_
	F�r f \in I_p verschwindet [f] "=" f(p) = 0

	
<h2>Besonders erinnerungsw�rdige S�tze</h2>
* D(f) = Spec A_f, O_{Spec A, p} := (O_{Spec A})_p = A_p
* V: Ideale -> abg. Mengen: J -> V(J); I: (abg) Mengen -> Ideale: M -> {a \in A | a|_M = 0} => I\circ V(J) = \sqrt(J)


<h2>Fragen</h2>
* Wie h�ngen die Grundlegenden Ideen der Schematheorie mit dem Satz v. Gelfand-Neumark zusammen?
* Sind Verschwindungsmengen (algebraisch) irreduzibler Polynome (topologisch) irreduzibel?
* Wie sind Garben kategorientheoretisch definiert?
* Sind V, I Funktoren? (falls ja, adjungiert? ...?) Folgt daraus irgendetwas interessantes?
* Was bedeutet "Pr�garbe auf einer Basis (eines topologischen Raumes)"?
* Anscheinend sind Morphismen zwischen geringten R�umen C^\infty(M) und C^\infty(N), f�r diff'bare Mfgen M und N, gerade die differenzierbaren Abbildungen zwischen diesen Mfgen. Stimmt das? Und falls ja, warum?


<h1>ToDos</h1>
* Beweise: Ist A nullteilerfrei, so ist (0) ein Primideal und liegt dicht in Spec A (d.h. der topologische Abschluss von (0) bzgl. der Zariski-Topologie ist Spec A).
* Zeige die Wohldefiniertheit der Lokalisierung
* Erstelle �bersicht zu V(f), D(f), O_X(D(f)), ... f�r den Fall A = C(X)
 -> in diesem Zusammenhang auch interessant: Identit�ten wie D(fg) = D(f) \cap D(g), ...

* �bersicht zu Bildern von Spec erstellen ~"done": https://github.com/GraffL/Vorlesungszusammenfassungen/blob/master/Schematheorie/Anschauung%20f%C3%BCr%20Spec.pdf 