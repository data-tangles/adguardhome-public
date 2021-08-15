# adguardhome-public
AdGuard Home Compose File

The official Docker guide at AdGuard home seems to lack a compose file for deplyoying in stacks and Swarms. I simply converted the existing docker run command into a compose file and added the "latest" tag to get the latest version when redeploying. Feel free to copy and use for your own setups. 

Steps to run: 

- Copy the compose file to your Docker host and rename the file to docker-compose.yml
- Edit the values under Environment:TZ and volumes: to match your locale and storage setup
- Run docker-compose up -d

The original setup is available at: https://github.com/AdguardTeam/AdGuardHome/wiki/Docker
