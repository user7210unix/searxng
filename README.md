<img src="https://upload.wikimedia.org/wikipedia/commons/a/a3/SearXNG_logo.svg">

- Docker Installation
  ### Install Docker, BuildX and Compose
  ```sudo pacman -Syu docker docker-buildx docker-compose```

  ### Allow your user to run Docker commands without root access
  ```sudo usermod -aG docker $USER```

  ### Ensure the Docker daemon is started and starts on boot
  ```sudo systemctl enable --now docker.service```

- installation 
  [Docker searxng](https://docs.searxng.org/admin/installation-docker.html#compose-instancing)

- Configuration File
  [settings.yml](https://github.com/user7210unix/searxng/blob/main/settings.yml)
- file location ```~/searxng/core-config/settings.yml```
