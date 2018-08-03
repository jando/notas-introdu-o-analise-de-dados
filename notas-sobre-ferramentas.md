### Fazendo histogramas em Python

Para fazer um histograma em Python, você pode usar a biblioteca matplotlib, que vem com o Anaconda. O código a seguir fará um histograma de uma lista de exemplos de pontos de dados chamados dados.

```python
data = [1, 2, 1, 3, 3, 1, 4, 2]

%matplotlib inline
import matplotlib.pyplot as plt
plt.hist(data)
```

A linha %matplotlib inline é especificamente para o Jupyter notebook e faz com que seus gráficos apareçam em seu bloco de anotações em vez de uma nova janela. Se você não está usando o Jupyter notebook, você não deve incluir esta linha, e em vez disso você deve adicionar a linha plt.show () na parte inferior para mostrar o gráfico em uma nova janela.


### Cursos de Estatística

https://www.udacity.com/course/intro-to-descriptive-statistics--ud827

https://www.udacity.com/course/intro-to-inferential-statistics--ud201



## Correlação não implica em Causa

Exemplo:

Declaração de Correlação:
Estudantes que passam no primeiro projeto tem mais chances de visitar as aulas mais vezes na primeira semana.

Declaração de Causa:
Visitar as aulas com mais frequência faz com que os estudantes passem no primeiro projeto?

Ref: https://classroom.udacity.com/courses/ud170/lessons/5430778793/concepts/53961386570923


https://www.udacity.com/course/ab-testing--ud257