# The 4-Minute Jupyter Training

## Quick Start - Build Docker Container
1. Build docker image  
``` docker build . -t stats ```

2. Run docker image  
``` docker run -p 8888:8888 -v $(pwd):/home/jovyan/work stats ```

