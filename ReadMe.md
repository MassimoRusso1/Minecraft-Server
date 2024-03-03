Open this Repository in a codespace
Run the server in the Terminal with following command:
java -jar server.jar
After run ngrok for the public hosting with this command in the terminal:
./node_modules/.bin/ngrok authtoken 2dBNIPsuNGaeNC9rVYHCyRoqdD3_68RZJhCp3vrHxJEi4ZWPT
Dann:
./node_modules/.bin/ngrok tcp 25565
It will appear a window in your browser copy the address without the tcp//
Put it in your mincraft server ip in your game