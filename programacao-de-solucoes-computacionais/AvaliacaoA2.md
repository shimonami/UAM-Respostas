### Questão 1
Observe o código abaixo, escrito em linguagem de programação Java.

 ```java
public class HelloWorldMetodos {
  static void olaMetodos (){
    System.out.println ('Sou um novo método!');
  }

  public static void main(String[] args) {
    System.out.println ('Começando a execução do programa.');
    olaMetodos();
    System.out.println ('Terminando a execução do programa.');
  }
}
```


Com base na estrutura apresentada, avalie as afirmações a seguir.

I. Apesar de estar elencado no código fonte, a saída 'Sou um novo método!' não será exibida na execução do programa.
II. O método olaMetodos() depende de uma estrutura de repetição para ser executado.
III. A solução executa um total de 3 comandos de saída de dados, 2 no main e 1 no olaMetodos().
IV. Um método pode ser criado e não ser executado. No caso do presente código, se o método não fosse chamado no main, o programa não apresentaria um erro.

É correto o que se afirma em:

> III e IV, apenas

### Questão 2

Existem diferentes tipos de algoritmos de ordenação. Um algoritmo de ordenação é um algoritmo de manipulação de dados que coloca os elementos em uma dada sequência, efetuando sua ordenação completa ou parcial. Uma das razões para se ordenar uma sequência de dados é a possibilidade de acesso a eles de modo mais eficiente.

Em relação a algoritmos de ordenação, marque a alternativa correta:

> O algoritmo Quick Sort pode ser considerado um algoritmo complexo de ordenação, que utiliza recursão.

### Questão 3
Na programação orientada a objetos, o encapsulamento refere-se ao agrupamento dos atributos com os métodos que operam sobre eles, ou seja, à restrição de acesso direto aos elementos da classe. Isso mantém os dados e o código protegidos contra interferências externas. O encapsulamento é implementado utilizando-se os modificadores de acesso tanto para atributos quanto para métodos.

Com base nos níveis de acesso, avalie as afirmações a seguir.

I. O modificador private tende a restringir o acesso, mantendo as informações das variáveis dentro da classe.
II. O modificador public tende a não restringir o acesso, possibilitando que diferentes componentes do sistema acessem e modifiquem as variáveis.
III. O modificador de acesso protected terá relação com herança de classes. Nele, as subclasses herdam e podem acessar variáveis das superclasses.
IV. Não existe um melhor modificador de acesso, pois as suas aplicabilidades dependerão do contexto em que serão utilizados.

É correto o que se afirma em:

> II, III e IV, apenas.

### Questão 4
A compreensão da lógica proposicional é importante para que, ao construir algoritmos e escrever programas de computador, um programador seja capaz de estruturar soluções simples e objetivas, que sejam ágeis e de fácil compreensão. Para isso, compreender alguns conceitos de lógica é essencial.

Com base no excerto apresentado, avalie as afirmações a seguir.

I. A tautologia pode ser definida como uma proposição composta cuja última coluna da tabela verdade possui somente valor verdadeiro, independentemente dos valores das proposições simples componentes.
II. A Contradição pode ser definida como uma proposição composta cuja última coluna da tabela verdade possui somente valor falso, independente dos valores verdade das proposições simples componentes.
III. É comum que seja possível encontrar expressões mais simples que outras que representam uma condição em um programa de computador, em vista da possibilidade de existência de equivalência lógica.
IV. A equivalência lógica utiliza de expressões irregulares da matemática para simplificar a execução de algoritmos de computador, diminuindo os testes de expressão, mas tornando as soluções mais onerosas para serem executadas.

É correto o que se afirma em:

>I, II e III, apenas.

### Questão 5
Vetores (ou arrays) são usados para armazenar vários valores em uma única variável, ao invés de declarar variáveis separadas para cada valor. É a forma mais simples de organizar listas de dados na memória, pois são armazenados em sequência, um após o outro, o que permite que qualquer valor de qualquer posição seja acessado livremente.

Considerando o conceito de arrays, avalie as asserções a seguir e a relação proposta entre elas.

I. Após definir ou alocar um vetor (array), não é possível aumentar o seu tamanho.

PORQUE

II. Como as suas partes são divididas de forma sequencial na memória, não é possível aumentar a alocação, sendo que a sequência da memória pode ser ocupada por outras estruturas.

A respeito dessas asserções, assinale a opção correta.

> As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.

### Questão 6

Através das estruturas de seleção, é possível permitir ou não a execução de determinados blocos de ações. O comando mais usual em linguagens de programação para tais estruturas é o se ou if. Os operadores racionais são comumente utilizados para realizar testes nas estruturas de seleção, podendo comparar valores e retornar se a comparação é verdadeira ou falsa.

Com base no excerto apresentado, avalie as afirmações a seguir.

I. O operador racional “>”, que representa maior que, pode ser utilizado para comparar duas variáveis, verificando se uma é maior que a outra.
II. O operador racional “>”, que representa maior que, pode ser utilizado para comparar uma variável com um valor fixo, verificando se a variável é maior que o número de comparação.
III. O operador “=”, que representa igual, compara dois valores e retorna verdadeiro caso sejam iguais.
IV. O operador “!=”, que representa diferente, compara dois valores e retorna verdadeiro caso sejam diferentes.

É correto o que se afirma em:

> I, II e IV, apenas.

### Questão 7
Parte relevante das linguagens de programação mais utilizadas na atualidade possibilitam a utilização de mecanismos de tratamento de exceção. Um tratamento de exceção é responsável por tratar ocorrências que alteram o fluxo usual da execução de algoritmos em programas de computador.

No que diz respeito ao tratamento de exceções, analise as asserções a seguir e a relação proposta entre elas.

I. Mesmo contribuindo para os programas de computador se tornarem mais estáveis e evitando erros como estouro de memória, corrupção de dados ou saídas inválidas, é comum o uso de tratamento em exceção ser criticado.

PORQUE

II. O uso de tratamento de exceção pode encorajar o abuso de blocos try/catch mal projetados, podendo não deixar clara ocorrência de exceções nas rotinas que deveriam tratá-las.

A seguir, assinale a alternativa correta.

> As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.

### Questão 8

Um sistema computacional desenvolvido com uma linguagem de programação orientada a objetos é, como o nome do paradigma sugere, composto por objetos que interagem por meio da troca de mensagens (chamadas de métodos). Como sabemos, objetos são construídos a partir de classes e um dos primeiros passos na implementação de um sistema computacional desse tipo é identificar as classes de interesse e a forma como elas se relacionam. Em geral, há dois tipos de relacionamentos entre classes. Eles são chamados de TEM-UM (do inglês HAS-A) e É-UM (do inglês IS-A).

Com base na programação orientada a objetos, avalie as afirmações a seguir.

I. Se uma classe base, denominada pessoa, for herdada pelas classes padeiro e escritor, isso quer dizer que padeiro é uma pessoa e escritor é uma pessoa.
II. Se uma classe pacote possuir variáveis de instância do tipo comida e bebida, terá uma relação de composição (tem-um).
III. Caso uma classe chamada Navio tenha uma classe base chamada "ObjetoDoSistema", essa não é uma relação de “é-um”, pois a classe base do navio teria de ser “Veiculo”.
IV. Em diversos casos a composição pode ser mais bem empregada que a herança, porém, ele possui um limite de 10 objetos.

É correto o que se afirma em:

> I e II, apenas.

### Questão 9
Um algoritmo básico de sequência simples pode ser estruturado em três etapas básicas: entrada, processamento e saída. Cada etapa apresenta suas particularidades e lógicas de estruturação. Sobre a estruturação de um algoritmo de sequência simples, assinale a alternativa correta.

> O processamento de dados pode realizar operações de soma, subtração, multiplicação e divisão, além de repetir diversas dessas operações em sequência.

### Questão 10
Analise o código abaixo e a estruturação da classe Carro:

```java
public class Carro{
  private String cor;
  private double preco;
  private String modelo;

  public Carro(){
  }

  public Carro(String modelo, double preco){
    this.cor = “PRETA”;
    this.modelo = modelo;
    this.preco = preco;
  }

  public Carro(String cor, String modelo, double preco){
    this.cor = cor;
    this.modelo = modelo;
    this.preco = preco;
  }
}
```

Em relação ao código apresentado, marque a alternativa correta:

> A classe carro apresenta 3 construtores, sendo que um deles possui 3 parâmetros.

### Questão 11

Se as estruturas de repetição não existissem na programação, as soluções seriam muito mais limitadas em relação ao que se pode criar hoje. Além de menor eficiência, a escrita dos códigos estaria comprometida em diversos aspectos, pois, sempre que uma instrução tivesse que ser repetida, teria que ser escrita diversas vezes.

Com base nas estruturas de repetição, avalie as afirmações a seguir.

I. No contexto de laços de repetição, uma variável acumuladora recebe um valor inicial e é incrementada nas iterações de um laço por uma expressão.
II. As estruturas de repetição necessitam de variáveis acumuladoras, pois, sem elas, não seria possível determinar um critério de parada.
III. As estruturas de repetição apresentam como padrão a realização de um teste antes da execução de suas instruções, não sendo possível realizar testes ao seu final.
IV. Comandos de entrada de dados podem ser realizados internamente nas estruturas de repetição, não prejudicando sua execução, caso sejam implementados corretamente.

É correto o que se afirma em:

> I e IV, apenas.

### Questão 12

Quando inicializamos um objeto, dizemos que estamos construindo esse objeto da classe envolvida na instrução. Isso é feito por um bloco denominado construtor. Podemos utilizar um construtor padrão da classe, que o compilador nos entrega gratuitamente. Esse construtor zera todas as variáveis da classe.

Considerando a aplicabilidade de construtores, avalie as asserções a seguir e a relação proposta entre elas.

I. Um construtor padrão zera todas as variáveis da classe, independentemente do tipo dessas variáveis. Contudo, o construtor pode determinar características diferentes para os objetos instanciados.

PORQUE

II. Por meio da escrita de um construtor personalizado, podemos construir um objeto realizando a atribuição de valores às variáveis de instância.

A respeito dessas asserções, assinale a opção correta.

> As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.

### Questão 13
Um tipo abstrato de dados (TAD) trata-se de um conjunto de dados estruturados e um conjunto de operações que podem ser executadas sobre esses dados. Alguns tipos são muito utilizados em computação: pilha e fila.

Considerando os tipos abstratos de dados citados, avalie as asserções a seguir e a relação proposta entre elas.

I. Nas estruturas de dados pilha e fila, a inserção e a retirada de elementos seguem regras bem definidas. A pilha segue LIFO (last in, first out): o último elemento a ser inserido é o primeiro disponível para remoção.

PORQUE

II. A pilha não segue o padrão da fila, FIFO (first in, first out), onde o primeiro elemento que é inserido deve ser o primeiro que é removido.

A respeito dessas asserções, assinale a opção correta.

> As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa da I

### Questão 14
A sobrecarga de métodos é um tipo de polimorfismo, pois, do ponto de vista do código-cliente, um mesmo método pode ser chamado de formas diferentes, embora saibamos que, na verdade, trata-se de vários métodos com o mesmo nome.

Em relação a esse tipo de polimorfismo, marque a alternativa correta.

> Esse tipo de polimorfismo é chamado de polimorfismo estático, por ser realizado pelo compilador.

### Questão 15
Laços de repetição são comumente utilizados em algoritmos que estruturam diferentes tipos de soluções computacionais. Esses algoritmos apresentem variações, em geral, focados em controlar critérios e quantidades de repetições. A imagem a seguir representa uma aplicação hipotética das estruturas while e do-while. Na imagem, o personagem Papa-Léguas está correndo e parando na ponta do penhasco, com uma representação visual da instrução while (not edge) run();. A frente, passando do penhasco e suspenso no ar, o personagem Coiote apresenta a instrução do run() while (not edge);.

![image](https://user-images.githubusercontent.com/12941120/193720436-8c1758ac-8b0e-4c62-bae9-d0a568f74aaa.png)

Disponível em: https://www.reddit.com/. Acesso em: 3 de jul.de 2022.

Sobre a utilização de estruturas de repetição, assinale a alternativa correta.

> O while de Papa-Léguas verifica a condição e depois executa a instrução de corrida, já o Coiote executa antes a instrução de corrida e depois verifica a condição, através do do-while, por isso Coiote caiu e o Papa-Léguas não.
