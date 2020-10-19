#   Design e Arquitetura de Software - Orientação a Objeto


-   [Requerimento de Software](#requerimentos-de-software)

-   [Design de Objetos por Categoria](#design-de-objetos-por-categorias)

-   [CRC](#class-responsability-collaboratorcrc)

-   [Principios de Design Orientado a Objeto](#os-4-principios-do-design-orientado-a-objeto)

-   [Abstraçao em Java e UML](#abstração-em-java-e-uml)

Arquitetura de Software é uma forma de abstração do projeto de software e
não consiste em linhas de código, mas sim em uma visão dos componentes, objetos
e as tecnologias usadas no desenvolvimento da aplicação.


### Requerimentos de Software

    Parte dos problemas surgem por não terem os requisitos bem definidos
    
    Os requerimentos podem ser divididos em funcionais e não funcionais,
    para isso é preciso balancear o que vai satisfazer a qualidade esperada
    pelo cliente.

    - Pontos importantes : 
        - Elicitar os requerimentos
        - criar componentes
  
    - Algo que ajuda o comprador a definir o projeto é contar uma história:
        - Ex: Como um _______ , eu quero __________ , então eu posso _________

### Design de Objetos por Categorias

    - Objetos possuem comumente 3 categorias:
        - boundary objects:
          - São objetos que fica na "borda" da aplicação
            podendo ser essa borda, comunicação com outros serviços.
            internet ou mesmo a interface de usuário

        - control objects:
            -  Objectos que visam controlar o funcionamento de outros
            objetos. Muitsa vezes servindo como um mediador para acoplar
            diversos objetos
        
        - entity objects:
            - Entity objects são os mais comuns entre os objetos, normalmente
            usados para representar coisas do mundo real.


### Class Responsability Collaborator(CRC)

    Para elaborar o design de um software podemos pensar no CRC
    como um método de esboçar a construção do software.

    - CRC tem três pontos:
      - Classes
      - Colaboradores
      - Responsabilidades


### Os 4 Principios do Design Orientado a Objeto

    - Abstração :
        - Comportamentos e atributos de um conceito, sem visar características
        minúsculas, o que pode ser irrelevante
    
    - Encapsulamento :
        - O acesso a metodos e atributos funcionam como em uma "caixa preta"
        o usuario não tem conhecimento de como foi implementado e apenas tem
        acesso ao que é permitido a ele.
    
    - Decomposição:
        - Quebrar um problema grande em um problema pequeno
        - Pontos importantes ao decompor : 
            - Objetos fixos e dinamicos
            - Tempo de Vida
            - Compartilhamento de Objetos
        - Existem 3 tipos de relacionamento encontrados numa decomposição :
            - Associação : um objeto não depende do outro, seu relacionamento é livre
            - Agregação : uma relação "tem - um", onde um objeto possui o outro
            mas não depende disso para poder existir
            - Composição : um tipo específico de "tem- um" onde um objeto vai depender
            do objeto que ele possui para existir

    - Generalização
        - Objetos que podem ser aplicados diversas vezes
        por ter a necessidade de seu uso repetido, comum e com 
        caracteríticas compartilhadas.
        - Para aplicação desse conceito, pode-se pensar
        no conceito de herança, existende em linguagens que implementam POO.
        - Polimorfismo : é quando duas classes tem o mesmo comportamento, mas
        possuem implementação diferente para a mesma
        - O uso de Interfaces permite o uso de multipla herança 

### Abstração em Java e UML

-   Diagrama de Classes são uma forma de representar os Objetos da Aplicação
-   É uma forma que tem seu lugar consolidado na prototipação das classes de
    software

- Características UML :
    - Propriedades : equivalente aos atributos das classes
    - Operações : equivalente aos métodos





    
