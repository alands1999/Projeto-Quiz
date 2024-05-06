# Projeto Quiz

O Quiz de Conhecimentos Gerais é um projeto desenvolvido em JavaScript, utilizando a plataforma Node.js para execução direta no terminal. Para interação com o usuário, é empregada a dependência readline-sync, permitindo a entrada de dados de forma síncrona.

O código é estruturado em torno de uma matriz de objetos questoes, cada objeto representando uma pergunta específica com sua respectiva resposta. As perguntas são selecionadas aleatoriamente por meio da função questRamdom, que embaralha a matriz de perguntas. Em seguida, as 10 primeiras perguntas são selecionadas pela função questionsSelected.

Para exibir as perguntas, existe a função teste, que itera sobre as perguntas selecionadas, exibindo-as no terminal e solicitando as respostas do usuário. Se a resposta estiver correta, o programa exibe "Resposta Correta!" e incrementa o contador de acertos. Caso contrário, exibe "Resposta errada!" e incrementa o contador de erros.

Após responder todas as perguntas, o código utiliza uma série de condicionais if para determinar a mensagem final com base no desempenho do jogador. Se o número de acertos for menor ou igual a 3, é exibida a mensagem "OH não! Tente mais uma vez!". Se estiver entre 4 e 6, a mensagem será "BOM TRABALHO! pratique um pouco mais!". Para acertos entre 7 e 8, a mensagem será "MUITO BOM! você acertou a maioria!". E finalmente, se o jogador acertar 9 ou 10 perguntas, a mensagem será "Excelente! você é um verdadeiro Expert!".

O código conclui exibindo o nome do jogador, sua pontuação final e a mensagem correspondente ao seu desempenho.

Este projeto proporciona uma experiência interativa e desafiadora, testando o conhecimento do jogador em uma variedade de tópicos históricos e culturais.

## Projeto: 

![1](https://github.com/alands1999/Projeto-Quiz/assets/150439841/a1eee530-b06b-4d7b-ba0e-0e4814316675)
