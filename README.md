a. How many data your publlsher program will send to the message broker in one run? <br>
According to main.rs and function main in that file, my publisher program will send 5 messages in one run. It can be seen from the number of publish_event function calls. <br>
b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?<br>
It means both subscriber and publisher are connecting to the same server. <br>

Running RabbitMQ
![image](https://github.com/steven-fo/advprog-module8-publisher/assets/119484321/99930658-4930-4839-a1e0-c5184b6e094e)
