# Agents instructions

- Starting of all docker containers is handled by one single template in roles/plex/templates/opt/plex/docker-compose.yml
- For each container add a file to roles/plex/tasks link it in roles/plex/tasks.main.yml
- Variable defaults go to roles/plex/defaults/main.yml
- Prefix variables with the container it's used for
- Sort the variables alphabetically