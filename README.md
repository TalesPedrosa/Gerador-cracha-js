# Gerador-cracha-js
Repositório destinado ao Projeto Parte II Lógica + Versionamento

Esse projeto é um gerador de crachá, ou seja, ao final do projeto, tem que ser exibido no console um crachá com:
- sobrenome e nome, respectivamente
- idade estimada
- quantidade de letras
- se o aluno está ativo ou não
Separamos em duas duplas, a dupla A ficou responsável pelo desenvolvimento da primeira parte do código "index.html" , criar a branch "feature-coleta-dados" comitá-lo, fazer o pull request dele e revisar o código da dupla B.
O código "index.html" da dupla A:
- utiliza "prompt()" para solicitar, em variáveis separadas, três dados ao utilizador: o nome, o sobrenome e o ano de nascimento
- utiliza "confirm()" para perguntar ao utilizador: "É aluno ativo da instituição?" e guardar o resultado numa variável
A dupla B ficou responsável pela adição da segunda parte do código feito pela dupla A , criando uma branch de nome "feature-geracao-cracha" que adiciona:
- Adicionamos a função number() para converter o ano de nascimento para um tipo numérico
- Subtraimos a idade pelo ano atual e colocamos essa informação na variável idade
- Criamos outra variável usando o método ToUpperCase() para conseguir guardar o sobrenome do usuário em letras maiúsculas
- Criamos outra variável usando .lenght para determinar a quantidade de caracteres do primeiro nome
- Adicionamos console.log para exibir o crachá final
E aqui no READ.ME, descrevemos tudo que é preciso para entender o nosso projeto, sem que seja necessário abrir o código ou visualizar o históricos de ações e alterações realizadas no repositório
