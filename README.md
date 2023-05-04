Download Link: https://assignmentchef.com/product/solved-csc361-lab-1-http-and-web-server
<br>



<table width="789">

 <tbody>

  <tr>

   <td width="789">Determine the IP address of the host that is running the server (e.g., 128.238.251.26 ). Then run a working version of your server program server.py . From another host, open a browser and provide the corresponding URL. For example:

    <table width="639">

     <tbody>

      <tr>

       <td width="639">1        http://128.238.251.26:6789/hello.html</td>

      </tr>

     </tbody>

    </table>hello.html is the name of the file you placed in the server directory, which is also included. <strong>Note </strong>also the use of the port number after the colon. You need to replace this port number with whatever port you have chosen in your server code. In the above example, we have used the port number 6789 . The browser should then display the contents of hello.html . If you omit :6789 , the browser will assume port 80 and you will get the web page from the server only if your server is listening at port 80 . (This is <strong>not</strong> recommended.) Then try to get a file that is not present at your server. You should get a 404 Not Found message. RUNNING THE CLIENTInstead of using a browser, write your own HTTP client to test your server. Your client will connect to the server using a TCP connection, send an HTTP request to the server, and display the server response as an output. You can assume that the HTTP request sent is a GET method. The client should take command line arguments specifying the server IP address or host name, the port at which the server is listening, and the path at which the requested object is stored at the server. The following is an input command format to run the client.

    <table width="639">

     <tbody>

      <tr>

       <td width="639">1         client.py 128.338.251.26 6789 hello.html</td>

      </tr>

     </tbody>

    </table> </td>

  </tr>

 </tbody>

</table>