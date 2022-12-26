# Вопрос 04

Сформулировать аксиоматическое определение вероятности, её основные свойства.

## Ответ

Пусть $\Omega$ &mdash; пространство элементарных исходов, $\mathfrak{B}$
&mdash; $\sigma$-алгебра событий над ним.

Отображение $\mathbf{P} : \mathfrak{B} \rightarrow \mathbb{R}$ называют
**вероятностью**, если

$$
\forall A \in \mathfrak{B}: \mathbf{P}(A) \geqslant 0;
$$

$$
\mathbf{P}(\Omega) = 1;
$$

$$
\forall A_1, A_2, \ldots \in \mathfrak{B}:
\mathbf{P}(A_1 + A_2 + \ldots) = \mathbf{P}(A_1) + \mathbf{P}(A_2) + \ldots
$$

Вероятность невозможного события:

$$
\mathbf{P}(\varnothing) = 0.
$$

Вероятность объединения двух событий:

$$
\forall A, B \in \mathfrak{B}:
\mathbf{P}(A \cup B) = \mathbf{P}(A) + \mathbf{P}(B) - \mathbf{P}(A \cap B).
$$

Вероятность противоположного события:

$$
\forall A \in \mathfrak{B}: \mathbf{P}(\overline{A}) = 1 - \mathbf{P}(A).
$$

Вероятность ограничена:

$$
\forall A \in \mathfrak{B}: 0 \leqslant \mathbf{P}(A) \leqslant 1.
$$

Вероятность сохраняет порядок:

$$
\forall A, B \in \mathfrak{B}:
A \subseteq B \Rightarrow \mathbf{P}(A) \leqslant \mathbf{P}(B).
$$
