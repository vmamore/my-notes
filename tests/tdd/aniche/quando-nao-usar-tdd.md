# Quando não usar TDD?
<!-- TOC -->
- A ideia não é usar TDD porque a prática está em alta no mercado mas sim pelo benefício que ele agrega ao processo

- Deixe sua experiência te guiar também na escolha de usar ou não TDD.
- Lembre-se que no fim das contas, o que precisamos é de feedback sobre o que estamos fazendo

- Cuidado na hora de julgar se um código merece ou não ser testado.
- Na dúvida, teste.
- Lembre-se que todo código é considerado culpado até que se prove inocente.

# Refatoração em sistemas legados:
<!-- TOC -->
    - 1 - Comece testando da maneira que conseguir
        - 1.1 - Se conseguir teste unidade, excelente.
        - 1.2 - Se não, subir de nível até conseguir escrever um teste.
            - 1.2.1 - Em aplicações legadas web, o dev pode começar com testes de sistema, 
                      para garantir o comportamento do sistema.
    - 2 - Na refatoração, o dev deve criar classes menores e mais coesas e já escrever testes de unidade para elas.
    - 3 - Durante a reescrita, pode ser que o dev sinta a necessidade de escrever testes "feios".
        - 3.1 - Em sistemas legados, não tenha medo de escrever código de teste que será jogado fora depois.
                Se fizermos uma analogia, imagine esses códigos sejam como os andaimes utilizados durante a obra.
                Eles não fazem parte do produto final, estão lá apenas para ajudar no desenvolvimento.
        - 3.2 - O padrão "Adapter" pode ajudar o dev a conectar código bem escrito com o legado que deve ser mantido.


# Sugestões de livros:
<!-- TOC -->
    - 1 - Test-Driven-Development: By example - Kent Beck
    - 2 - Growing Object Oriented Software, Guided By Tests - Steve Freeman and Nat Pryce
    - 3 - Agile Software Development, Principles, Patterns and Practices - Robert Martin