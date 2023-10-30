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

# Vídeo demonstração
Abaixo um vídeo mostrando a funcionalidade do jogo.
https://youtu.be/0-pKKEdIxZM
