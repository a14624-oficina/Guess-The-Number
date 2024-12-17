<h1> guess the number </h1>
Introdução e nome do jogador:

O jogo começa pedindo o nome do jogador, e usa esse nome durante o jogo para tornar a experiência mais personalizada.
Objetivo do jogo:

O objetivo do jogo é o jogador tentar adivinhar um número secreto gerado aleatoriamente pelo programa. O número secreto está entre 0 e 20.
Número de tentativas:

O jogador tem 6 tentativas para adivinhar o número correto. A cada palpite, o programa diz se o número secreto é maior ou menor do que o palpite.
Condição de vitória:

O jogador ganha se acertar o número dentro das 6 tentativas. O jogo termina quando o jogador adivinha corretamente ou quando esgotam-se as tentativas.
Perder a partida:

Se o jogador não adivinhar o número após as 6 tentativas, ele perde a partida, e o número secreto é revelado.
Jogar novamente:

Após o jogo terminar, o jogador tem a opção de jogar novamente. Se responder "sim" (ou "s"), o jogo reinicia. Caso contrário, o jogo termina e é feita uma despedida.

while tentativas > 0:

Este while garante que o jogador tenha um número de tentativas limitado. O jogo continua até que o número de tentativas seja 0.
print(f"Tens {tentativas} tentativa(s) restantes."):

Este comando imprime o número de tentativas restantes para o jogador.
palpite = input("Adivinha o número: "):

O programa pede ao jogador que insira um palpite, que será armazenado na variável palpite.
if not palpite.isdigit()::

Esta condição verifica se o palpite inserido não é um número (usando o método .isdigit(), que retorna True se a string contiver apenas números). Se não for um número, o jogo imprime uma mensagem de erro e continua com o próximo ciclo do loop (sem gastar uma tentativa).
continue:

O comando continue faz com que o loop pule para a próxima iteração, sem diminuir as tentativas, caso o input não seja um número válido.

Verificação do palpite:

Você já fez a verificação do palpite corretamente. Caso o palpite seja igual ao número secreto, o jogador é parabenizado e o jogo termina. Caso contrário, o jogo informa se o número é maior ou menor que o palpite.
Contagem de tentativas:

Cada vez que o jogador faz um palpite, o número de tentativas diminui. Se o jogador não acertar o número e não tiver mais tentativas, o jogo termina com a revelação do número secreto.
Jogar novamente:

Após o fim de cada partida, o jogador pode escolher se quer jogar novamente. Se o jogador digitar "sim", o jogo recomeça. Caso contrário, o jogo termina.

