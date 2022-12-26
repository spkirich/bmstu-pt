# Вопрос 03

Сформулировать определение $\sigma$-алгебры событий, её основные свойства.

## Ответ

Пусть $\Omega$ &mdash; пространство элементарных исходов.

Непустое семейство $\mathfrak{B}$ подмножеств $\Omega$ называется
**$\sigma$-алгеброй** событий, если

$$
\forall A \in \mathfrak{B}:
\overline{A} \in \mathfrak{B};
$$

$$
\forall A_1, A_2, \ldots \in \mathfrak{B}:
A_1 \cup A_2 \cup \ldots \in \mathfrak{B}.
$$

Достоверное событие $\Omega \in \mathfrak{B}$:

$$
\forall A \in \mathfrak{B} : \Omega = A \cup \overline{A}.
$$

Невозможное событие $\varnothing \in \mathfrak{B}$:

$$
\varnothing = \overline{\Omega}.
$$
