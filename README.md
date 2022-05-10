# NLW 2022 - Feedback Widget (Feedget)

Projeto implementando da edição de 2022 da Next Level Week da Rocketseat.

Um widget de feedback com função de tirar um screenshot da tela do usuário e enviar para o backend em conjunto com uma mensagem.

## TecStack 

### Frontend com React, Typescript e TailwindCSS.
### Backend com NodeJS, Typescript, Prisma(PostgresSQL), Express. Refatorado nos moldes SOLID.
### Mobile com React Native, Expo.

## Funcionamento

O widget inicia como um pequeno ícone no canto da tela. Ao ser clicado, ele expande, oferecendo ao usuário as três opções de feedback: Erro, Ideia ou Outro.
É oferecido ao usuário um campo de texto para descrever o feedback, juntamente com a funcionalidade de tirar e anexar um screenshot da tela. Ao clicar em 'Enviar', os dados contidos nos campos de texto e a imagem do screenshot são enviadas para o backend, que grava estes dados em um banco (Postgres) e envia um email para o administrador do site/app com o feedback do usuário.


 
