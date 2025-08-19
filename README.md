Esse é um jogo de adivinhação de bandeiras.

O Jogo de Adivinhação de Bandeiras é um jogo interativo onde o jogador precisa adivinhar o nome dos países a partir da imagem de suas bandeiras. A cada rodada, o jogador é desafiado a escrever o nome do país correspondente à bandeira exibida. O jogo é composto por 10 rodadas, e o objetivo é acertar o maior número possível de respostas no menor tempo, podendo ser jogado somente localmente

**Funcionalidades:**

10 Rodadas: O jogador tem 10 rodadas para adivinhar o nome de países a partir de suas bandeiras.

Rank de Tempo e Acertos: Ao final das 10 rodadas, o jogo exibe um ranking com o tempo total gasto e o número de acertos, estimulando o jogador a melhorar sua performance a cada tentativa.

Interface Simples e Intuitiva: O design da interface é feito com HTML e CSS, oferecendo uma experiência limpa e fácil de jogar.

Desafios Progressivos: Cada rodada desafia o jogador com uma nova bandeira de um país diferente, as vezes pode repitir.

O jogo identifica automaticamente quem entra no rank (de 5 pessoas, podendo ser alterado no codigo do servidor (index.jx na pasta API)) e em qual posição a pessoa fica.

**Tecnologias Utilizadas:**

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) Responsável pela estruturação da página e exibição das informações.

![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3) Utilizado para o design e estilo da interface, proporcionando uma experiência visual agradável.

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
 Usado para a lógica do jogo, controlando as interações do jogador, cronômetro, verificação das respostas e para o proprio servidor.

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) e ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) Servem como o backend do jogo, permitindo o armazenamento dos rankings e fornecimento de dados necessários para o jogo, como as imagens das bandeiras e os países correspondentes.

E uma API propria, sem depender de APIs externas.

**Como Jogar:**

O jogador será apresentado a uma bandeira de um país.

Ele deve escrever o nome do país correspondente no campo de resposta.

Após cada resposta, o tempo é contabilizado e o jogo segue para a próxima rodada.

Ao final das 10 rodadas, o jogo exibe o desempenho do jogador com base no tempo total e número de acertos.

**Objetivo:**

O principal objetivo é acertar o maior número possível de países corretamente e no menor tempo, desafiando-se a melhorar a cada rodada.
