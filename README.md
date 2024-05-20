# E o Banco, hein? 

💡 A atividade abaixo foi proposta pelo Professor Gabriel Augusto durante o curso do Instituto PROA visando a aprendizagem de Lógica de Programação com JavaScript.


## Objetivo da atividade 

No mundo do desenvolvimento o pensamento crítico é a parte mais importante. Com um pensamento apurado, você consegue fazer melhores perguntas, ser mais assertivo nas ações e no desenvolvimento. 

Exatamente por isso, mantenha muita atenção no que é solicitado abaixo. Pense com cuidado, planeje e execute. Dessa vez, vocês estão alterando um código pronto e aplicando sua visão. 
Mantenha na cabeça que qualquer alteração não vai quebrar o mundo... Então experimente tudo o que quiser experimentar. Brinque bastante e altere tudo o que quiser alterar. 

Com o projeto de ajustes e melhorias de um caixa eletrônico, por exemplo, encontramos algumas questões que são muito importantes, mas não foram aplicadas. 

Vamos aplicá-las uma a uma. 

## Enunciado da atividade 

- Ao acessar o sistema, pergunte o nome do usuário e diga "Olá {Nome} é um prazer ter você por aqui!".

- Na função "inicio", utilize escolha/caso (switch/case) para validar a opção escolhida pelo usuário. 

- Sempre que o usuário for sacar dinheiro, o valor restante não pode ser negativo, ou seja, caso o usuário tente sacar mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada". 

- Sempre que o usuário for sacar dinheiro, o valor a ser sacado não pode ser igual ou menor que zero. Exiba uma mensagem de "Operação não autorizada". 

- Adicionar a opção para ver o extrato (Coloque algumas compras ou depósitos fictícios). 

- Adicionar a opção para fazer uma transferência. A transferência consiste em você informar o número de uma conta (pode ser qualquer número, mas obrigatoriamente um número, ou seja, nenhum outro caractere deve ser aceito), perguntar o valor da transferência e remover o valor da conta da mesma forma como na ação do saldo. Caso o usuário tente transferir mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada". 

- Sempre que o usuário for transferir dinheiro,  o valor a ser transferido não pode ser igual ou menor que zero, ou seja, caso o usuário tente transferir mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada". 

- No menu principal, a ordem das opções deve ser: Saldo, Extrato, Saque, Depósito, Transferência e Sair. 

- Atualize a função "erro" com as novas opções do menu.

- Caso o usuário informe um valor para depósito igual ou menor que zero, não deixe a operação ocorrer. Exiba uma mensagem de "Operação não autorizada". 

- Sempre que o usuário for acessar o saldo, sacar, retirar o extrato ou transferir dinheiro é necessário que ele informe uma senha. Essa senha deve ser validada com uma condicional. A senha é 3589.

- Caso a senha informada não seja a correta, é necessário chamar a função atual novamente. 

- Quando o usuário escolher sair do sistema, exiba uma mensagem agradecendo por utilizar os serviços do banco: "{Nome}, foi um prazer ter você por aqui!".
