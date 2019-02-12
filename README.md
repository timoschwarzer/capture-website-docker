# capture-website-docker
Dockerized version of sindresorhus/capture-website-cli

## Usage
```bash
docker run --cap-add=SYS_ADMIN timoschwarzer/capture-website-cli capture-website --delay=3 https://timoschwarzer.com > screenshot.png
```
