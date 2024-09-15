java c
Lineare Algebra II
Ubungsblatt 11
SS 2024
Aufgabe 1. Sei n ∈ N>0. Gegeben sei die Matrix

a) Zeigen Sie, dass A orthogonal ist. Offensichtlich ist A auch symmetrisch. Was verr¨at Ihnen das ¨uber die Eigenwerte von A? Begr¨unden Sie Ihre Antwort.
b) Berechnen Sie die Spur von A. Was verr¨at Ihnen das ¨uber die Dimension der Eigenr¨aume von A? Begr¨unden Sie Ihre Antwort.
c) Finden Sie einen Eigenvektor zum Eigenwert 1, und beschreiben Sie die lineare Abbildung A geometrisch.
[Hinweis: Eigenwerte und Eigenvektoren k¨onnen hier ohne viel Rechenaufwand bestimmt werden.]
Aufgabe 2. Es sei V = Rn versehen mit dem Standardskalarprodukt ⟨·, ·⟩.
a) Sei f : V → R eine lineare Abbildung. Zeigen Sie, dass es einen eindeutig bestimmten Vektor w ∈ V gibt mit der Eigenschaft
⟨w, v⟩ = f(v)
f¨ur alle v ∈ V .
[Hinweis: Sie k¨onnen den Ansatz w =Pni=1 λibi machen, mit λ1, . . . , λn ∈ R und b1, . . . , bn eine Orthonormalbasis von V .]
F¨ur v1, . . . , vn−1 ∈ V sei q(v1, . . . , vn−1) ∈ V derjenige Vektor mit
⟨q(v1, . . . , vn−1), v⟩ = det(v, v1, . . . , vn−1)
f¨ur alle v ∈ V .
b) Zeigen Sie, dass q eine wohldefinierte Abbildung Vn−1 → V ist. Fortan schreiben wir
v1 × · · · × vn−1 := q(v1, . . . , vn−1).
c) Zeigen Sie, dass v1 × · · · × vn−1 orthogonal zu v1, . . . , vn−1 ist.
d) Zeigen Sie: Sind v1, . . . , vn−1 linear unabh¨angig, so ist {v1 × · · · × 代 写Lineare Algebra II Ubungsblatt 11
代做程序编程语言vn−1, v1, . . . , vn−1} eine Basis von V .
Bemerkung: Man nennt v1 × · · · × vn−1 das verallgemeinerte Kreuzprodukt von v1, . . . , vn−1. F¨ur n = 3 ergibt sich das gew¨ohnliche Kreuzprodukt V × V → V , bekannt aus Schule, Physik, usw.
Aufgabe 3. a) Sei V = Rn mit dem Standardskalarprodukt ⟨·, ·⟩. Sei v, w ∈ V mit v = w und ∥v∥ = ∥w∥. Zeigen Sie, dass es eine Spiegelung Sb gibt (b ∈ Rn\{0}) sodass Sb(v) = w.
[Hinweis: Es lohnt sich 2⟨v − w, v⟩ = ∥v − w∥2zu zeigen.]
b) Zeigen Sie, dass jede Matrix A ∈ O(n), A ≠ En ein Produkt aus h¨ochstens n Spiegelungen ist.
[Hinweis: Sei A = (a1, . . . , an) ≠ En in Spaltenschreibweise. Zeigen Sie, dass es ein Sb gibt mit Sb(ai) = e1 f¨ur ein i. Bestimmen Sie SbA und schließen Sie per Induktion.]
Aufgabe 4. Sei (V,⟨·, ·⟩) ein endlich dimensionaler Euklidischer oder unit¨arer Vektorraum, und f ∈ EndK(V ) (wobei K = R im Euklidischen und K = C im unit¨aren Fall). Es gibt dann eine lineare Abbildung f∗ ∈ EndK(V ) die eindeutig durch die Eigenschaft
⟨f∗(v), w⟩ = ⟨v, f(w)⟩ f¨ur alle v, w ∈ V                          (1)
bestimmt ist. Die Existenz und Eindeutigkeit von f* wird in der Vorlesung gezeigt. Zeigen Sie, nur unter der Verwendung von (1), dass f¨ur alle f, g ∈ EndK(V ) und λ ∈ K gilt:
a) (f + g)* = f* + g*
b) (λf)* = ¯λf*
c) (f ◦ g)* = g* ◦ f*
d) (f*)* = f.







         
加QQ：99515681  WX：codinghelp
