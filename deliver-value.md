🔥 Entrega de valor 🔥

Neste texto, vou compartilhar sobre uma das funcionalidades que desenvolvi e que mais me encantou, já que abrange diversos aspectos da computação, incluindo a Matemática.

Contextualização do problema:
Em um cenário globalizado, indivíduos recebiam Push Notifications que não faziam sentido em determinadas regiões.

Em um cenário hipotético, a notificação é sobre venda de veículos em Porto Alegre mas alguns usuários da base de dados são de São Paulo e recebiam a notificação. 
Dado esse problema voltava muitos como, usuários desativando notificações (um dos principais meios de comunicação b2c).

Objetivo da entrega:
Disparar Push Notifications geolocalizada.

Após termos essas informações minuciosas quando o usuário fazia o login no app (com o consenso) pegávamos o ip e com o ip consultávamos uma api externa para pegar sua latitude e longitude.

Com a latitude e longitude verificávamos se o cliente estava próximo da região da venda de veículos (100km). Se fosse positivo, enviávamos a push notification para o cliente ou se desse negativo não enviava.



 #comunication #engenhariadesoftware #matematica
