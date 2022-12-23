# Propostas para o desenvolvimento do jogo
## Estruturação lógica em JavaScript

![image](https://user-images.githubusercontent.com/101356855/202557783-09dda643-df5e-42be-96bf-91a94ad73d4c.png)

## Diretrizes

1- Gerar um número aleatório entre 1 e 100.

2- Gravar o número do turno que o jogador está. Iniciar em 1.

3- Dar ao jogador uma forma de adivinhar o número.

4- Após a tentativa ter sido submetida, primeiro gravar em algum lugar para que o usuário possa ver as tentativas anteriores.

5- Depois, verificar se o palpite está correto.

6- Se estiver correto:

    i. Escrever mensagem de parabéns.
    
    ii. Impedir que o jogador insira mais respostas (isso pode bugar o jogo).
    
    iii. Mostrar controle que permita ao jogador reiniciar o jogo.
    
7- Se o palpite estiver errado e o jogador ainda tem turnos sobrando:

    i. Dizer ao jogador que ele está errado.
    
    ii. Permitir que ele insira outra resposta.
    
    iii. Incrementar o número do turno em 1.
    
8- Se o jogador está errado mas não tem turnos sobrando:

    i. Dizer ao jogador que o jogo acabou.
    
    ii. Impedir que o jogador insira mais respostas (isso pode bugar o jogo).
    
    iii. Mostrar controle que permita ao jogador reiniciar o jogo.
    
9- Quando reiniciar, tenha certeza de resetar todas as variáveis e a interface do jogo, então volte para o passo 1.

# Fonte
https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/A_first_splash

