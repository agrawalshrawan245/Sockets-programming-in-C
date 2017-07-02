# Sockets-programming-in-C
Awesome server and client development in C language

# How to use?
  1) Compile server.c (in my case, I use gcc compiler, however you might use any C compiler)
  2) Execute the compiled server from terminal:   ./server
  3) Compile client.c
  4) Execute the compiled client from terminal

If above steps was successfully done, then client may be able to write to server.

# Example
  alpha_bank.c is a server side for banking system. To use it, the following steps are required:
  
  1) Compile and execute alpha_bank.c
  2) The IP and port number should be printed on the terminal of executed alpha_bank.c:
  3) Open another terminal
  4) Using telnet service, connect to the IP and port number, for example, just type:
      
      telnet 127.0.0.1 8888
  5) Now you are using a simple ATM, there are two bank accounts with card numbers and balances:
  
        -  char* card_number1="0000 0000 0000 0000";
        -  unsigned int balance1 = 1000; 
        -  char* card_number2="1000 0000 0000 0000";
        -  unsigned int balance2 = 1500;
  6) ATM asks for card number, just enjoy above numbers
  7) Test other functions: BALANCE, WITHDRAW, DEPOSIT between two clients

Give some stars!
