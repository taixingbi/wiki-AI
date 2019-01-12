* listen()  

server.listen( function( request, response ) {
    response.write( 'Hello' );
    response.end();
} );

http server will call this function every time it receives an HTTP request
