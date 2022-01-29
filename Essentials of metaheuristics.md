# Essentials of metaheuristics

Краткий конспект книги [https://cs.gmu.edu/~sean/book/metaheuristics/Essentials.pdf](https://cs.gmu.edu/~sean/book/metaheuristics/Essentials.pdf) с моими заметками.



## Gradient-based Optimization

### Градиентный спуск

Идём в направлении градиента. Шаг равен либо $\alpha \norm{\gradient f(\vec{x})}$, либо происходит line-search по функции в этом напрпавлении.

### Метод Ньютона

Инвартируем Гессиану, умножаем на вектор градиента, получается условно касательная. Сходится не только к минимуму, но и к максимуму и седловым точкам.

