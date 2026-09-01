# LC Circuit Simulator

A simple interactive LC circuit simulator built with HTML, CSS, JavaScript, and Canvas.

## What does it show

- Q(t): charge
- I(t): current
- U_E: electric energy
- U_B: magnetic energy

## Parameters

- L: Inductance (H)
- C: Capacitance (F)
- R: Resistance (Ω)
- Q0: Initial charge (C)
- T: Time window (s)
- Speed: Animation speed

## Physics

- ω0 = 1 / sqrt(LC)
- γ = R / (2L)
- R = 0: undamped oscillation
- R > 0: damped response

## Notes

Ideal components only. Initial current is zero. No external AC source.
