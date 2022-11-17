# Вопрос № 03

Сформулировать определение $\sigma$-алгебры событий.
Сформулировать её основные свойства.

## Определение

Непустое семейство $\mathfrak{B}$ подмножеств пространства
элементарных исходов $\Omega$ называется **$\sigma$-алгеброй**
событий, если

$$
\forall A \in \mathfrak{B} :
    \overline{A} \in \mathfrak{B};
$$

$$
\forall A_1, A_2, ..., A_i, ... \in \mathfrak{B} :
    A_1 \cup A_2 \cup ... \cup A_i \cup ... \in \mathfrak{B}.
$$

## Свойства

Достоверное событие $\Omega \in \mathfrak{B}$:

$$
\forall A \in \mathfrak{B} : \Omega = A \cup \overline{A}.
$$

Невозможное событие $\varnothing \in \mathfrak{B}$:

$$
\varnothing = \overline{\Omega}.
$$
