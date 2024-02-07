
## Required installations:

* https://1drv.ms/f/s!AqT2YEB97-1RgP8MtsMPqoOGsq4ddg?e=IocXv0
  * Follow instructions in installation_steps.pdf for installation of virtual box, Ubuntu
* Paraview
* docker (get.docker.com)
  * docker image pull ghcr.io/acrlakshman/openfoam-v2306:opt

## Launch

docker container run --name openfoam2306-workshops -v $(pwd)://home/developer/OpenFOAM/developer-v2306/run -it ghcr.io/acrlakshman/openfoam-v2306:opt bash

create `solvers/bin` inside `run`
export PATH=$PATH:$FOAM_RUN/solvers/bin

## Meeting link:
* https://teams.live.com/meet/956185859972?p=squ9g3dkz1H85PNg
