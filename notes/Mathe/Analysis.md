---
title: "Analysis"
subject: "Mathe"
tags: ["Rechengesetze"]
difficulty: "mittel"
updated: "2026-09-17"
---

# Analysis

## Grundlagen

### Ableiten

| Ableitungsregel | Funktion | Ableitung |
|---|---|---|
| Konstantenregel | $y = C$ | $y' = 0$ |
| Faktorregel | $y = x^n$ | $y' = n \cdot x^{n-1}$ |
| Potenzregel | $y = a \cdot f(x)$ | $y' = a \cdot f'(x)$ |
| Summenregel | $y = u + v$ | $y' = u' + v'$ |
| Differenzregel | $y = u - v$ | $y' = u' - v'$ |
| Produktregel | $y = u \cdot v$ | $y' = u' \cdot v + u \cdot v'$ |
| Quotientenregel | $y = u \div v$ | $y' = \dfrac{u' \cdot v - u \cdot v'}{v^2}$ |
| Kettenregel | $y = u(v(x))$ | $y' = u'(v(x)) \cdot v'(x)$ |

### Schnittpunkte

1. Funktionen gleichsetzen
2. Nach $x$ auflösen
3. Funktionswerte ausrechnen

### Tangenten-/Normalengleichung

**Tangente:**
1. Ableiten und Steigung an der $x$-Stelle der Tangenten ausrechnen
2. $x$-Stelle einsetzen und Punkt bestimmen
3. In $y = mx + c$ einsetzen und nach $c$ auflösen

**Normale:**
1. Steigung bestimmen: $m(N) = -\dfrac{1}{m(T)}$
2. $m$ in Tangentengleichung austauschen

### Intervalle

$I(x;x]$

| Klammer | Bedeutung |
|---|---|
| $($ | eingeschlossen bzw. $\leq$ |
| $[$ | ausgeschlossen bzw. $<$ |

### Lokale Extremstellen

1. **Notwendige Bedingung:** Die Ableitung bzw. die Steigung von $f$ muss an der gegebenen Stelle $0$ betragen
2. **Hinreichende Bedingung (a):** Vorzeichenwechsel → entsprechende lokale Extremstelle
3. **Hinreichende Bedingung (b):**
   - $f''(x) > 0$ → lokales Minimum
   - $f''(x) < 0$ → lokales Maximum

### Wendepunkte

Extremstelle in der zweiten Ableitung

### Monotonie

| Verhalten | Bedingung |
|---|---|
| Streng monoton wachsend | für alle Funktionswerte im Intervall gilt: $f'(x) > 0$ |
| Streng monoton fallend | für alle Funktionswerte im Intervall gilt: $f'(x) < 0$ |

**Limes:** noch nicht fertig

---

## Lineare Gleichungen

- **Funktionsterm:** $f(x) = mx + c$
- **Lösungsweg:** nach $x$ umstellen

**Verlauf:** 

![Lineare Gleichung Verlauf](notes/images/mathe/LineareGleichungVerlauf.png)

---

## Quadratische Gleichungen

- **Funktionsterm:** $f(x)=ax^2+bx+c$ (Normalform, zum Rechnen)
- $f(x)=a(x-d)^2+e$ (Scheitelpunktform)

**Lösungsweg:**

1. **pq-Formel** (wenn $a=1$ und $f(x)=0$):

$$x_{1,2} = -\frac{p}{2} \pm \sqrt{\left(\frac{p}{2}\right)^2 - q}$$

2. **Mitternachtsformel:**

$$x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$

**Verlauf:**

![Quadratische Gleichung Verlauf](notes/images/mathe/QuadratischeGleichungVerlauf.png)

**Anzahl der Lösungen:** Diskriminante $D = b^2-4ac$

| Diskriminante | Anzahl Lösungen |
|---|---|
| $D > 0$ | 2 verschiedene Lösungen |
| $D = 0$ | 1 doppelte Lösung |
| $D < 0$ | keine reelle Lösung |

**Scheitelpunkt/Symmetrieachse:** $x_s = \dfrac{b}{2a}$

---

## Bruchgleichungen

- **Funktionsterm (Beispiel):** $\dfrac{1}{x-1} = 4$

**Lösungsweg:**
1. Definitionsmenge bestimmen → **Nenner darf nie 0 sein** (hier: $x \neq 1$)
2. Nach $x$ auflösen

**Verlauf:**

![Bruchgleichung Verlauf](notes/images/mathe/BruchGleichungVerlauf.png)

---

## Potenzgleichung

- **Funktionsterm:** $f(x) = x^n$
- **Lösungsweg:** entsprechende Wurzel ziehen (bei geradem Exponenten zwei Lösungen)

**Verlauf:**

![Potenzgleichung Verlauf](notes/images/mathe/PotenzGleichungVerlauf.png)

---

## Exponentialgleichung

- **Funktionsterm:** $f(x) = a \cdot b^x$

**Lösungsweg:**
1. Gleiche Basis herstellen, z. B.: $2^x = 16 = 2^4$

**Logarithmus** (löst Exponentialgleichungen):

![Loesungsweg Logarithmus Verlauf](notes/images/mathe/LogarithmusLoesungsweg.png)


**Verlauf** (Vergleich $f(x) = 5^x$, $f(x) = 2^x$, $f(x) = 1{,}5^x$):

| $x$ | −2 | −1 | 0 | 1 | 2 |
|---|---|---|---|---|---|
| $5^x$ | 0,04 | 0,2 | 1 | 5 | 25 |
| $2^x$ | 0,25 | 0,5 | 1 | 2 | 4 |
| $1{,}5^x$ | 0,44 | 0,67 | 1 | 1,5 | 2,25 |

![Exponentialgleichung Verlauf](notes/images/mathe/ExponentialGleichungVerlauf.png)

---

## Wurzelgleichung

- **Funktionsterm:** $f(x) = \sqrt[n]{x} = x^{\frac{1}{n}}$

**Lösungsweg:**
1. Definitionsmenge bestimmen (unter der Wurzel $\geq 0$)
2. Wurzel isolieren
3. Wurzel auflösen
4. Nach $x$ auflösen
5. **Probe!**

**Verlauf:**

![Wurzelgleichung Verlauf](notes/images/mathe/WurzelGleichungVerlauf.png)

---

## Sinusfunktion

- **Funktionsterm:** $f(x) = a \cdot \sin(b(x-c)) + d$

| Parameter | Bedeutung |
|---|---|
| $a$ | Streckung in $y$-Richtung |
| $b$ | Streckung in $x$-Richtung |
| $c$ | Verschiebung in $x$-Richtung |
| $d$ | Verschiebung in $y$-Richtung |

- **Wertebereich $W$:** $[\text{globales Minimum}; \text{globales Maximum}]$
- **Mittellinie:** $y = d$
- **Ableitungen:** $\sin(x) \to \cos(x) \to -\sin(x) \to -\cos(x) \to \sin(x)$
  - Streng monoton wachsend: für alle Funktionswerte im Intervall gilt: $f'(x) > 0$