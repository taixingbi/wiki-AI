* listen()  
  
Whenever an HTTP request is received,it handles the request and returns some response. 

    server.listen( {
        handleRequest: function( request, response ) {
            // handle the request...
        },
        handleError: function( err ) {
            // handle the error...
        }
    } );

http server will call this function every time it receives an HTTP request
