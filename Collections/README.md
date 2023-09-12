# Collections Java

- Parte teórica

Códigos de exemplo retirados do curso de Fundamentos da Programação Orientada a Objetos com Java da DIO professora ![Camila Cavalcante](link github).

## Collection Framework API

- **Collection:** é uma estrutura de dados que serve para agrupar muitos elementos em uma única unidade. Tais elementos são objetos **(ou seja, não aceita tipo primitivo, int---> Integer; double ---> Double; String=String...)**;

- Uma collection pode ter coleções **homogênias e heterogêneas**, mais comum serem homogêneas (contém um tipo específico). Usando herança por exemplo, poderia ter as classes Veiculo, Carro extands Veiculo e Moto extands Veiculo. Neste caso um array (coleção) de veículo seria uma coleção heterogênia, enquanto um array de carro ou array de moto são homogêneos.

- O **núcle principal** das coleções é formado pelas interfaces que permitem manipular a coleção independemente do nível de detalhe que elas representam;

- Existem **4 tipos de collections** das quais pode-se ter subclasses que implementam várias formas diferentes de se trabalhar com cada uma das coleções, são elas

**List** (lista):

**Set** (conjunto):

**Queue** (fila):

**Map** (mapa):

![Hierarquia de coleções](image.png)

- Todas essas classes e interfaces estão dentro do package java.util;

- Embora a interface Map não seja filha direta da interface Collection, ela também é considerada uma coleção devido às suas funções.
