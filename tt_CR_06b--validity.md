## truth tables, assignment 7b (at-home)

---

Each problem is worth 10 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 8 points. Your grade will be put on a 10 point scale when it is posted in Canvas.

<span style="color:blue">**Do this alone, and don't discuss it with anyone who hasn't done it.**</span>

For each, indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile.

---

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="10" late-credit="8"}
7.6 P -> Q, Q -> R :|-: P <-> R
|   T T T     T T T   -   T T T
|   T T T     T F F   -   T F F
|   T F F     F T T   -   T T T
|   T F F     F T F   -   T F F
|   F T T     T T T   -   F F T
|   F T T     T F F   -   F T F
|   F T F     F T T   -   F F T
|   F T F     F T F   -   F T F

7.7 (P v Q) -> R, ~Q :|-: P->R
|   T T T   T T    F T -  T T T
|   T T T   F F    F T -  T F F
|   T T F   T T    T F -  T T T
|   T T F   F F    T F -  T F F
|   F T T   T T    F T -  F T T
|   F T T   F F    F T -  F T F
|   F F F   T T    T F -  F T T
|   F F F   T F    T F -  F T F

7.8 Q -> ~R, R v S :|-: S -> Q
|   T F F T   T T T -  T T T
|   T F F T   T T F -  F T T
|   T T T F   F T T -  T T T
|   T T T F   F F F -  F T T
|   F T F T   T T T -  T F F
|   F T F T   T T F -  F T F
|   F T T F   F T T -  T F F
|   F T T F   F F F -  F T F

7.9 ~P v ~Q, Q & S :|-: ~P
|   F T F F T  T T T - F T
|   F T F F T  T F F - F T
|   F T T T F  F F T - F T
|   F T T T F  F F F - F T
|   T F T F T  T T T - T F
|   T F T F T  T F F - T F
|   T F T T F  F F T - T F
|   T F T T F  F F F - T F

7.10 (PvS),~P->~S:|-:P&~S
| TTT FTTFT - TFFT
| TTF FTTTF - TTTF
| FTT TFFFT - FFFT
| FFF TFTTF - FFTF

7.11 ~P <-> Q, ~(Q & P) :|-: ~P
|   F T F T    F   T T T   - F T
|   F T T F    T   F F T   - F T
|   T F T T    T   T F F   - T F
|   T F F F    T   F F F   - T F

7.12 P -> (Q v ~P), P :|-: ~Q
|   T T   T T F T     T - F T
|   T F   F F F T     T - T F
|   F T   T T T F     F - F T
|   F T   F T T F     F - T F

7.13 ~(P v ~Q), Q v P :|-: P -> Q
| F   T T F T    T T T   -   T T T
| F   T T T F    F T T   -   T F F
| T   F F F T    T T F   -   F T T
| F   F T T F    F F F   -   F T F

7.14 (~P <-> Q) & P, P -> ~Q :|-: Q
|   F T F T   F T      T F F T   - T
|   F T T F   T T      T T T F   - F
|   T F T T   F F      F T F T   - T
|   T F F F   F F      F T T F   - F

7.15 M v N, M -> S, N -> T :|-: S v T
|   T T T   T T T   T T T   -   T T T
|   T T T   T T T   T F F   -   T T F
|   T T T   T F F   T T T   -   F T T
|   T T T   T F F   T F F   -   F F F
|   T T F   T T T   F T T   -   T T T
|   T T F   T T T   F T F   -   T T F
|   T T F   T F F   F T T   -   F T T
|   T T F   T F F   F T F   -   F F F
|   F T T   F T T   T T T   -   T T T
|   F T T   F T T   T F F   -   T T F
|   F T T   F T F   T T T   -   F T T
|   F T T   F T F   T F F   -   F F F
|   F F F   F T T   F T T   -   T T T
|   F F F   F T T   F T F   -   T T F
|   F F F   F T F   F T T   -   F T T
|   F F F   F T F   F T F   -   F F F

7.16 M v N, M -> S, N -> T :|-: S & T
|   T T T      T T T      T T T   -   T T T
|   T T T      T T T      T F F   -   T F F
|   T T T      T F F      T T T   -   F F T
|   T T T      T F F      T F F   -   F F F
|   T T F      T T T      F T T   -   T T T
|   T T F      T T T      F T F   -   T F F
|   T T F      T F F      F T T   -   F F T
|   T T F      T F F      F T F   -   F F F
|   F T T      F T T      T T T   -   T T T
|   F T T      F T T      T F F   -   T F F
|   F T T      F T F      T T T   -   F F T
|   F T T      F T F      T F F   -   F F F
|   F F F      F T T      F T T   -   T T T
|   F F F      F T T      F T F   -   T F F
|   F F F      F T F      F T T   -   F F T
|   F F F      F T F      F T F   -   F F F
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>

---
