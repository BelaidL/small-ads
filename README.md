# small-ads
 ## Authors
 * Belaid Lagha
 * Idir Lankri

 ## Compilation

 * Type in a terminal:
      ```$ cd belaid-idir/```
      ```$ make```

 ## Execution

  ### Start the server
   * Type in a terminal:
      ```$ ./server [<backlog>]```
     
       where <backlog> is the maximum number of pending incoming
       connections.  If not specified, its value is 100.
   
  ### Start a client 
   * Type in a terminal:
      ```$ ./client <server-address>```

       A log file 'client.log' stores the different messages exchanged on
       the network.  It can be used for debugging purpose.
