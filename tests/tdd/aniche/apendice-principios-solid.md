# Princípios SOLID
<!-- TOC -->

## Rigidez:
- É a tendência do software em se tornar difícil de mudar, mesmo de maneiras simples. 
  Toda mudança causa uma cascata de mudanças subsequentes em
  módulos dependentes. Quanto mais módulos precisam ser modicados, maior é a
  rigidez do projeto de classes

## Fragilidade:
- É a tendência do software em quebrare em muitos lugares diferentes toda vez que uma única mudança acontecer.

## Mobilidade:
- Imbolidade é a impossibilidade de se reusar software de outros projetos ou de partes do mesmo projeto.
  Neste cenário, o módulo que se deseja reutilizar frequentemente tem uma bagagem muito grade de dependências 
  e não possuic código claro.

## Viscosidade:
- Quando é fácil fazer a "coisa errada" e é difícil fazer a "coisa certa", ou seja, é difícil preservar 
  e aprimorar o projeto de classes.

## Complexidade Desnecessária:
- Quando num projeto de classes contém muitos elementos inúteis ou não utilizados (dead code).
  Geralmente ocorre quando há um projeto inicial e não segue uma abordagem de desenvolvimento iterativa e incremental,
  de modo que os projetistas tentam prever uma série de futuros requisitos para o sistema e concebem um projeto de
  classes demasiadamente flexível ou desnecessariamente sofisticado.

## Repetição Desnecessária:
- Quando há repetição de trechos de código, é sinal de que uma abstração apropiada não foi capturada durante o processo
  de projeto de classes.

## Opacidade:
- É a tendência de um módulo de ser difícil de ser entendido. A tendência é que códigos se torne opacos, assim, é necessário
  esforço constante em manter esse código claro e expressivo.
- ### Soluções:
    - Devs devem ler e refatorar o código de forma que qualquer outro leitor possa entender.
    - Revisões de código feita por outros desenvolvedores.

## SOLID:
### Princípio da Resposabilidade Única (SRP)
    - Uma classe deve ter apenas uma única razão para mudar.
### Princípio do Aberto-Fechado (OCP)
    - Entidades do software (classes, módulos, funções e etc) devem ser abertas para extensão, mas fechadas para alteração.
### Princípio de Substituição de Liskov (LSP)
    - Se um tipo S é subclasse de um tipo T, então objetos do tipo T podem ser substituídos por objetos do tipo S, 
      sem alterar nenhuma das propriedades desejadas daquele programa.
### Princípio da Inversão de Dependêcia (DIP)
    - Módulos de alto nível não devem depender de módulso de baixo nível. Ambos devem depender de abstrações.
    - Abstrações não devem dependender de detalhes. Detalhes devem depender de abstrações.
### Princípio da Segregação de Interfaces (ISP)
    - Classes cliente não devem ser forçadas a depender de métodos que elas não utilizam.