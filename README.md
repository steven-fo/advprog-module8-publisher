a. How many data your publlsher program will send to the message broker in one run? <br>
According to main.rs and function main in that file, my publisher program will send 5 messages in one run. It can be seen from the number of publish_event function calls. <br>
b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?<br>
It means both subscriber and publisher are connecting to the same server. <br>

Running RabbitMQ
![image](https://github.com/steven-fo/advprog-module8-publisher/assets/119484321/99930658-4930-4839-a1e0-c5184b6e094e)

Subscriber terminal screenshot
![Screenshot (119)](https://github.com/steven-fo/advprog-module8-publisher/assets/119484321/91b4229a-adc3-4058-a6b1-b4b89ab342c5)
It can be seen from the image that there are 5 incoming messages that are caught from publisher.

Publisher terminal screenshot
![Screenshot (117)](https://github.com/steven-fo/advprog-module8-publisher/assets/119484321/a985d5f8-4059-4f2c-9abf-36bceb34b210)
The screenshot is taken after running cargo run in publisher

Chart screenshot
![image](https://github.com/steven-fo/advprog-module8-publisher/assets/119484321/4a015a5f-b01c-4be2-8068-dfd2baee246a)
The spikes in the second chart refer to the number of messages that were sent from the publisher.
