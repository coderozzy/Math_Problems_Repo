# LISTA ZADAŃ NR 6: Podstawowe statystyki i ich rozkłady

## Zadanie 1 (Szereg rozdzielczy)
Z populacji generalnej pobrano $n=50$-elementową próbkę (wyniki pomiarów). Otrzymano następujące wyniki surowe:
$$3.6, 5.0, 4.0, 4.7, 5.2, 5.9, 4.5, 5.3, 5.5, 3.9,$$
$$5.6, 3.5, 5.4, 5.2, 4.1, 5.0, 3.1, 5.8, 4.8, 4.4,$$
$$4.6, 5.1, 4.7, 3.0, 5.5, 6.1, 3.8, 4.9, 5.6, 6.1,$$
$$5.9, 4.2, 6.4, 5.3, 4.5, 4.9, 4.0, 5.2, 3.3, 5.4,$$
$$4.7, 6.4, 5.1, 3.4, 5.2, 6.2, 4.4, 4.3, 5.8, 3.7.$$

Na podstawie tych danych:
a) Sporządzić szereg rozdzielczy, przyjmując liczbę klas $k=7$.
b) Wyznaczyć rozstęp $R$ oraz długość klasy $b$.
*(Dane pochodzą z Zadania 1.1, Krysicki Cz. II, str. 7)*.

## Zadanie 2 (Miary położenia)
Dla próbki z Zadania 1, po uporządkowaniu wyników rosnąco:
$$3.0, 3.1, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8, 3.9, 4.0, 4.0, 4.1, 4.2, 4.3, 4.4, 4.4, 4.5, 4.5, 4.6, 4.7,$$
$$4.7, 4.7, 4.8, 4.9, 4.9, 5.0, 5.0, 5.1, 5.1, 5.2, 5.2, 5.2, 5.2, 5.3, 5.3, 5.4, 5.4, 5.5, 5.5, 5.6,$$
$$5.6, 5.8, 5.8, 5.9, 5.9, 6.1, 6.1, 6.2, 6.4, 6.4.$$

Wyznaczyć:
a) **Medianę** ($m_e$) – wartość środkową.
b) **Modę** ($m_o$) – wartość najczęstszą.
c) Porównać, czy w tym przypadku $m_e \approx \bar{x}$ (gdzie $\bar{x} = 4.844$).
*(Dane uporządkowane wg Zadania 1.10, Krysicki Cz. II, str. 14)*.

## Zadanie 3
W pewnym eksperymencie chemicznym (lub procesie produkcji procesorów) badano ilość czystej substancji. Dla 5 pomiarów otrzymano wyniki: $3.5, 3.4, 2.1, 5.4, 1.1$.

Obliczyć:

a) Średnią arytmetyczną z próby $\bar{x}$.
b) Wariancję z próby $s^2$ (używając wzoru dla małej próby).
c) Odchylenie standardowe $s$.

## Zadanie 4
Pojazd (lub pakiet danych w sieci) przebył drogę złożoną z trzech odcinków o tej samej długości, ale z różnymi prędkościami: $v_1=50, v_2=60, v_3=70$ km/h. Obliczyć średnią prędkość na całej trasie.

*Wskazówka: Należy użyć średniej harmonicznej, a nie arytmetycznej.*

## Zadanie 5
Dane są dwie sześcioelementowe próbki (np. czasy dostępu do dwóch różnych dysków):

* Próbka I: $80, 40, 40, 80, 40, 80$
* Próbka II: $40, 80, 120, 80, 120, 40$

Obliczyć współczynniki zmienności $v = \frac{s}{\bar{x}}$ dla obu próbek. Który dysk działa bardziej stabilnie (ma mniejszy rozrzut względny)?

## Zadanie 6
Znaleźć przedział ufności (lub prawdopodobieństwo), wiedząc, że badana cecha $X$ populacji ma rozkład normalny $N(\mu, \sigma)$. Statystyka $U$:

$$
U = \frac{\bar{X} - \mu}{\sigma} \sqrt{n}
$$

ma rozkład $N(0,1)$.

## Zadanie 7
Wylosowano małą próbkę ($n=10$) z populacji o rozkładzie normalnym. Ponieważ nie znamy odchylenia standardowego populacji $\sigma$, musimy użyć odchylenia z próby $s$. Statystyka:

$$
t = \frac{\bar{X} - \mu}{s} \sqrt{n-1}
$$

podlega rozkładowi **t-Studenta**. Odczytać z tablic wartość krytyczną dla $n-1$ stopni swobody i poziomu ufności $0.95$.

## Zadanie 8
Dla badania wariancji (rozrzutu) próby stosuje się statystykę:

$$
\chi^2 = \frac{nS^2}{\sigma^2}
$$

> *Uwaga: Symbol $S^2$ oznacza wariancję z próby liczoną ze wzoru z dzieleniem przez $n$ (zgodnie z definicją w podręczniku Krysickiego).*

która ma rozkład chi-kwadrat. Wykonano 15 pomiarów ($n=15$). Odczytać z tablic wartości, między którymi z prawdopodobieństwem $0.90$ znajdzie się ta statystyka.

## Zadanie 9
Wykazać na prostym przykładzie liczbowym, że średnia z próby $\bar{X}$ jest **estymatorem nieobciążonym** średniej w populacji (czyli $E(\bar{X}) = \mu$), natomiast wariancja z próby (dzielona przez $n$) jest obciążona (dlatego dzielimy przez $n-1$).

## Zadanie 10
Dla małej próbki: $0.18, 0.56, 0.87, 1.37, 2.46$ wyznaczyć wartości dystrybuanty empirycznej $S_n(x)$.