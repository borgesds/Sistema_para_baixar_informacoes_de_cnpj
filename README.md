# SISTEMA DE TABULAÇÃO DE CNPJ's

---------------------------------------------------

## O que é?
Esse sistema é um modelo para buscar informações sobre os CNPJ's. A API é grátis e o link para acessar é: https://rapidapi.com/cnpja/api/consulta-cnpj-gratis.
Aqui automatizamos a resposta da API para entrada de de um arquivo CSV com os CNPJ's e retirar informações importantes:

| cnpj | state | city | district | street | number | zip | ddd | phone |

## Os CNPJ'?

1 - Os CNPJ's contido nesses arquivos voram retirados de um gerador de CNPJ da internet, o link é:https://www.4devs.com.br/gerador_de_cnpj.

2 - Todos os dados são usado para desenvolver as melhorias dos códigos.

3 - O sistema de buscar as informações é grátis, mas ele aceita 2 ou 3 CNPJ's por minuto. 

4 - O código foi preparado para que não tenha interrupções e que possa rodar quantos CNPJ's forem necessarios.

5 - O acesso pode ser expirado a qualquer momento. Então faça uma nova conta e mude o 'x-rapidapi-key' dentro do código.

