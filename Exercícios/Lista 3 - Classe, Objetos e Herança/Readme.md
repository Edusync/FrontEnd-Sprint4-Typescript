# Exercícios: Classes, Objetos e Herança

**Os exercícios abaixo, deverão ser feitos utilizando TypeScript**

**1 -** Crie uma classe usuário que deve receber dois parâmetros no método construtor: e-mail e senha, e anotá-los em propriedades da classe. 

Crie uma classe com nome "Admin", essa classe deve estender uma segunda classe chamada "Usuario". A classe "Admin" por sua vez não recebe parâmetros próprios apenas e-mail e senha 
da classe pai (super). Deve ser criada uma propriedade interna this.admin = true em
seu construtor. 

Agora com suas classes formatadas, adicione um método na classe Usuario chamado isAdmin 
que retorna se o usuário é administrador ou não baseado na propriedade admin ser true ou não.

**2 -** Crie uma classe “Carro” com atributos cor, marca, placa. Defina seus métodos
modificadores e assessores. E crie métodos que permitam ao usuário inserir 3 carros,
listar as placas dos carros e modificar suas cores.

**3 -** Crie uma classe “Animais” com atributos porte, idade, peso. Defina seus métodos
modificadores e assessores. Crie uma classe filho “Felinos”, com atributo tipoFelino e
com os métodos AfiarGarras() e Dormir(). Crie métodos que permitam ao usuário
inserir 2 felinos, e informar se eles estão dormindo ou afiando garras.

**4 -** Crie uma classe “Pessoa” com atributos nome, endereço, cpf. Crie uma classe
filha “Estudante” com atributos turma e turno. Crie métodos que permita ao usuário
inserir 10 estudantes e separe alunos por turno. Permita ao usuário alterar o turno
dos estudantes.

**5 -** Crie uma classe para representar uma pessoa, com os atributos privados de nome,
data de nascimento e altura. Crie os métodos públicos necessários para sets e gets
e também um método para imprimir todos dados de uma pessoa. Crie um método
para calcular a idade da pessoa.

**6 -** A fim de representar empregados em uma firma, crie uma classe chamada
Empregado que inclui as três informações a seguir como atributos:
• um primeiro nome,
• um sobrenome, e
• um salário mensal.
Sua classe deve ter um construtor que inicializa os três atributos. Forneça um método
set e get para cada atributo. Crie duas instâncias da classe e exiba o salário anual de
cada instância. Então dê a cada empregado um aumento de 10% e exiba novamente
o salário anual de cada empregado.

**7 -** Crie uma classe para representar datas.
• Represente uma data usando três atributos: o dia, o mês, e o ano.
• Sua classe deve ter um construtor que inicializa os três atributos e verifica a
validade dos valores fornecidos.
• Forneça um construtor sem parâmetros que inicializa a data com a data atual
fornecida pelo sistema operacional.
• Forneça um método set um get para cada atributo.
• Forneça uma operação para avançar uma data para o dia seguinte.
**Referencia: [https://www.w3schools.com/js/js_dates.asp](https://www.w3schools.com/js/js_dates.asp)**

**8 -** Crie uma classe para representar um jogador de futebol, com os atributos nome,
posição, data de nascimento, nacionalidade, altura e peso. Crie os métodos públicos
necessários para sets e gets e também um método para imprimir todos os dados do
jogador. Crie um método para calcular a idade do jogador e outro método para mostrar
quanto tempo falta para o jogador se aposentar. Para isso, considere que os
jogadores da posição de defesa se aposentam em média aos 40 anos, os jogadores
de meio-campo aos 38 e os atacantes aos 35.

**9 -** Crie uma classe chamada Ingresso, que possui um valor em reais e um método
imprimirValor(). Crie uma classe IngressoVIP, que herda de Ingresso e possui um
valor adicional. Crie um método que retorne o valor do ingresso VIP (com o adicional
incluído). Crie um programa para criar as instâncias de Ingresso e IngressoVIP,
mostrando a diferença de preços.