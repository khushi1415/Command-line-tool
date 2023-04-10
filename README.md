# Command-line-tool
A Command line tool for working with JSON Web Tokens (JWT)

This tool will help in session management and secure authentication. Server generates an 
"access Token", encrypting the "user Id" and "expires in", with the ACCESS_TOKEN_SECRET, and sends the 
"access Token" to the browser (client side). The browser (client side) receives the "access Token" and saves 
it on the client side. The "access Token" is included in every subsequent request to the server
