O programa desenvolvido tem como objetivo analisar o comportamento vibracional de cadeias atômicas lineares compostas por 2, 3 e 4 massas conectadas por molas. Utilizando o método de resolução do problema de autovalores generalizado, o código calcula as frequências naturais de vibração e os modos normais associados a cada configuração. O modelo parte de uma matriz de rigidez 
𝐾
K construída conforme o número de massas e as conexões elásticas entre elas, sendo que a matriz de massa 
𝑀
M é diagonal.

Na configuração com duas massas, observa-se que quando 
𝑚
1
=
𝑚
2
m 
1
​
 =m 
2
​
 , os modos vibracionais assumem formas simétricas e as frequências são bem definidas. Contudo, ao introduzir uma diferença entre as massas, as frequências naturais se deslocam e os modos deixam de ser simétricos, revelando a sensibilidade do sistema à distribuição de massa.

Ao expandir para três massas, o sistema passa a apresentar três modos distintos, permitindo observar interações mais complexas entre os deslocamentos relativos. Variações nas massas novamente alteram significativamente a forma dos modos e os valores das frequências.

Na configuração com quatro massas, o código permite estudar também os efeitos de molas de segunda vizinhança (ligando 
𝑚
1
m 
1
​
  a 
𝑚
3
m 
3
​
  e 
𝑚
2
m 
2
​
  a 
𝑚
4
m 
4
​
 ). A introdução dessas conexões adicionais modifica consideravelmente as frequências naturais, principalmente as mais altas, e altera os modos normais, refletindo a influência de interações não-locais na dinâmica do sistema.

Fisicamente, isso ilustra como a vibração de átomos em sólidos pode ser afetada por vizinhos além dos mais próximos, o que é relevante em materiais reais. O programa oferece uma visualização clara desses efeitos e é uma excelente ferramenta didática para compreender vibrações em sistemas discretos.
