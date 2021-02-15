run
`crontab -e`

insert
`@reboot sleep 60 && /usr/local/bin/docker-compose -f /opt/docker/nginx-proxy-manager/docker-compose.yml up -d`
