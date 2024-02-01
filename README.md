# deepstream-test

This repository is intended for test regarding Nvidia Deepstream docker containers.

- ***docker*** - containers docker compose configs for a management stack (dockge, portainer and glances) together with 3 stacks for deepstream devel, samples and triton
- ***project*** - config files for the deepstream-app
- ***samples*** - container video samples for detection

# Usage

Start the nvidia-deepstream-triton-devel container, mount the project folder into the container an run:

```
deepstream-app -c /path/to/config/file.txt
```