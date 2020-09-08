#   Design e Arquitetura de Software - Orientação a Objeto


[Requerimento de Software](#requerimentos-de-software)

[Design de Objetos por Categoria](#design-de-objetos-por-categorias)

[CRC](#class-responsability-collaboratorcrc)

    Arquitetura de Software é uma forma de abstração do projeto de software
    não consiste em linhas de código, mas uma visão dos componentes, objetos
    e a forma como o software deve ser desenvolvido.


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


