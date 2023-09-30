# Exercício de Sala 🏫  

- Conteúdo teórico: 
[ES6 Instantiation](https://github.com/reprograma/on21-imersao-js-S6-Prototype-2#es6-instantiation)

## Exercício 1

Vamos criar um aplicativo de corridas estilo Uber apenas para mulheres.

##### a) Crie a classe Driver e seus atributos

Pra começar, defina uma função construtora ES6 Instantiation (Classe) para um objeto `Driver`.

Essa classe deve possuir os seguintes atributos:
- [ ] `name` - Nome: recebido como parâmetro no constructor
- [ ] `age` - Idade: recebido como parâmetro no constructor. Só é possível ser motorista caso a idade seja maior ou igual 18. Caso contrário, o objeto motorista não pode ser criado.
- [ ] `numberOfRides` - Quantidade de corridas realizadas: inicializado com 0.
- [ ] `amountEarned` - Valor recebidos em corridas: inicializado com 0.

##### b) Crie a classe Passenger e seus atributos

Crie outra classe chamada `Passenger`.

Essa classe deve possuir os seguintes atributos:
- [ ] `name` - Nome: recebido como parâmetro no constructor
- [ ] `age` - Idade: recebido como parâmetro no constructor
- [ ] `password` - Senha: recebido como parâmetro no constructor
- [ ] `amountSpent` - Valor gasto em corridas: inicializado com 0.

##### c) Crie o método abaixo

A classe `Driver` deve possuir o seguinte método:
- [ ] `runDrive(amount)`, que serve para a a motorista aceitar uma corrida.

Esse método deve obedecer as seguintes regras:
- O parâmetro `amount` é o valor da corrida.
- O motorista aumenta em 1 a sua quantidade de corridas realizadas
- O `amount` do motorista **aumenta** a cada corrida, de acordo com o parâmetro `amount` da função (esse valor será sempre **positivo**).

##### d) Crie o método abaixo

A classe `Passenger` deve possuir o seguinte método:
- [ ] `requestDrive(driver, amount, password)`, que serve para a passageira solicitar uma corrida com uma motorista específica.

Esse método deve obedecer as seguintes regras:

- O parâmetro `amount` é o valor da corrida.
- A corrida só pode ser solicitada se a senha (`password`) estiver correta.
- O parâmetro `driver` precisa, obrigatoriamente, ser do tipo `Driver`, caso contrário, a requisição não pode ser realizada.
- O `amount` do passageiro **diminui** a cada corrida, de acordo com o parâmetro `amount` da função (esse valor será sempre **negativo**).
- O método `runDrive(amount)` da motorista deve ser chamado, para aumentar o `amountEarned` e o `numberOfRides` da motorista escolhida.

Teste tudo o que foi criado.

---

Terminou o exercício? Dá uma olhada nessa checklist e confere se tá tudo certinho, combinado?!

- [ ] Fiz o fork do repositório.
- [ ] Clonei o fork na minha máquina (`git clone url-do-meu-fork`).
- [ ] Resolvi o exercício dentro da pasta resolução.
- [ ] Adicionei as mudanças. (`git add .` para adicionar todos os arquivos, ou `git add nome_do_arquivo` para adicionar um arquivo específico)
- [ ] Commitei a cada mudança significativa ou na finalização do exercício (`git commit -m "Mensagem do commit"`)
- [ ] Pushei os commits na minha branch (`git push origin nome-da-branch`)
