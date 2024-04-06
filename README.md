# Jifeng Chen's 4.1P: Building a simple calculator microservice

This is the Jifeng Chen's implementation of SIT323 4.1P

To utilize this demonstration, please follow the steps below:

1. **Firstly**, initiate the server by executing the following command:
    ```bash  
    node server.js
    ```
   This command will launch a Node.js process on the server, listening on port 3040.

2. **Next**, open your preferred web browser and navigate to the following address:  
   http://localhost:3040/add?n1=5&n2=10
   http://localhost:3040/subtraction?n1=5&n2=10
   http://localhost:3040/multiplication?n1=5&n2=10
   http://localhost:3040/division?n1=5&n2=10

   This action will prompt the server to execute the corresponding arithmetic operation

3. **Finally**, the server will respond with the answer of the arithmetic operation
