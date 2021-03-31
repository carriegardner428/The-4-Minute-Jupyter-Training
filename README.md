# The 4-Minute Jupyter Training

## Quick Start - 
1. Build Docker Container for Jupyter
2. Open The 4-Minute Jupyter Training notebook


### Build Docker Container
1. Build docker image  
``` docker build . -t stats ```

2. Run docker image  
``` docker run -p 8888:8888 -v $(pwd):/home/jovyan/work stats ```

