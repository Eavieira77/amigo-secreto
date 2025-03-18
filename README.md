# amigo-secreto
Jogo do Amigo Secreto

Descrição do Projeto
O Amigo Secreto Online é um aplicativo web desenvolvido em JavaScript que permite aos usuários organizar e realizar sorteios de amigo secreto de forma simples e eficiente. O usuário insere os nomes dos participantes, e o sistema realiza o sorteio de forma aleatória, exibindo o resultado diretamente na tela.

Este projeto foi desenvolvido para facilitar a organização de eventos sociais, como festas de fim de ano, onde a tradição do amigo secreto é comum. O aplicativo garante que o sorteio seja justo e que cada participante receba um amigo secreto único.

Funcionalidades
Adicionar nomes: Os usuários escreverão o nome de um amigo em um campo de texto e o adicionarão a uma lista visível ao clicar em "Adicionar".

Validar entrada: Se o campo de texto estiver vazio, o programa exibirá um alerta solicitando um nome válido.

Visualizar a lista: Os nomes inseridos aparecerão em uma lista abaixo do campo de entrada.

Sorteio aleatório: Ao clicar no botão "Sortear Amigo", um nome da lista será selecionado aleatoriamente e exibido na página.

Desafios de Desenvolvimento
Um dos principais desafios enfrentados durante o desenvolvimento deste projeto foi garantir que o nome sorteado fosse exibido corretamente na tela. 

Solução Implementada
Para resolver o problema do sorteio e exibição dos nomes, foi implementada a seguinte lógica:

Armazenamento dos Nomes: Os nomes dos participantes são armazenados em um array.

Embaralhamento do Array: O array de nomes é embaralhado utilizando o algoritmo de Fisher-Yates, garantindo uma distribuição aleatória.

Atribuição de Amigos Secretos: Cada nome é atribuído ao próximo nome no array embaralhado, criando um ciclo fechado onde o último nome é atribuído ao primeiro.

Exibição do Resultado: O resultado é exibido na tela, mostrando para cada participante o nome do amigo secreto sorteado.

Tecnologias Utilizadas
HTML5: Estruturação da interface do usuário.

CSS3: Estilização e design responsivo.

JavaScript: Lógica de programação e interatividade.

Como Executar o Projeto

Clone o Repositório:
git clone https://github.com/Eavieira77/amigo-secreto.git

Acesse a versão online:
https://amigo-secreto-rust-seven.vercel.app/


Jogo do Amigo Secreto - Facilite seus sorteios e divirta-se com seus amigos! 🎉



