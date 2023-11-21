# Colisao-Cena

##
Trabalho feito por Cauã Magalhães Leão e Guilherme Matos Oliveira

Este trabaho foi na intenção, de aplica colissores, trigger e kinematic, a uma cena, nas quais utilizadas foram:
 - Static Collider
 - Rigidbody Collider
 - Static Trigger Collider
 - Rigidbody Trigger Collider
 - Kinematic Rigidbody Trigger Collider.

# Static Collider
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/e6b5488a-93c5-4e74-b6a8-e1f304c50b2b)

Foram aplicados apenas os Box colliders a esses cilidros, para o personagem não os atravessar, fazendo o papel de Obstáculos no Jogo.

# Rigidbody Collider
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/bc2c7902-69bd-4786-bcac-07d977e9ae99)


O Rigidbody Collider, foi aplicado no Personagem que o Jogador irá controlar, fazendo o trabalho de adicionar massa ao personagem, na ajuda das colisões a outro objetos e atribuição de massa para a movimentação do personagem.

# Static Trigger Collider
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/af6f4679-bcf5-482e-a70f-9bc7db6dc5b3)

O Static Trigger Collider, foi associado a um Empty Object, somente para ativar um Trigger, fazendo quando o Personagem chegar no limite posto no Trigger, ele irá ativar o mesmo para ativar uma mensagem de "Você Venceu!". Seguindo um Código abaixo.

![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/3c898418-f803-4dc7-82f1-59bc3e0147f2)

Fazendo exatamente o seu objetivo, de ativar uma mensagem quando o Personagem chegar numa determinada distância, e quando o Personagem, sair da distância do colisor a mensagem irá sumir, até ele retornar ao collider novamente.

# Kinematic Rigidbody Trigger Collider.
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/6ec191b7-7d94-4acd-8043-f8220b061e92)

Essa parede foi ativada o Trigger e o Kinematic, para o Personagem poder atravessar ela, a kinematic faz com que o objeto perca a física que está aplicada a ele, permitindo que isso seja feito.

##

## Atualizações para acréscimo de Menu e HUD

## Tela de Menu

![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/bf39f961-3b17-484e-98bc-424000647bc0)

Nesse menu criei um canvas, para por o título do jogo, depois usando a opção do UI no GmaeObject, para adicionar o Text Legacy, e o Button, depois só basto fazer a estilização dele, e adicionar um código simples de quando clicasse no botão, mudava a cena na qual ira mudar, seguindo exemplo abaixo.

# Script 
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/54b99bd3-151c-4568-8595-4e0ecb8bc06c)

Foi criado um public void para carregar a fase, não necessitando void start nem update, pelo que ele irá fazer, após isso só foi necessário colocar a fase na qual será trocada, usando "using UnityEngine.SceneManagement" instanciado lá em cima, e outro public void, para sair do jogo. Os dois que serão botões difentes do Menu.

## Temporizador
![image](https://github.com/GuilhermeM777/Colisao-Cena/assets/127865701/85812d4c-efe1-4332-b7c4-787638d84744)

Para fazer esse simples temporizador, que vai iniciar quando a cena foi trocada, o objetivo é que o personagem chegue antes do tempo, pois se não, o jogo voltará pro menu, mostrando que ele perdeu, só bastou declarar as variáveis do horário, iniciando em zero, e tendo que ir até 10 segundos.

## Link do Jogo (Atualizado)
https://drive.google.com/file/d/1IHnZiXBXlyOA9UftVwEPN1mkOhgKquff/view?classId=f0643abd-0e31-4c6a-be01-3711a471dd39&assignmentId=26eab67f-9352-47b6-82fd-cd5eeae25fa2&submissionId=c26ab857-8ade-56d4-5107-df0e49216b00

## Video de Demonstração (Atualizado)
https://youtu.be/V7jSVpjKaA8?si=piZlFKB7Evb-vecc
