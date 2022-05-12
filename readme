This widget With this widget you will be able to create surveys with the question of your choice and with four possible answers. 
You can send this survey to as many users as you want. To do this, you will have to use postman to send the messages. 
You will have to fill in the following json where:
	1. Number: the number of the creator of the poll.
  2. numbers_poll: the numbers of the users you want to participate in the poll,.
  3. q1: the question of the poll.
  4. a1: first answer.
  5. a2: second answer.
  6. a3: third answer.
  7. a4: fourth answer.
The json will look like this:
{
    "number":"34000000000",
    "numbers_poll": ["34000000000", "34000000000", "34000000000"],
    "q1":"What is your favourite season?",
    "a1":"Spring",
    "a2":"Summer",
    "a3":"Autumn",
    "a4":"Winter"
}
The user will have to send a POST request to the following server: https://poll.wardcampbell.com/chatwith-endpoint.

After sending the request, users should receive the survey message on whatsapp. Users will have to reply with the number that matches the chosen answer. 
In the case of the json above, if their favorite season is summer they will answer with a 2.
Finally, after two hours all users who have participated will receive a message with the results of the final poll.
