# ColisoresUnity
## Autores
Filipe Custodio Gonçalves e Gabriele Batista Sousa

## Descrição
Esse é um trabalho solitado em aula solitado pela orientadora Aline Firmino, com objetivo de utilizar tipos diferentes de colisores.

## Pesquisa sobre colisores:
(pesquisa)

## Requisitos 
Para ver a cena é necessario o Unity com versão `2021.3.6f1`

## Instalação
1. Clonar o projeto `https://drive.google.com/file/d/10r5fIHSmw27BPhso82r9C4f91-8dO5Hg/view?usp=sharing`
2. Abrir o projeto no Unity.

## Desenvolvimento 
Para criar esse projeto foi feito os seguintes passos:
1. Montar o labirinto com as paredes contentedo __Static Colider__:
 <img src="img/7.png"/>

3. Colocar o jogador que vai ser programado com __RigidBody collider__:
 <img src="img/1.png"/>

4. Criar o prefab da flecha para colidir com o personagem utilizando __Kinematic RigidBody Collider__:
 <img src="img/2.png"/>

5. Criar placa de pressão para instanciar a flecha em contato com o jogador considerando o __Static Trigger Collider__:
 <img src="img/4.png"/>

6. Adicionar pontos de verificação de checkpoint com um __RigidBody Trigger Collider__:
  <img src="img/5.png"/>

7. Criar portas com cores diferentes ligadas a botões(placas coloridas) __Kinematic RigidBody Collider__:
  <img src="img/6.png"/>
 <img src="img/3.png"/>
