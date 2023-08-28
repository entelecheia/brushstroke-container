# brushstroke-container

This repository contains code to containerize the [Neural Brushstroke Engine](https://github.com/nv-tlabs/brushstroke_engine) using Docker.

## Contents

- `Dockerfile` - Builds the Docker image with Neural Brushstroke Engine and dependencies
- `entrypoint.sh` - Startup script to launch the drawing interface
- `models/` - Contains pretrained models
- `config.yaml` - Configuration file for canvas size, brushes etc.
