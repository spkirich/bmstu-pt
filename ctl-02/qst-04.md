# Вопрос № 04

Сформулировать аксиоматическое определение вероятности.
Сформулировать основные свойства вероятности.

## Определение

Пусть на пространстве элементарных исходов $\Omega$ определена
$\sigma$-алгебра событий $\mathfrak{B}$. **Вероятностью** называют
отображение $\mathbf{P} : \mathfrak{B} \rightarrow \mathbb{R}$,
удовлетворяющее следующим аксиомам.

Аксиома неотрицательности:

$$
\forall A \in \mathfrak{B} :
    \mathbf{P}(A) \geqslant 0.
$$

Аксиома нормированности:

$$
\mathbf{P}(\Omega) = 1.
$$

Расширенная аксиома сложения:

$$
\forall A_1, A_2, ... \in \mathfrak{B} :
    \mathbf{P}(A_1 + A_2 + ...) =
    \mathbf{P}(A_1) + \mathbf{P}(A_2) + ...
$$

**Вероятностью события** $A \in \mathfrak{B}$ называют
$\mathbf{P}(A)$.

## Свойства

Вероятность противоположного события:

$$
\forall A \in \mathfrak{B} :
    \mathbf{P}(\overline{A}) = 1 - \mathbf{P}(A).
$$

Вероятность невозможного события:

$$
\mathbf{P}(\varnothing) = 0.
$$

Сохранение порядка:

$$
\forall A, B \in \mathfrak{B} :
    A \subseteq B \Rightarrow
        \mathbf{P}(A) \leqslant \mathbf{P}(B).
$$

Ограниченность вероятности:

$$
\forall A \in \mathfrak{B} :
    0 \leqslant \mathbf{P}(A) \leqslant 1.
$$

Вероятность объединения двух событий:

$$
\forall A, B \in \mathfrak{B} :
    \mathbf{P}(A \cup B) = \mathbf{P}(A) + \mathbf{P}(B)
        - \mathbf{P}(A \cap B).
$$
