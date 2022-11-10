# rabbitMQ-microservice
Демонстрация, как работать c RabbitMQ  

Сначала запустить докер   
docker run -d --hostname demo-rabbit -p 5672:5672 -p 15672:15672 --name demo-rabbit rabbitmq:3-management  


consumer - слушатель (тот, который принимает сообщения от брокера и выполняет задачи)  
producer - (тот, кто отправляет сообщения в брокер)  

npm i  
npm run start:dev  

В браузере можно открыть станицу монтиринга rabbit  
http://localhost:15672/  
guest  
guest  

при открытии страницы   
http://localhost:3000/  
в брокер отправится 5 сообщений (с задержкой в несколько секунд)  