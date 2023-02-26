## truth tables HW 7

Your grade will be put on a 10 point scale when it is posted in Canvas.

For 7.1, determine the truth values for each sentence, and then indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile. 

For 7.2 - 7.10, just indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile.

---


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="10" late-credit="8"}
7.1 P -> Q, Q -> R :|-: P <-> R
|   T T T     T T T   -   T T T
|   T T T     T F F   -   T F F
|   T F F     F T T   -   T T T
|   T F F     F T F   -   T F F
|   F T T     T T T   -   F F T
|   F T T     T F F   -   F T F
|   F T F     F T T   -   F F T
|   F T F     F T F   -   F T F

7.2 (P v Q) -> R, ~Q :|-: P->R
|   T T T   T T    F T -  T T T
|   T T T   F F    F T -  T F F
|   T T F   T T    T F -  T T T
|   T T F   F F    T F -  T F F
|   F T T   T T    F T -  F T T
|   F T T   F F    F T -  F T F
|   F F F   T T    T F -  F T T
|   F F F   T F    T F -  F T F

7.3 Q -> ~R, R v S :|-: S -> Q
|   T F F T   T T T -  T T T
|   T F F T   T T F -  F T T
|   T T T F   F T T -  T T T
|   T T T F   F F F -  F T T
|   F T F T   T T T -  T F F
|   F T F T   T T F -  F T F
|   F T T F   F T T -  T F F
|   F T T F   F F F -  F T F

7.4 ~P v ~Q, Q & S :|-: ~P
|   F T F F T  T T T - F T
|   F T F F T  T F F - F T
|   F T T T F  F F T - F T
|   F T T T F  F F F - F T
|   T F T F T  T T T - T F
|   T F T F T  T F F - T F
|   T F T T F  F F T - T F
|   T F T T F  F F F - T F

7.5 (PvS),~P->~S:|-:P&~S
| TTT FTTFT - TFFT
| TTF FTTTF - TTTF
| FTT TFFFT - FFFT
| FFF TFTTF - FFTF

7.6 ~P <-> Q, ~(Q & P) :|-: ~P
|   F T F T    F   T T T   - F T
|   F T T F    T   F F T   - F T
|   T F T T    T   T F F   - T F
|   T F F F    T   F F F   - T F

7.7 P -> (Q v ~P), P :|-: ~Q
|   T T   T T F T     T - F T
|   T F   F F F T     T - T F
|   F T   T T T F     F - F T
|   F T   F T T F     F - T F

7.8 ~(P v ~Q), Q v P :|-: P -> Q
| F   T T F T    T T T   -   T T T
| F   T T T F    F T T   -   T F F
| T   F F F T    T T F   -   F T T
| F   F T T F    F F F   -   F T F

7.9 (~P <-> Q) & P, P -> ~Q :|-: Q
|   F T F T   F T      T F F T   - T
|   F T T F   T T      T T T F   - F
|   T F T T   F F      F T F T   - T
|   T F F F   F F      F T T F   - F

7.10 M v N, M -> S, N -> T :|-: S v T
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

7.10 M v N, M -> S, N -> T :|-: S & T
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

&copy; 2023 Gregory Johnson

---
