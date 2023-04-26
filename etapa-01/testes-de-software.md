# Etapa 01
## O que são testes?

Os testes são atividades que fazem parte do ciclo do desenvolvimento de um software. Eles devem ser realizados por desenvolvedores e analistas de testes com o objetivo de assegurar a qualidade do produto. 

## Os sete princípios de testes

1. **Teste demonstra a presença de defeitos**
>> 1.1. O teste pode demonstrar a presença de defeitos, mas nunca sua ausência;  

>> 1.2. O teste apenas reduz a probabilidade que os defeitos permaneçam em um software, porém isto não prova que ele esteja perfeito;
2. **Teste exaustivo não é possível**
>> 2.1. Testar tudo não é viável, exceto para casos triviais;  

>> 2.2. Ao invés de realizar testes exaustivos, os **riscos e prioridades** devem ser levados em consideração para dar foco aos esforços do teste;  
3. **Teste antecipado**
>> 3.1. Os testes devem ser realizados o mais breve possível no ciclo de desenvolvimento, pois quanto mais cedo encontrarmos um defeito, mais barata será sua identificação e correção;  
4. **Agrupamento de defeitos**
>> 4.1.Um número pequeno de módulos contém a maioria dos defeitos descobertos durante o teste, antes de sua entrega ou exibe a maioria das falhas operacionais;  

>> 4.2. Os bugs estão distribuídos de forma heterogênea. Alguns módulos têm mais defeitos do que outros;
5. **Paradoxo do pesticida**
>> 5.1. Pode ocorrer de um mesmo conjunto de testes repetidos várias vezes não encontrarem novos defeitos após determinado momento;

>> 5.2. Para superar este "paradoxo do pesticida" os casos de testes necessitam ser frequentemente revisados e atualizados;  

>> 5.3.Um conjunto de testes novos e diferentes precisa ser escrito para exercitar diferentes partes do software ou sistema, com objetivo de aumentar a possibilidade de encontrar mais erros;
6. **Teste depende do contexto**
>> 6.1. Os testes devem ser realizados de formas diferentes, conforme o contexto da tarefa;  
>>>> 6.1.1. Por exemplo, um software de piloto automático de um carro deve ser testado com amplitude e profundidade diferente de um software de e-commerce;  
7. **Ilusão da ausência de erros**
>> 7.1. Encontrar e consertar defeitos não ajuda se o sistema construído não atenda às expectativas e necessidades dos usuários;  

## Erro, Defeito e Falha
Os erros são cometidos por pessoas. Defeitos são gerados à partir destes erros. A falha é a execução do defeito. 

Os softwares são feitos por pessoas, estas que podem cometer erros de síntaxe ou semântica no código, gerando defeitos.  

Se um defeito no código for executado, o sistema falhará ao tentar executar o que deveria. Falhas geram insatisfação com a qualidade.

> **Exemplo**  
>Um desenvolvedor errou a forma de como iria ser realizado um cálculo, esquecendo de informar a quantidade de casas decimais. O defeito está no código, sem a adição das casas decimais. A falha é exibida no sistema, quando o cálculo é executado e o resultado esperado não é exibido.

### Referências

**Iterasys.com.br** - Início Rápido em Testes de Software