# Вопрос 01

Сформулировать определения случайной величины и функции распределения
вероятностей случайной величины. Записать основные свойства функции
распределения.

## Ответ

Пусть $(\Omega, \mathfrak{B}, P)$ - вероятностное пространство.

Отображение $X : \Omega \rightarrow \mathbb{R}$
называют **случайной величиной**, если

$$
\forall x \in \mathbb{R}:
\{ \omega | \omega \in \Omega, X(\omega) < x \} \in \mathfrak{B}.
$$

Отображение $F_X : \mathbb{R} \rightarrow \mathbb{R}$
называют **функцией распределения вероятностей случайной величины** $X$, если

$$
\forall x \in \mathbb{R}:
F_X(x) = P \{ X < x \}.
$$

Функция распределения ограничена:

$$
\forall x \in \mathbb{R}:
0 \leqslant F_X(x) \leqslant 1.
$$

Функция распределения неубывает:

$$
\forall x_1 < x_2 \in \mathbb{R}:
F_X(x_1) \leqslant F_X(x_2).
$$

Функция распределения имеет пределы

$$
\lim_{t \rightarrow -\infty}
F_X(t) = 0,
$$

$$
\lim_{t \rightarrow +\infty}
F_X(t) = 1.
$$

Функция распределения непрерывна слева:

$$
\forall x \in \mathbb{R}:
F_X(x) = \lim_{t \rightarrow x - 0} F_X(t).
$$

Вероятность выражается через функцию распределения:

$$
\forall x_1 < x_2 \in \mathbb{R}:
P \{ x_1 \leqslant X < x_2 \} = F_X(x_2) - F_X(x_1).
$$
