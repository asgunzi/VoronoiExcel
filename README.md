# VoronoiExcel
Implementação do Diagrama de Voronoi - Excel VBA


# Diagramas Voronoi em Excel – e retalhonamento de áreas

Diagramas de Voronoi são diagramas bonitos como o seguinte.

Cada região tem um centro, escolhido aleatoriamente, e cada região denota a influência de cada centro.

É possível fazer uma dessas, em Excel.


![](https://ideiasesquecidas.files.wordpress.com/2021/04/voronoi01.png)

De forma genérica, um Diagrama de Voronoi começa com um número de regiões.

Para cada região, é sorteado um centro, em coordenadas x e y.

Depois, para cada pixel da área total, é calculada a distância para cada centro da região. O pixel pertence à região mais próxima.

O caso mais fácil possível é o de duas regiões, exemplificado abaixo.

![](https://ideiasesquecidas.files.wordpress.com/2021/04/voronoi02.png)

Com 3 regiões:
![](https://ideiasesquecidas.files.wordpress.com/2021/04/voronoi03.png)

Vide arquivo no Github: https://github.com/asgunzi/VoronoiExcel. É necessário ativa macros.

![](https://ideiasesquecidas.files.wordpress.com/2021/04/voronoi04.png)

Eu achava que essa era apenas uma curiosidade, porém, vi recentemente algumas aplicações bem interessantes.

![](https://ideiasesquecidas.files.wordpress.com/2021/04/reformaagraria.jpg)

Uma é de reforma agrária. A forma normal de dividir regiões é manualmente, como a da esquerda. Porém há áreas melhores e piores – digamos, em termos de acesso à estrada (em preto), declividade, qualidade do solo.

Hoje em dia, é possível levantar informações topográficas precisas. Aplicando um Voronoi aperfeiçoado, é possível redividir regiões de forma justa para o INCRA: alguém com uma região melhor vai ter menos área, enquanto outra com condições piores tem mais área, segundo restrições mapeadas.

Na área florestal, um projeto em andamento é o de retalhonar áreas de acordo com faixas de declividade e linhas de plantio, por exemplo, para que os talhões sejam ótimos operacionalmente e homogêneos para critérios de silvicultura e colheita.

Vide também:

http://alexbeutel.com/webgl/voronoi.html

https://ideiasesquecidas.com/laboratorio-de-matematica/
