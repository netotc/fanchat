💬 FanChat: Chat em Tempo Real com Node.js e Socket.IO
O FanChat é uma aplicação de chat em tempo real desenvolvida com Node.js e Socket.IO, projetada para proporcionar uma experiência de comunicação fluida e eficiente. Este projeto demonstra funcionalidades essenciais de um sistema de chat, incluindo o registro persistente de mensagens e um robusto sistema de validação de usuários.
✨ Recursos Principais
Registro de Mensagens (chat.log)
Todas as mensagens enviadas pelos usuários são automaticamente salvas em um arquivo de texto (chat.log). Cada registro inclui um timestamp ([YYYY-MM-DD HH:MM:SS]) e o nome do usuário, garantindo um histórico completo e organizado das conversas. As novas mensagens são anexadas ao final do arquivo, mantendo a ordem cronológica.

Validação e Gerenciamento de Usuários
O FanChat implementa um sistema inteligente de validação de nomes de usuário para garantir um ambiente organizado:

Prevenção de Nomes Vazios: Impede que usuários entrem no chat com nomes em branco.
Exclusividade de Nomes: Bloqueia o uso de nomes já ativos por outros usuários conectados, assegurando que cada participante seja único.
Feedback ao Usuário: Retorna mensagens claras informando se o nome de usuário foi aceito ou rejeitado.
Gerenciamento de Sessões: Remove automaticamente o nome de usuário da lista de ativos quando um usuário se desconecta, liberando-o para uso futuro.

🚀 Como Executar o Projeto
Siga os passos abaixo para colocar o FanChat em funcionamento na sua máquina:

1. Clonar o Repositório
Abra seu terminal e execute o comando:
git clone https://github.com/seu-usuario/fanchat.git
cd fanchat
Lembre-se de substituir seu-usuario pelo nome de usuário correto do repositório, caso não seja o seu.

2. Instalar as Dependências
Com o terminal na pasta do projeto (fanchat), instale as dependências necessárias:
npm install express socket.io

3. Iniciar o Servidor
Após a instalação das dependências, inicie o servidor Node.js:
node server.js

Com certeza! Vamos elaborar um README mais completo e profissional, mantendo a concisão.

💬 FanChat: Chat em Tempo Real com Node.js e Socket.IO
O FanChat é uma aplicação de chat em tempo real desenvolvida com Node.js e Socket.IO, projetada para proporcionar uma experiência de comunicação fluida e eficiente. Este projeto demonstra funcionalidades essenciais de um sistema de chat, incluindo o registro persistente de mensagens e um robusto sistema de validação de usuários.

✨ Recursos Principais
Registro de Mensagens (chat.log)
Todas as mensagens enviadas pelos usuários são automaticamente salvas em um arquivo de texto (chat.log). Cada registro inclui um timestamp ([YYYY-MM-DD HH:MM:SS]) e o nome do usuário, garantindo um histórico completo e organizado das conversas. As novas mensagens são anexadas ao final do arquivo, mantendo a ordem cronológica.

Validação e Gerenciamento de Usuários
O FanChat implementa um sistema inteligente de validação de nomes de usuário para garantir um ambiente organizado:

Prevenção de Nomes Vazios: Impede que usuários entrem no chat com nomes em branco.
Exclusividade de Nomes: Bloqueia o uso de nomes já ativos por outros usuários conectados, assegurando que cada participante seja único.
Feedback ao Usuário: Retorna mensagens claras informando se o nome de usuário foi aceito ou rejeitado.
Gerenciamento de Sessões: Remove automaticamente o nome de usuário da lista de ativos quando um usuário se desconecta, liberando-o para uso futuro.
🚀 Como Executar o Projeto
Siga os passos abaixo para colocar o FanChat em funcionamento na sua máquina:

1. Clonar o Repositório
Abra seu terminal e execute o comando:

Bash

git clone https://github.com/seu-usuario/fanchat.git
cd fanchat
Lembre-se de substituir seu-usuario pelo nome de usuário correto do repositório, caso não seja o seu.

2. Instalar as Dependências
Com o terminal na pasta do projeto (fanchat), instale as dependências necessárias:

Bash

npm install express socket.io
3. Iniciar o Servidor
Após a instalação das dependências, inicie o servidor Node.js:

Bash

node server.js
Você deverá ver uma mensagem no terminal indicando que o servidor está em execução.

4. Acessar o Chat
Abra seu navegador web e digite o seguinte endereço:
http://localhost:3000

Você será solicitado a digitar um nome de usuário. Insira um nome válido para entrar no chat e começar a interagir em tempo real!
