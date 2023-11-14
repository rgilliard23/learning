# Docker Images


## Summary

### Like blueprints for containers
1. Runtime environment
2. Application Coede
3. Dependencies
4. Extra Configuration (e.g. env variables)
5. Commands

______

## Docker Images
### Images are made up from several "layers"

1. Parent Image includes the OS & sometimes the environment
2. Other layer's are built on top of the parent image and can contain source code and dependencies.
3. The final layer is composed of Commands
