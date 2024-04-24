#Tutorial 8
##Nabiilah putri Safa - 2206030426
-----------------------------------

a. How many data your publlsher program will send to the message broker in one
run?

The publisher program in the provided code will send five messages to the message broker in one run. Each call to the publish_event function sends one message, and there are five such calls in the main function. Therefore, the publisher program sends a total of five UserCreatedEventMessage instances to the message broker in one run.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

The publisher utilizes the same URL as the one found in the subscriber program because the URL "amqp://guest:guest@localhost:5672" is essentially a standard link used to connect to a message broker using the AMQP (Advanced Message Queuing Protocol). When the same URL is used in both the publisher and subscriber, these two programs will connect to the message broker on the same machine, with identical credentials and port numbers. This ensures that the publisher can publish messages to the same message broker instance where the subscriber is subscribed.

![Screenshot 2024-04-24 144924](https://github.com/nabiilahputri13/html-portfolio/assets/124870275/15d05df0-c857-4e35-9bbe-2299fe788da8)

![Screenshot 2024-04-24 153754](https://github.com/nabiilahputri13/html-portfolio/assets/124870275/c04f260a-6bec-4378-91da-486963efafea)

![Screenshot 2024-04-24 153922](https://github.com/nabiilahputri13/html-portfolio/assets/124870275/63b90f68-06e7-43ff-81a5-991e57448dbe)