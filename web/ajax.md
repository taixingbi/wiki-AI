### ajax
when an event happen     
step 1 in browse, create request object and send request   
* XMLHttpRequest
  * status
    * 100 Continue
    * 101 Switching Protocols
    * 200 OK. The request has succeeded
    * 201 Created
    * 202 Accepted
  * readyState    
    * 0	UNSENT	Client has been created. open() not called yet.
    * 1	OPENED	open() has been called.
    * 2	HEADERS_RECEIVED	send() has been called, and headers and status are available.
    * 3	LOADING	Downloading; responseText holds partial data.
    * 4	DONE
    


step 2 in server, process request, and create a reqonse and send back to a browse     
step 3 in browse, process returned data using js and update page content.      

![alt tag](https://www.w3schools.com/xml/ajax.gif)


### all types
* jquery  
* xml  







