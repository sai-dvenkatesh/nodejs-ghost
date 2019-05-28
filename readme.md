# step - 1
check out ports 80,443,9000, 3306 are not in usage 
if so stop those services 
#step -2
git clone https://github.com/sai-dvenkatesh/nodejs-ghost.git
# step - 3
docker-compose up --build -d
# step - 3
hit browser with URL
yourdocker_host_ip
