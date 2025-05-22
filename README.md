# CabXplorer

This repository contains an example Codex environment setup.

## Setup Instructions

1. **Install Docker** - Follow the Docker installation guide for your platform: <https://docs.docker.com/get-docker/>
2. **Clone this repository**
   ```bash
   git clone <repo-url>
   cd CabXplorer
   ```
3. **Build the Docker image**
   ```bash
   docker build -t cabxplorer-env .
   ```
4. **Run the container**
   ```bash
   docker run -it --name cabxplorer cabxplorer-env
   ```
5. **Install additional dependencies** inside the container if required. Update `requirements.txt` to list them.
6. **Run Codex commands** inside the container.

Use `docker commit` if you need to save changes made inside the running container.
