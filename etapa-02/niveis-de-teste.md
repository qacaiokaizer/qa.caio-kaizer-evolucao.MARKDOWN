# Etapa 02
## Níveis de Testes

### O que são níveis de testes?

Os níveis de testes definem as metodologias e práticas que serão aplicadas para testar uma aplicação em um determinado período do ciclo de vida de um software.

## Testes Unitários

Costumeiramente realizado pelos desenvolvedores, estes testes têm o objetivo de validar pequenos trechos de código de forma isolada, como classes, métodos, funções, etc, antes da integração com outros sistemas.

Um teste de unidade é um programa que chama métodos de uma classe e verifica se eles retornam os resultados esperados.

## Testes de Integração

Diferentemente dos testes unitários, o teste de integração tem é um serviço mais completo, porque envolve mais classes, dependências e sistemas reais, como banco de dados e serviços remotos. 

Como são testes maiores, eles demoram mais tempo para executar e, consequentemente, são chamados com menor frequência.

## Testes de Sistema

Estes testes estão posicionados no topo da pirâmide de testes. Tem como objetivo simular o uso de um sistema por um usuário real ou stakeholders do produto, realizando testes funcionais e não funcionais. Popularmente, são conhecidos como testes de ponta-a-ponta (end-to-end, e2e) e testes de interfaces. 

## Testes de Aceitação

São os testes realizados, de forma manual, pelos clientes. O objetivo é validar se os resultados esperados estão de acordo com a implementação realizada. Se o software entregue atende aos requisitos que foram pedidos pelo cliente, o sistema pode entrar em produção.

Existem duas fases nos testes de aceitação, são elas:

### Testes Alfa e Testes Beta

Os testes **Alfa** são realizados por uma pequena parcela dos usuários, em um ambiente controlado. Se o sistema for aprovado, pode-se realizar um teste com um número maior de usuários em um ambiente menos rígido. Esses testes são chamados de **Beta**.


### Referências

**Iterasys.com.br** - Início Rápido em Testes de Software  
**Marco Tulio Valente** - Engenharia de Software Moderna