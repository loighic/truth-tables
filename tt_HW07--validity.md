## truth tables HW 7

Each problem is worth 20 points, and the whole assignment is worth 100 points. Problems that are submitted late will receive 16 points. Your grade will be put on a 10 point scale when it is posted in Canvas.

For 7.1, determine the truth values for each sentence, and then indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile. 

For 7.2 - 7.5, just indicate whether the line is a good or a bad one by putting a `✓` or an `✗` under the turnstile.

---


~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash autoAtoms" points="20" late-credit="16"}
7.1 (P v Q) -> R, ~Q :|-: P->R
7.1 (A v ~B) -> C, B :|-: A->C
7.1 (P & T) -> ~R, T :|-: P->R
~~~

~~~{.TruthTable .Validity system="magnusSL" options="turnstilemark nocounterexample nodash" points="10" late-credit="8"}
7.2 Q -> ~R, R v S :|-: S -> Q
| F T F F T T T - T F T
| F T F F T T F - F F T
| F T T T F F F - T F T
| F T T T F F F - F F T
| T F T F T T T - T T F
| T F T F T T F - F T F
| T F T T F F F - T T F
| T F T T F F F - F T F

7.3 ~P v ~Q, Q & S :|-: ~P
|   F T F F T  T T T - F T
|   F T F F T  T F F - F T
|   F T T T F  F F T - F T
|   F T T T F  F F F - F T
|   T F T F T  T T T - T F
|   T F T F T  T F F - T F
|   T F T T F  F F T - T F
|   T F T T F  F F F - T F

7.4 (PvS),~P->~S:|-:P&~S
| TTT FTTFT - TFFT
| TTF FTTTF - TTTF
| FTT TFFFT - FFFT
| FFF TFTTF - FFTF

~~~








&copy; 2023 Gregory Johnson

---
